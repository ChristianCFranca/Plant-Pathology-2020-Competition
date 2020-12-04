# Plant-Pathology-2020-Competition

Welcome you! This is my implementation of a CNN Classifier in Pytorch for the [Plant Pathology 2020 Competition](https://www.kaggle.com/c/plant-pathology-2020-fgvc7) hosted at Kaggle.

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/PPC.PNG?raw=true)

The goal of the Competition was to train a model using images of a training set to 
1. Accurately classify a given image from testing dataset into different diseased category of healthy leaf; 
2. Accurately distinguish between many diseases, sometimes more than one on a single leaf; 
3. Deal with rare classes and novel symptoms; 
4. Address depth perception—angle, light, shade, physiological age of the leaf; and 
5. Incorporate expert knowledge in identification, annotation, quantification, and guiding computer vision to search for relevant features during learning.

I was able to achieve the top 17% leaderboard with an MC AUROC Score of 0.97165, getting the 219° place (of a total of 1317 teams).

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/rank.PNG?raw=true)

First, i performed a simple EDA on the dataset provided by Kaggle. You can check it in the notebook `Exploratory Analysis.ipynb`.

Second, in the notebook `CNN Train in Pytorch.ipynb` you shall find every bit of detail of how the training was accomplished using a `ResneSt50` architecture. By the end of the entire training process, i was able to achieve a `95.968%` accuracy on the test set.

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/CMResults.PNG?raw=true)
