# modeling_facial_recognition_Datacamp

### Create a facial recognition model to determine whether Arnold Schwarzenegger appears in an image

### Problem description:
The team's mission is to deploy AI-driven solutions that can accurately distinguish between images of notable personalities and the general populace, enhancing the personal security of such high-profile individuals. You're to focus on Arnold Schwarzenegger, a figure whose accomplishments span from bodybuilding champion to Hollywood icon, and from philanthropist to the Governor of California.


### Data 
The data was provided in Datacamp and was added to this repository. The dataset contains processed facial image data derived from the "Labeled Faces in the Wild" (LFW) dataset, focusing specifically on images of Arnold Schwarzenegger and other individuals not identified as him


### Motivation
My motivation for this project was to practice configuring different classification models. More specifically, I wanted to examine the hyper parameters of each model and their impact on the models scoring.
  

### Thought process
- I conducted exploratory analysis
- I chose 3 classification models and hyper parameters to tune considering the dataframe
- I iterated over the models and hyper parameters tuning with Gridsearch
- I visualised the models scoring
- I evaluated the best model's performance with conf_matrix, accuracy, precision, recall and f1
