# Duplicate-detection
Detect duplicates

## Instructions
Run duplicate_detection.ipynb

## Logic
I observed that amoung all the given columns, only duplications in 'id' and 'name' are worthwile to detect, because they act as the keys of a company.

I detected duplication in this columns, then used this information to retrieve the duplicates and their references in the original file, and marked which field they are duplicated on.

As a matter of fact, the duplicate in 'id' is also a duplicate in 'name'. I decided to keep it because things might be different in real work, where finding duplicates in 'id' is also important.

## To improve
At first sight, I thought this exercise might take some simple NLP methods to find the duplicates caused by typos, such as 'Apple' and 'Aple'. I didn't go deeper in this direction after I detected the actual duplicates.
