# treatment_weights.py
For animal treatment or toxicology studies. Calculates descriptive statistics on weights over a number of days. 


### About
Often drug or toxin treatment causes changes in weight, which can be an indication of toxicity or off-target effects. This program 
was written to calculate mean, ste, and std from raw data with regard to treatment and day. 


### Data Organization
Input is a csv file with the following columns:

* cohort	
* date	
* day	
* treatment	
* cage	
* mouse	
* weight


### Variables You Will Need to Change
* file_name = 'mouse_weights.csv'
* directory = 'D:\\Dropbox'
* group1 = 'saline'
* group2 = 'drug'

### Output
Outputs both descriptive stats to a separate csv file in the original directory.
