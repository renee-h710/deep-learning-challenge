# deep-learning-challenge

Overview:
This analysis was to assist Alphabet Soup in determining what makes a funding candidate successful. 

Results:
Data Preprocessing:
Using their charity data, I looked at all aspects of the applications except the EIN and applicant's name. Excluding those items, the rest were used as features for the model. The target for the model was whether or not the applicant was sucessful.

Compiling, Training, and Evaluating the Model:
In total: my model contains two hidden layers with 8 neurons each. For the input and hidden layers, I used the relu activation, and sigmoid for the output layer.
Unfortunately, I was only able to achieve about a 71% accuracy for the model despite changing several aspect. I increased the number of epochs to train the data, expanded the number of layers and neurons, and changed the activation types.

Summary:
Overall, there does seem to be a way to predict success for an applicant, but my model as it currently stands will only be accurate 71% of the time. With more data or perhaps a different model, I could predict with better accuracy.
