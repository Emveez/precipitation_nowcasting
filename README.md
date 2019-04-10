# Precipitation Nowcasting

Some of the source code to train the models for precipitation nowcasting of my degree project. The spatio temporal dataset are stored in HDF5 format which are then read from disk to memory to train the network. The PyTorch framework is used to train the models.

# Prediction sample
![Alt Text](https://media.giphy.com/media/ZbZNj4GBCHBpSCHfZV/giphy.gif) <br />
Left is the raw probability of the prediction, middle rounded at threshold .5, right is the ground truth.
