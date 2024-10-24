# SER_course_work
Over the past decade, the problem of recognizing emotions in the voice has become particularly important. The main difficulty is to make a computer capable of recognizing not only the semantic meaning of a statement, but also the emotional background that accompanies it.
The relevance of the study of emotions in speech is determined not only by the general importance of emotional intelligence in the modern world, but also by the specific problems that are solved through this research. One of the key essences of the problem is the development of systems that can analyze and recognize emotions in human speech. This is important for understanding and improving communication, developing psychological research, and creating more efficient interfaces with computers and other technologies.
The aim of this work was to develop and study a system for recognizing emotions in human voice.

In the course of the work, many methods of emotion recognition were considered, and we also developed our own CNN-based model architecture and trained it on two datasets, one containing mel-spectrograms created from audio recordings taken from the RAVDESS dataset, and the other containing mel-spectrograms obtained from the segmented data of the first dataset. The analysis of the existing results allowed us to draw many conclusions about how the emotion recognition system works in general. The developed models showed a good classification result, including 81% accuracy in classifying 8 emotions. 

Last update:
In the course of the course work, the following goals were achieved: a system that can quite accurately determine the emotional state of a person by voice was developed and improved. The next step to solving the problem is to collect a dataset containing content in Ukrainian, since the ability to recognize emotions in the Ukrainian-speaking environment is especially relevant for preparing public speeches, presentations to partners, diploma defenses, etc. This will help improve speakers' skills, increase the level of interaction with the audience, and achieve more effective communication.
Thus, the purpose of the next step was to study the effect of data size on the accuracy of emotion recognition in speech using the HuBERT model and to determine the minimum amount of data required to train an effective model for emotion recognition in speech. To achieve this goal, specific tasks were identified: 
- to train the HuBERT model for speech emotion recognition of English recordings;
- to train the model on data that make up 25%, 50%, 75%, 100% of the existing data set;
- to analyze how the amount of data affects the quality of the model;
- to determine the minimum number of examples required to collect your own data set.
As a result:
- The HuBERT model was trained on the RAVDESS dataset containing English language recordings. The results of the training were quite good, which indicates that this model is well suited for solving this particular task.
- Having trained the models on different amounts of data, it was concluded that the best result was shown by the model trained on the full data set. However, given that the results of the model trained on 75% of the dataset are only slightly worse, we can assume that this amount of data also showed a good result.
- Taking into account the conclusions drawn for the previous task, we can conclude that the amount of data corresponding to 75-100% of the RAVDESS dataset is suitable for model training. However, given the small difference in results and the difficulty of collecting your own data set, the minimum amount of data needed to accurately classify an emotion is a set equivalent in size to about 75% of the RAVDESS data set.
The next steps:
- collecting an own dataset with Ukrainian-language content; training and improving the model on the collected data.
- learn how to classify a bunch of emotions in order to be able to analyze people's speeches more efficiently in the future.
- learn how to advise on the optimal emotion to be able to correct the received speeches.
