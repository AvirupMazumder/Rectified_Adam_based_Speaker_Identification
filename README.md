# Speaker-Identification-using-Improvement-CNN

# About the Codes
In this repository you will find 3 codes; **models.py**,**cfg6.py** **and** **predict.py**. In models.py we are doing feature extraction through MFCC and fitting it in CNN and LSTM. In cfg6.py, we are storing some pre determined values such as sampling rate, number of filters, hopping rate and nffts. We are passing it to models.py through a class Config stored in cfg6.py. In predict.py we are predicting the values of our speaker identifications and storing it in the form of a .csv file.  



# Procedure of running the codes
First of all you have to store your audio files of all the speakers in a single file called 'wavfile'. Then you create a .csv file for your dataset in the name 'instruments.csv'.Now you have to create empty directories.. 'pickles' and 'models'. Then first you have to run models.py first using optimizer 'Radam' , then you use the optimizer 'Adam'...After running this code and getting all saved files in 'pickles' and 'models' directory, its time to run our predict.py.. save the reulting .csv file by giving different names to each of them.
