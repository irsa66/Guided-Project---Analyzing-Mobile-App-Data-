# Guided-Project---Analyzing-Mobile-App-Data-

Analyzing data on mobile apps from the Apple Store and Google Play 

In this project, I use basic Python commands and functions to analyze a dataset on mobile apps in the Google Play store and the App Store. 

I have created a new dataset by using simple list slicing to get rid of the row that contains the column headers; I have printed the headers separately. 
I started off with creating a function that conducts a simple analysis of the dataset, and prints out the number of rows and columns in the dataset.
Then, I deleted a row that contained incorrect data (according to the discussion section on the Google Play Store data set), following which I checked for duplicate entries and 
used a for loop to get rid of duplicate app entries and add the unique ones to a new list. 
Next, I checked the number of reviews using a for loop and created a dictionary with app names as keys and their corresponding number of ratings as values. Then, I further cleaned the 
dataset by removing duplicate entries - for each duplicate entry, I only kept the ones with the highest number of reviews by creating a new list of lists (dataset) called 'android_clean'.

Then I used the 'explore_data' function created previously to explore the 'android_clean' dataset. 
