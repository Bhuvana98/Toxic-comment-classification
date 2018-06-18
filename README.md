# Toxic-comment-classification
Identify and classify toxic online comments
Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

In this competition, we’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. we’ll be using a dataset of comments from Wikipedia’s talk page edits.
Link to the kaggle competition- https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge .
Datasets can be downloaded from the link above.
## Results
I have used Bidirectional LSTM with two fully connected layers. I added some dropout to the LSTM since even 2 epochs is enough to overfit.
This has generated  an accuracy of about 98.08%.
