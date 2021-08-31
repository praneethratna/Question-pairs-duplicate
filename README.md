# Question pairs duplicate Identification
This Repo contains the model for Identification of Duplicate Questions using keras and attention.

## About the dataset


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
