# Recommender_System_Images
Collaborative filtering models, more specifically Alternating Least Squares models, were used to recommend users of the platform Flicker images that match their preferences. The aim was to provide each user with a top 15 selection of images that are likely to match their preference. 


The Alternating Least Squares model is built on the concept of discovering and using patterns that involve the interactions of multiple actors. The basic idea is that if actor A and actor B have interacted and liked similar items, in this case, images. The model will recommend images to actor A that they haven’t seen but which actor B and similar actors have seen and liked. Reversely, images that were seen and liked by actor A and similar actors will be recommended to actor B. Providing users with recommendations using this type of model is only possible since we have a large data set of past user-item interactions which enable the identification of such patterns between actors (see image below). 


![alt text](https://github.com/aber0016/Recommender_System_Images/blob/main/rec_2.png?raw=true)
