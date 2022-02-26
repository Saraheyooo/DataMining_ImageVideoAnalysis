# DataMining_ImageVideoAnalysis
20220112

In this repository, there are three questions that address different aspects of image and video analysis using data mining techniques. The methods include object detection using the MS COCO, ResNet-50 model, Keras based on TensorFlow library and visualizes networks using Gephi. After loading the images by URL and pre-processing the features, we can discover insight into these data. Finally, apply Matplotlib, Seaborn tools and t-SNE to visualize the results and interpret the conclusions.



## Question 1

A researcher has performed a network analysis on the dataset and now likes to know whether we can find different types of video thumbnails in different communities. In order to answer that question, she wants to categorize the video thumbnails using image classification.
Design a classification scheme (with clear definitions and examples) for catego- rizing video thumbnails in nodes.csv [column video_thumbnail]. Make sure that your classification scheme could be used by someone who hasn’t seen the data before.
Then discuss 1) why this classification scheme would be relevant to use in the context of the analysis of exercise 6.1 (e.g. what will it learn us about this data, what kind of questions can we answer with it), 2a) whether and why you think this classification model could be computationally reproduced (by a Resnet50, for example) and 2b) where there could be potential bottlenecks in reproducing this classification scheme.


## Question 2
Google Images can uncover interesting cultural representations. For example, if you search for “CEO”, you will mainly see pictures of middle- aged white males; if you search for “big data”, you will see an abundance of dark blue, cyberspace-like images.
Come up with a Google Images query you want to research, explain your choice, and collect at least 50 images from this query.
Then analyze the images using one of the methods we explored in week 4, 5 or 6. Make sure to motivate your choice of method: why are the image features you chose relevant in the context of your query? Interpret the results and discuss what other features could be relevant to analyze.


## Question 3
Use the subsets of movie trailers from 1920-1940, 1960-1980 and 2000-2020 from exercise 6.1, but instead of comparing the shot types and shot lengths, use one of the (pre-trained) image feature extraction methods we discussed in exercise 5.2 to compare the subsets, and explain your choice. 
Make a plan for tackling the dimensionality of the data: each subset consists of multiple videos, each video consist of multiple frames/seconds/shots, and each frame/second/shot could contain multiple faces/genders/emotions/objects/texts/colors. How are you going to compare the subsets? Explain the choices you make carefully. Then implement your plan and interpret the results.
