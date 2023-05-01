# LibraryThing-Recommendation

This repository contains the code for a few different approaches to create recommendation systems using the [LibraryThing](https://www.librarything.com/home) Dataset. The dataset details can be found [here](https://cseweb.ucsd.edu//~jmcauley/datasets.html#social_data). To run the notebooks download and extract the [dataset](https://drive.google.com/file/d/1wgXv14TyrRD5DH6ZfJqApFymQv7_vuho/view?usp=share_link). Place the extracted files into the same directory as the ipynb. The code is organised as follows:
* LibraryThings Data Cleaning.ipynb: Contains the common preprocessing pipeline for all approaches.
* Neural_Network_Approach.ipynb: Contains the code for a neural networks-based recommendation engine.
* node2vec/: A node2vec implementation based on the official Stanford SNAP [implementation](https://github.com/aditya-grover/node2vec). The original code, which only works for python2, has been modified for use with python3 with Gensim's latest Word2Vec implementation.

Additionally, included are the html versions of the notebooks for easier viewing.
