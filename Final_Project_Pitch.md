## Final Project Elevator Pitch -- Michael Malione

### Project Statement and Goal
For my Final Project, I'm going to design and build an entry for the Kaggle Competition entitled "Diabetic Retinopathy Detection".
* http://www.kaggle.com/c/diabetic-retinopathy-detection

The goal of this project is to analyze digital retina images and create a learning model that predicts a staged diagnosis of the condition, which will be scored according to the quadratic weighted kappa. This metric measures the agreement between two ratings. My machine ratings will be compared to diagnostic ratings that were compiled manually and provided with the dataset.
* http://www.kaggle.com/c/diabetic-retinopathy-detection/details/evaluation

### What question or questions do I hope to answer?
The question I hope to answer is whether I can develop a learning model that achieves results that are good enough to place me well on the competition's Leader Board. I'm eager to see how high of a kappa score I can achieve, and given my prior domain specific experience with computer grahics, image processing, and computer vision, I'm hoping to build a system that is actually quite effective. For sake of the final project, getting such a system up and running, and going through the steps of training and validating it, will be a constructive experience.

### What data set do I plan to use, and how you will obtain the data?
The data set is provided in the Kaggle competition. It consists of some 44,350 pairs of color retinal scan images, each pair from an individual who has been diagnosed for DR on the integer scale from 0 to 4. Given that there is some 95 GB of data here, I'm expecting to use AWS to run much of the analysis. A big part of this project will entail feature engineering, and even though this project won't involve typical munging as we've learned it in class, I'll need to write custom image processing software to detact and extract relevant features from the images, so there will plenty of clean-up code required.

### What type of machine learning problem is this? (from our 2x2 matrix)
This is a classification problem, supervised and categorical.

### Why did I choose this project?
* I'm interested in applying data science to areas of medicine.
* I have relevant domain specific experience.
* The data set is large and interesting.
* The project has a really good machine learning component to it.
* The project has relevance and solves a real outstanding problem.
* There's a pot of gold at the end of the rainbow if I do really, really well. 
