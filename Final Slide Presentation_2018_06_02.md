Data Science Course Capstone Project
========================================================
author: Marwan Medhat
date: 25 June 2021
autosize: true

Word Prediction App Description
========================================================

Want to know the predicted next word? 
Use our new app...

- Users start to type a sentence, the app predicts next word
- App uses a subset of data from the three data sources (blogs, twitter & news)
- App also uses the technology of Swiftkey

Try it now...select it [here](https://dwenke.shinyapps.io/Final_Project_2018_06_03/)

How to Use the Word Prediction App
========================================================

<div style="align:top"><img src="./www/App_UserGuide.png" alt="User Guide" /></div>

Data Gathering & Cleansing 
========================================================

- Merged data from the 3 Data Sources into one data file (Blogs, Twitter & News)
- Cleansed data including converting to lowercase, stripping white space, and removing punctuation & numbers
- Created Bigram, Trigram and Quadgram n-grams
- Extracted term-count tables from the n-grams
- Sorted in descending order based on frequency
- Saved n-gram objects

Word Prediction Algorithm & Summary
========================================================
- Algoithm checks for the highest-order n-gram (n=4)  
- If n=4 is not found, then checks the next lower-order model (n=3)
- If n=3 is not found, then the app continues to check (n=2)
- If n=2 is not found, then the app returns "No Match Found"

- Code is available on [GitHub](https://github.com/DWenke/Data-Science-Capstone-Final-Project/)
- Further work can include expanding both the number of data sources & number of n-grams
Enjoy the app!

