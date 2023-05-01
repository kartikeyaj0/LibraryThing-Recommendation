# LibraryThing-Recommendation

This repository contains the code for a few different approaches to create recommendation systems using the [LibraryThing](https://www.librarything.com/home) Dataset. The dataset details can be found [here](https://cseweb.ucsd.edu//~jmcauley/datasets.html#social_data). To run the notebooks download and extract the [dataset](https://drive.google.com/file/d/1wgXv14TyrRD5DH6ZfJqApFymQv7_vuho/view?usp=share_link). Place the extracted files into the same directory as the ipynb. The code is organised as follows:
* LibraryThings Data Cleaning.ipynb: Contains the common preprocessing pipeline for all approaches.
* Neural_Network_Approach.ipynb: Contains the code for a neural networks-based recommendation engine. (Requires running the LibraryThings Data Cleaning.ipynb before to generate pickled filed)
* node2vec/: A node2vec implementation based on the official Stanford SNAP [implementation](https://github.com/aditya-grover/node2vec). The original code, which only works for python2, has been modified for use with python3 with Gensim's latest Word2Vec implementation.
* SocialNetworkGraphBookRecommendation.ipynb: Contains code for the User Network Graph Based Collaborative Filtering Approach. (Requires running the LibraryThings Data Cleaning.ipynb before to generate pickled filed)
* SVD_baseline.ipynb: file contains the code for simple SVD.
* XGBOOST_prediction.ipynb: Contains the code for Xgboost model and how the embedding are created.
* similarity_and_prediction.ipynb: contains the code for user-user similarity, and clustering based recommendation model. to run this file please download this [CSV file]([https://www.google.com](https://drive.google.com/file/d/1guD-1anJCD0dDTRmoQD62ixhLfFwFKnd/view?usp=sharing)). 
The csv file is genrated from XGBOOST_prediction.ipynb and it contains the cleaned reviews and there embeddings which we will use in this file.

Additionally, included are the html versions of the notebooks for easier viewing.
