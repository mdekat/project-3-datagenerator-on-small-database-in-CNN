# project-3-Datagenerator on small database in CNN

The dataset used in this project is the Rice Leaf Disease dataset on UCI ML Repositories which can be found here: http://archive.ics.uci.edu/ml/datasets/Rice+Leaf+Diseases.

Because of the small dataset I experimented with a ImageDataGenerator. I varied the various parameters of the Imagegenerator (without keeping track) to find the ones that gave the best results.

Adadelta was the best Optimizer to use.

## The notebook file contains the following steps:
0. import libaries
1. load data, prep data and prepare the ImageDataGenerator
2. create and compile model
3. train model
4. evaluate model

## Results
Results can be found on the bottom of the Notebook file. Accuracy gets up to 90%.

I have not been able to find ways to visualize what parts of the images are triggers for classification. I would be much obliged if anyone can help me do that. 
