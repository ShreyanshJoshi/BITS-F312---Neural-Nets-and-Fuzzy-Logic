# BITS-F312---Neural-Nets-and-Fuzzy-Logic
This repository contains code of the weekly labs and my solutions to the 2 assignments for the course for the year 2021-22.

**Labs** - Conducted on a weekly basis, and are meant for just introducing the coding part of a particular topic to students. Usually, some code is already implemented and students are given some homework where they have to write similar code for a slightly different tasks. Students are not expected to optimize the models to attain the best results, but rather experiment with the code, trying out various hyperparameters in an attempt to understand how exactly things are working.

**Assignment1** - https://www.kaggle.com/c/nnfl-2021-assignment-1/overview - Given a set of coloured images labeled either as "fire" or "not_fire", the task was to process this data as you see fit and create a model that will classify the unlabeled data present in the test folder. Convolutional neural networks were supposed to be used for the same (without using transfer learning). The focus here was to use only spatial features in making predictions. As a result, regular 2D CNNs were used.

**Assignment2** - https://www.kaggle.com/c/nnfl-2021-assignment-2/overview - Given a set of videos labeled either as "fire" or "not_fire", the task was to process this data as you see fit and create a model that will classify the unlabeled data present in the test folder. Convolutional neural networks were supposed to be used for the same (without using transfer learning). In contrast to assignment 1, here we were supposed to extract the temporal correlations (apart from using spatial features) to better classify videos. Consequently, models such as 3D CNN, CNN+LSTM, ConvLSTM2D were used.


*My team (Team 5) ended up finishing on top of the leaderboard in both the assignments, with a score of 0.95319 and 1 on the private leaderboard in assignments 1 and 2 respectively.*

Note: 
- Output of some cells (usually such cells included printing a very long list, involving 10000+ entries) in the assignments has been erased, to avoid excessive scrolling on Github.

- An accuracy of 1 could be achieved in the second assignment, because the testing was done only on 20 videos.