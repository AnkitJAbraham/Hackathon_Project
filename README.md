<h1>Problem : E-commerce Credibility Detection<h1>

We worked on an application that checks the reviews of a product listed for sale on an e-commerce platform, to detect whether it is a fraudulent listing, or if it is genuine, if so, it checks for its credibility as well(how well has the product been received by customers and its "worth" or usefulness) .This would be implemented by two separate machine learning algorithms using sentiment analysis, with Tensorflow from <b>Intel AI Analysis Kit/oneAPI<b>.

<h3>Part 1 - Input of Product SKU, gathering all its consolidated reviews and grouping them together.<h3>

<h3>Part 2 - Checking for fraudulence in product listing :<h3> 
         Machine Learning model used - DistilBERT model, based on BERT (Bidirectional Encoder Representations from Transformers)
         Dataset - Fake Reviews Dataset from osf.io
         Here, we check if each review is fake or not, classified by the SDG model, and the total count of genuine and fake reviews is taken and compared to label it as fraudulent or not.
         
         
<h3>Part 3 - Checking for credibility in product listing : <h3>
         Dataset: Amazon reviews dataset from Kaggle.
         Machine Learning model used - Stochastic Gradient Descent Classifier
         Once we determine if a product is genuine, its credibility is also inferred, by checking for each review and its 'value', whether it is a positive or negative review. On comparing the overall ratings, we can determine if the product is credible, shown over a rating system.
         
         
 <h2>Team Name : The Spammers<h2>
 
 <h4>Team Members : <h4>
 
 Ashwin Saji
 Ajith Bobby
 Alwin Shibu
 Ankit John Abraham
 
 Submitted for the Slash Key 2.0 Hackathon, Organised by IEEE CS Kerala Chapter in association with Intel.
