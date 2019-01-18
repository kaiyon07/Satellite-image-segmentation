Eye in the Sky Competetition



How to Generate predictions for the test data shared online?

The predictions are already generated. Open the folder 'gen_test' to see the predictions. 

How to generate new predictions?

Copy your images for which you want to generate the predictions into the folder 'test_x'

Run the ipython notebook 'Generate_Predictions.ipynb'

The predictions will be in the folder gen_test


How to train on a new dataset?

Copy your train images to the train_x and the corresponding labels to train_gt

Now execute the 'Pre_Processing.ipynb'

Now execute the "K-Fold_Final_Model.ipynb"

Now execute the "Computing_Metrics.ipynb" to see the performance of the algorithm with leave one out cross validation on the training data.


