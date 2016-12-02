---
title: "Coursera Data Science Capstone"
author: "Ryan Einbender"
highlighter: highlight.js
hitheme: tomorrow
job: internet
mode: selfcontained
subtitle: Course Project
framework: io2012
widgets: mathjax
---

## Introduction
</span><img src="./headers.png"></img>

This Slidify deck was created for the Coursera Data Science Capstone Course

The overall goal for this exercise is to create an application that displays everything that we have learned in the previous 9 course. The application specifically will use prediction, analytics, data cleaning, shiny, and Slidify. We used all of these skills to create a text analytics tool with a UI that can predict the next word when given a single word or a sentence.  


--- .Coursera Data Science Capstone

## Data Cleaning


<span style="color:orange; font-weight:bold; font-size:0.9em">Great Prediction can only happen after data cleansing. Here are my steps:</span>

<font size="5">

Subset the data: The data used for this application is a subset of the original data that were combined into one data set.

Data cleaning: removing white spaces, punctuation, numeric, and convert all characters to lower case.

N-grams: create quad, tri, and bigrams

Frequency counts: sort all of the n-grams by frequency and save them in associated files.


</font>

--- .Coursera Data Science Capstone
## Text Prediction
<span style="color:orange; font-weight:bold;font-size:0.9em">Katz Back-off algorithm powered the prediction model. Here is how it works:</span>

<font size="5">
1) Data is loaded from the saved data sets (quad,tri,bigrams)

2) Words imputed by the user are cleaned 

3) Algorythem first uses Quadgram, if no Quadgram is found then Trigram, if no trigram is found then Bigram.

4) If no Quad, Tri, or Bigrams are found then the algorithm will use the highest frequency word of the data set. 


</font>

--- .Coursera Data Science Capstone
## Web Application (Shiny)

<span style="color:orange; font-weight:bold;font-size:0.9em">Next word prediction model created in Shiny 

The application has a blank text line where a user can insert a whole sentence and through the use of the predictive algorithm the result will be the predicted next word.

Here is a screen shot of the User interface:

</span><img src="./Screenshot(4).png"></img>


