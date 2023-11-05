# Introducation

# How to run

# Conclusion 

# find the top k words in a large dataset
This is the first assignment from Data Engineering course.

The goal of the project is to write code from scratch that can get the k most frequent words from a text file that is as big as 16 GB.

Since the data file is as large as the memory of my laptop, simple approaches like opening the file and reading the whole file will not work.

Thus, the file is read in chunks of 1GB. To make the process faster, multi-processing is used.

The code can be found in Word_freq.ipynb. 
Stop words used in this project is in stop_words directory.
A sample dataset is included as an example: small_50MB_dataset.txt
