# CNND
This is an implementation of "Transferred Deep Learning for Anomaly Detection in Hyperspectral Imagery" paper, but there are some bugs.
If you want to work on this project, first,  you should tune the network.
As I worked on this paper, the best epoch and bach size are 5, 20 respectively.
I achieved accuracy 83 and 94 on test data and train data respectively and saved the model
# Project Structure
In the main file, I used the tensorflow library for implementation, a low-level API layer. Also in the keras file, I designed the network, using keras
library.
there are five data set. I used 1 data set for generating train data and 1 data set for testing the network.
