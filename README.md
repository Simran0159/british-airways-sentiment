# British Airways Customer Booking Prediction

##Introduction
ML pipeline to predict whether a British Airways 
customer will complete a booking.

Completed as part of British Airways Data Science 
Virtual Experience — Forage.

## Key Challenge Solved
Dataset had severe class imbalance — 85% not booked, 
15% booked. Baseline ROC AUC was 38.86% (worse than 
random guessing). Fixed using SMOTE and 
class_weight='balanced'.

## Results
| Metric | Before Fix | After Fix |
| ROC AUC | 38.86% | 
| Class 1 Precision | 30% | 

## Tech Stack
Python · Pandas · scikit-learn · 
Random Forest · SMOTE · Matplotlib

## Source
British Airways Data Science Virtual 
Experience — Forage
