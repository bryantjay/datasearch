# Here's What I Did

## Data Connection and Preparation

 Connect to the “job_postings.csv” file.

![image](https://github.com/bryantjay/datasearch/assets/95669697/fe132cd5-2b61-400a-8d1d-b815155f5a0c)

The primary key Job Posting ID will be read in as a continuous numeric field, so be sure to convert it to a discrete data type.

Use the maximum and minimum pay fields to calculate Average Pay.

![image](https://github.com/bryantjay/datasearch/assets/95669697/04b49b14-394a-46ab-8a1c-a07fd4f7ba04)


Perform a split on “Job Skills” by selecting Transform > Custom Split, and then splitting off “All” columns separated by a comma.

![image](https://github.com/bryantjay/datasearch/assets/95669697/b7e8f9cc-962c-45d2-ac6d-cd479a012046)
![image](https://github.com/bryantjay/datasearch/assets/95669697/7f62d52e-4679-4101-853b-54d4e9622fb4)


Create a calculation to label job postings with “Tableau” listed as one of the first three required skills, and filter to only include those.

![image](https://github.com/bryantjay/datasearch/assets/95669697/7aa042a0-a5ed-4efb-976e-fe417aa2d0e2)
