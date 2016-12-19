# E-commercial-Product-Recommendations

There are three parts of code: 

1. DataRetrieve.ipynb
It serves to preprocess the dataset. 

put amazon-meta.txt(input dataset) in the same directory of DataRetrieve.ipynb

run the program

The output will appear in the same directory with the name rater.txt


2. spark_recommendation.py
It serves to do recommendation on spark. 

Copy the path of your inputfile rater.txt

Open spark_recommendation.py and replace variable $filename with the path copied

Save and run this python script with the command ./pyspark spark_recommendation.py

It will output MSE, as well as the ten top recommendation results. 
 
