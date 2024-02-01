# Projects Deep Learning No. 1

This is the project No. 1 in Deep Learning subsidiary of Machine Learning category. The prediction built in this project is binary classification, and one of the first stepping stones to more complex neural networks down the road.

The purpose of this notebook is to build a classification model using neural networks to predict a student's chances of admission into UCLA. The data set contains 8 features:
  * GRE Scores: (out of 340)
  * TOEFL Scores: (out of 120)
  * University Rating: It indicates the Bachelor University ranking (out of 5)
  * Statement of Purpose Strength: (out of 5)
  * Letter of Recommendation Strength: (out of 5)
  * Undergraduate GPA: (out of 10)
  * Research Experience: (either 0 or 1)
  * Chance of Admit: (ranging from 0 to 1)

**First: Understand your data**

The importance of this notebook is to focus on the data pre-processing steps that involve exploratory data analysis (EDA) and data visualization. EDA will help us understand each attribute characteristics and learn the statistical relationships among the attributes, while data visualization will help us spot trends and patterns, as well as, viewing these relationships on different plots.

**Second: Data preparation (Pre-processing)**

After understanding the dataset attributes and their relationships with each other and how they can affect the results, we need to identify the attributes variables type and how to clean them up and provide appropriate treatment to these data points before feeding the data into the neural networks models.

**Third: Model building**

Once the data is treated and ready to be fed into the machine, there are many factors of the models we need to look  at including the number of hidden layers, number of neurons, activation functions, optimizers, weights and biases, etc. These are the features of the models we called "hyper-parameters".

Note: This is a binary classification problem, as in there are only two output of this model: 0 or 1 (whether the student is admitted or not), so we will apply the ``` binary_crossentropy ``` as the minimizing loss function, while choosing ``` adam_max ``` as the popular optimizer.

The output here that we're getting is the accuracy rate, representing how accurate the model I built is.

**Fourth: Model training**

Keep 10% of the training data for validation. You can read further when downloading the files and upload them on Google Colab for further usage.
