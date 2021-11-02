# Personalized-Preception-Project

As human beings, we have our own preference on what we see, hear, and feel. It can be constructed based on personality, personal experience, unique context, and the situation at the time. For instance, beauty is a personalized  perception, and everyone has their own criteria. Some people might prefer small dogs with lots of hairs and others might prefer bigger dogs with floppy ears. So, there is an assumption we try to research with. Are we able to capture an individual's personalized perceptual preference and predict it based on limited data using machine learning? Based on the question assumption, this project focuses on researching what and how different machine learning models and different computer vision technologies can predict human preferences well with limited data. 

Key words: Computer Vision, Machine learning, Personalized Perception

# Experiment: 
We set up the experiments with Psychopy which is a very powerful tool for designing variant experiments and collecting data from observers by publishing the experiment on Pavlovia. All experiments have the same format, we give participants a pair of images and they may  choose one they prefer.  
For now, we focus on finding the attributes of the images which may really affect how  people define cuteness. Thus, in our experiment, we offer participants two cats’ images and ask  them to choose the one they think is much cuter. 

Fig1. The interface of our experiment, the participant is able to choose the left or right image regarding his preference. 
There are two types of our experiment, one we call a random sample experiment in which  we randomly picked up 2000 unrepeated images (like Dog, Cat, House…. etc.)  to construct the pair decision experiment with 1000 trials. In this case, we can easily obtain  balanced binary results (1000 labeled data for like, 1000 labeled data for dislike). The other one is a so-called Fully sampled experiment in which we offer 50 unrepeated images within one category, and all images will fully compare to each other. Therefore, the experiment has 1225 trials. The result for this experiment will be decimal data for each image which we called its score, and the score is according to how many times the image is selected during the experiment by the same participant. 


