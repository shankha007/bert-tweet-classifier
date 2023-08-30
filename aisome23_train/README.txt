The "train_val.csv" file contains data from the CAVES dataset (see below), for AISoMe track of FIRE 2023.
The file contains 9,921 tweets labelled with the concerns towards vaccines. The file is formatted in the standard CSV format, and can be viewed using spreadsheet software (e.g. Libre Office, Microsoft Excel). 
To read the file in Python, you may use the in-built "csv" library, or the "pandas" library.


There are 3 columns in the file:
 - ID of the tweet in a string format, appended with a "t" (to make it easier to work with on spreadsheet softwares).
 - The tweet text
 - The different labels (vaccine concerns) expressed in the tweet, seperated by spaces.


List of the 12 different vaccine concerns in the dataset:
 - [unnecessary]: The tweet indicates vaccines are unnecessary, or that alternate cures are better.
 - [mandatory]: Against mandatory vaccination — The tweet suggests that vaccines should not be made mandatory.
 - [pharma]: Against Big Pharma — The tweet indicates that the Big Pharmaceutical companies are just trying to earn money, or the tweet is against such companies in general because of their history.
 - [conspiracy]: Deeper Conspiracy — The tweet suggests some deeper conspiracy, and not just that the Big Pharma want to make money (e.g., vaccines are being used to track people, COVID is a hoax)
 - [political]: Political side of vaccines — The tweet expresses concerns that the governments / politicians are pushing their own agenda though the vaccines.
 - [country]: Country of origin — The tweet is against some vaccine because of the country where it was developed / manufactured
 - [rushed]: Untested / Rushed Process — The tweet expresses concerns that the vaccines have not been tested properly or that the published data is not accurate.
 - [ingredients]: Vaccine Ingredients / technology — The tweet expresses concerns about the ingredients present in the vaccines (eg. fetal cells, chemicals) or the technology used (e.g., mRNA vaccines can change your DNA)
 - [side-effect]: Side Effects / Deaths — The tweet expresses concerns about the side effects of the vaccines, including deaths caused.
 - [ineffective]: Vaccine is ineffective — The tweet expresses concerns that the vaccines are not effective enough and are useless.
 - [religious]: Religious Reasons — The tweet is against vaccines because of religious reasons
 - [none]: No specific reason stated in the tweet, or some reason other than the given ones.

 

More details about the dataset, evaluation metrics, and some baseline methods can be found in our paper: 
Poddar et.al. "CAVES: A Dataset to facilitate Explainable Classification and Summarization of Concerns towards COVID Vaccines", In Proc. of 45th SIGIR (2022).
Updated version on Arxiv: https://arxiv.org/abs/2204.13746 
Original publication on ACM: https://dl.acm.org/doi/abs/10.1145/3477495.3531745 

