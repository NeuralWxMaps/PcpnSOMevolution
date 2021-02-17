# PcpnSOMevolution
A look at how some of the Precipitation Neural Network nodes evolve as more training data is incorporated 

As forecast precipitation data is added to the neural network, the algorithm will make changes to the neighboring nodes, and eventually all of the nodes will become patterns of non-zero data.  The precipitation is being collected into a grid of 53-by-59 points, which means that 3100+ patterns of precipitation can eventually be defined.  The neural network algorithm will define an array of patterns that are characterised by a variety of shapes and a variety of magnitudes.  With each new model run that is collected into the database, the 31 ensemble member forecasts from the first 72 hours of the model run are added to the SOM training dataset. 

This is the progression of pattern numbers 1000, 2000 and 3000 after each new week of data was added to the dataset.  Back in mid-November 2020, pattern 3000 had not been defined yet, but after an additional week of data had been added, it had been defined. As more and more data are added to the algorithm, the changes should become smaller.
