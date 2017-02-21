# Predict_Drug_AdverseEvent_Level
[The drug search app can be found here](https://ccchang0111.shinyapps.io/shinyapp/) (R Shiny app)

The purpose of this app is to find out **how likely a given drug or ingredient will cause problem** and allow user to compare similar drugs with the same active ingredients. 

When a person is sick, it might be hard to decide what medicine to take, because there are so many similar drugs under different brand-names that can treat the same symptom. Sometimes doctors might also find it difficult prescribing the right drug.  This app is potentially useful for anyone (**especially for those who do not have access to good healthcare**) when it comes to deciding what drugs to take, or to learn more about the drug they are currently taking. 

The "problem" in FDA's report can range from minor issues (like 'rash') to sever problems (like 'permanent deafness') and to wierd cases (like 'snake bite'?!). However, **not all the drugs on the market have well-documented adverse events (AE) in FDA's dataset**. Therefore, for those drugs without any AE reports, I apply machine learning to calculate their 'problematic level' based on their **name** and **active ingredients**.

This document contains three sections:
1. Data collection and cleaning (90% of the total work!!)
2. Features and Lables (8%)
3. Training and Prediction (2% only! Once the 'goundwork' is well established, the rest is very easy)
