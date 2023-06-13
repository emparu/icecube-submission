# icecube-submission
Submission for the Kaggle IceCube - Neutrinos in Deep Ice competition
35th place solution (ensemble of public pre-trained models)

I used the Graphnet baseline submission, and Robin Smits' ensemble of 3 LSTM
I created an ensemble model. It was trained with the outputs of the 4 models from batches 520-525, and the number of pulses in each event

![Alt text](diagram1.png?raw=true "Title")

The 3 outputs are (x,y,z) coordinates, the model was trained using the Mean Angular Error loss.

createEnsemble.ipynb is the notebook used to train the ensemble

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/emanuelruzak/ensemble2) -->

This is the submission (submission.ipynb)


[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/emanuelruzak/submissionfinal2) -->

lstmviewicecube.ipynb is a notebook to visualize the outputs of the LSTM models
[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/emanuelruzak/lstmviewicecube) -->


