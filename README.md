# Malware-Detection
This repository contains codes to my 1st project review : Malware Detection

Steps required to achieve this model:
1) Choose the website required to detect any malicious threat is there or not
2) Our model also works as an Adware- removing advertisements as well
3) This model scraps the particular website needed to scan for malwares or adwares
4) After web scraping (with the help of Python and BeautifulSoap) we make our .csv file
5) After our .csv file is prepared, we need to preprocess the data and clean the data
6) Then we will divide our dataset in testing and training set for training and testing of our model
7) Then we need to apply Machine Learning models to detect the presence of Malwares and Adwares
8) After the detection, we need to analyse the result
10) Our extension from Pypi directly connects the website to our Machine Learning model and gives the output
11) If malware is found, our MalBlocker flashes a warning and stops the page from loading. Advertisements are automatically removed.
12) If the website has no problem with it, it launches smoothly.
