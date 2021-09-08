# Question pairs duplicate Identification
This Repo contains the model for Identification of Duplicate Questions using keras and attention.

## About the dataset

Quora's first public dataset is related to the problem of identifying duplicate questions. At Quora, an important product principle is that there should be a single question page for each logically distinct question. For example, the queries “What is the most populous state in the USA?” and “Which state in the United States has the most people?” should not exist separately on Quora because the intent behind both is identical. Having a canonical page for each logically distinct query makes knowledge-sharing more efficient in many ways: for example, knowledge seekers can access all the answers to a question in a single location, and writers can reach a larger readership than if that audience was divided amongst several pages.
**This dataset is based on actual data from Quora and will give anyone the opportunity to train and test models of semantic equivalence.**

There are over 400,000 lines of potential question duplicate pairs. Each line contains IDs for each question in the pair, the full text for each question, and a binary value that indicates whether the line truly contains a duplicate pair.

Here are the top 5 data values:
<div align='center'>
  <img src = "https://github.com/praneethratna/Question-pairs-duplicate/blob/master/data-image.png" alt = "drawing"/></br>
</div>

Information taken from https://www.kaggle.com/quora/question-pairs-dataset

## Model Architechture
<div align='center'>
  <img src = "https://github.com/praneethratna/Question-pairs-duplicate/blob/master/model.jpeg" alt = "drawing" width = "900" height = "900"/></br>
</div>

<hr>

## Further Inference
<ol type = "1">
  <li>This model still has the problem of increasing validation loss after about 2-3 epochs ie the model is overfitting a bit but validation accuracy is fine.</li>
  <li>Pre trained Embeddings like GloVe can be tried to decrease validation loss.</li>
  <li>Text preprocessing has not been done properly which also needs to be handled.</li>
  <li>A different model architecture without Attention can also be tried.</li>
</ol>  
