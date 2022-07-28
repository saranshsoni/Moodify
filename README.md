# Moodify
Description
Have you ever experienced that the instagram posts visible to you are completely unrelated to what you wanted to see ? Well, not anymore. Moodify will classify your insta feed according to your current mood, which will make your feed more engrossing and relatable. We will use Instagram API for gathering the feed and apply our model to select relevant posts. We plan to build a ML model which will classify the posts based on their picture, caption, and top few comments to predict which mood is more likely to relate with this post. Initially we will learn a CNN based model for the image part and a RNN based model for the textual part. Then we will combine their outputs to predict a common metric and classify the outputs in "happy", "funny", "motivational" etc. We will only be working on those posts with a single image (in case of multiple images we will select the first one). Later, if time permits, we may also build a mobile application for the same.

Week 1
Reading material for this week -

Python tutorial (you can leave file handling onwards part)
Basics of Neural Network
Details of Neural Network
NN with implementation (You can skip the CNN part for now)
Pytorch NN
Another Pytorch NN
Week 2
Reading material for this week -

Understanding CNN
NN with implementation (You can read the CNN part now)
CNN Implementation in PyTorch
Week 3
Reading material for this week -

Understanding RNN
Other Versions of RNN
RNN PyTorch Implementation
Week 4
Read and understand how will we use the Meta For Developers API for our purpose i.e. extracting the insta feed of a person.

API session recording
Demo repository
Week 5
Look up for dataset online for both image and textual data with annotated sentiments. Couple of examples -

Textual Data
Image Data
Week 6
Build a basic pipeline of the model including input preprocessing, a very basic naive model, correct output format, and metric calculation. Don't pay attention to model details or metric values now.

