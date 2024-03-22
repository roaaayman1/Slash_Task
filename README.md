# Slash_Task
* To achieve this taks, you will be given a data set that consists of 700  images before data augmentation and 3341 image after it to train your model and to tune your hyperparameters. However, feel free to extend it by collecting new images or by using data augmentation techniques.
* Setup the environment: Thie first step consists of setting the environement and downloading the data.
* Preprocessing: The second step is a preprocessing step that consists of resizing, plitting, and piping the input data.
* Exploring the data: The third step consists of a simple data exploration step where you will see samples of the data and some statistics to help you in understanding the data.
* Designing the model: The forth step consists of designing an architecture for the task.
* Traning: The fifth step consists of starting the training process.
* Monitoring: The sixth step consists of monitoring the traning process to investigate possible overfitting.
* Compiling the model by defininf an optimizer, a loss function, and the metrics to be used for monitoring the traning ===> model using Stochastic Gradient Descent optimizer with a learning rate of 0.01 and momentum of 0.7, After applying Parameter tuning ,Categorical Crossentropy as the loss function, and accuracy as the evaluation metric.
* The evaluation of the model's performance across various categories reveals mixed results. While it demonstrates strong precision and recall values for categories like Access, Home, and Nutrition, indicating its effectiveness in correctly identifying instances within these classes, it struggles with categories such as Artifacts, Beauty, and Games, where the precision and recall scores are notably lower. This suggests that the model may require further refinement or additional training data to improve its ability to accurately classify instances within these categories. Overall, the weighted average F1-score of 0.74 and accuracy of 0.77 indicate a moderate level of performance across all categories, leaving room for improvement in specific areas to enhance the model's overall effectiveness.
