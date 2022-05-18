# Rectified Adam Optimizer based CNN Model for Speaker Identification

Cite this paper
Mazumder, A., Ghosh, S., Roy, S., Dhar, S., Jana, N.D. (2022). Rectified Adam Optimizer-Based CNN Model for Speaker Identification . In: Mohanty, M.N., Das, S. (eds) Advances in Intelligent Computing and Communication. Lecture Notes in Networks and Systems, vol 430. Springer, Singapore. https://doi.org/10.1007/978-981-19-0825-5_16

Paper link: https://link.springer.com/chapter/10.1007/978-981-19-0825-5_16

# About the Codes
In this repository you will find 4 codes; **models_RadamOptimizer.py**,**models_AdamOptimizer.py**,**cfg6.py** **and** **predict.py**. In models_RadamOptimizer.py as well as in models_AdamOptimizer.py we are doing feature extraction through MFCC and fitting it in CNN and LSTM.In models_RadamOptimizer.py we have used optimizer 'Radam' and in 'models_AdamOptimizer.py', we have used Adam Optimizer  In cfg6.py, we are storing some pre determined values such as sampling rate, number of filters, hopping rate and nffts. We are passing it to models.py through a class Config stored in cfg6.py. In predict.py we are predicting the values of our speaker identifications and storing it in the form of a .csv file . 



# Procedure of running the codes
First of all you have to store your audio files of all the speakers in a single file called 'wavfiles'. Then you create a .csv file for your dataset in the name 'instruments.csv'.Now you have to create empty directories.. 'pickles' and 'models'. Then first you have to run models_RadamOptimizer.py first using optimizer 'Radam' , then you rum models_AdamOptimizer.py using the optimizer 'Adam'...After running this code and getting all saved files in 'pickles' and 'models' directory, its time to run our predict.py.. you will get your resultant prediction after following these steps. You will get your prediction in the form of a .csv file.
