# predicting-electricity-usage

This folder contains scripts for predicting electricity usage of commercial sites.
The method is based on recursive neural networks of the type Long Short-Term Memory, implemented using Keras.
There are two scripts for prediction electricity usage respectively one and 24 hours ahead.

Code was written during the work on my (Kjersti Rustad Kvisberg) master thesis "Prediction of electricity usage in Oslo Lufthavn Gardermoen" at the Norwegian University of Life Sciences (NMBU) autumn of 2022.
As part of the research project "Network balancing from large parking facilities and commercial buildings", the scripts were applied on a case study of Oslo Airport Gardermoen to assess wether it's electricity usage was possible to predict using the suggested methodology.
It should be possible to apply these scripts to other data sets, but this has not been tested.
For the thesis work, the electricity usage of the airport were estimated using meteorological data, calendar information and passenger numbers as features.
More about the project and the full thesis (in Norwegian) can be found at the [NMBU project pages](https://www.nmbu.no/forside/prosjekter/nex2g).

Other scripts were used to download data from online sources, format and merge data sets and visualize both input data sets and results from predictions. 
Please contact the author if you wish to access these additional scripts.
