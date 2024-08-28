<h1 style='color:rgb(144, 12, 63)'; align=center><font size = 8> Managing Blood Glucose </font></h1>

# Introduction

Insulin resistance and poor metabolic health is the primary driver of many diseases, including:

* Heart Disease and Stroke[^1]
* Blindness[^2]
* Kidney Disease[^3]
* Dementia and Alzheimer's Disease[^4]
* Cancer[^5]

Insulin resistance and poor metabolic health is a result of uncontrolled blood sugars (blood glucose). Uncontrolled blood sugar is caused by consuming too much refined carbohydrates such as white flour, white rice, and refined starches, as well as refined sugars that include: glucose, fructose, and refined corn syrup. Furthermore; artificial sweeteners can also cause metabolic issues.

# Purpose

This repository contains a set of open source tools that I'm using / developing to help manage my own blood glucose levels. My goal is to eventually create an app that can be used by anyone interested in managing their blood glucose, especially for people who have been diagnosed as having prediabetes or having Type 2 diabetes, with the aim of reducing blood sugars to the point of being in "remission" of these conditions.

The app will also help Type 1 diabetics manage their condition. 

## Problems with existing apps

I know there are many 'apps' out there already, but here are my pain points with them:

1. Most open source apps are only focused on Type 1 diabetes. 
2. The apps that come with blood glucose meters are proprietary. If I switch the glucose meter brand I use, I have to download another app. These apps do not talk to each other and therefore cannot give an aggregated analysis of my overall blood glucose levels. It can only give an analysis of my blood glucose levels according to the data stored in the app.
3. These apps all have complicated Terms Of Service (TOS) agreements, mostly requiring me to accept that these companies can gather and collect data from me, and my phone - including but not limited to location services, etc.
4. I don't find the graphs and data provided by these apps as meaningful or insightful. They're not very useful in helping make decisions that can help me manage blood glucose levels.
5. Apps that connect to software like "Apple Health" means that Apple has access to all my data. I'm not a fan of Big Tech having access to this data, especially since they can profit off of it, instead of me. They already make enough money from me, my data is my property.
6. Most generic blood glucose apps available (at least on the Apple app store) require paid subscriptions.

## Specifications of tools and app

The following are the specifications for the tools and apps:

- [ ] Track blood glucose levels, by date and time, according to a defined set of marker definitions
- [ ] Track meals
- [ ] Track the finger locations used to draw blood samples
- [ ] Track insulin injection locations
- [ ] Track blood pressure
- [ ] Provide graphs and charts that provide meaningful analysis to help make health decisions
- [ ] Use machine learning to predict A1C levels and trends
- [ ] Create a database to store the data, and use a pipeline to transfer that data to the charts and graphs

# Terms and definitions



[^1]: Dr. Philip Ovadia [What They Don't Tell You About Statins](https://youtu.be/uUgud92bVK4?si=jF0ITsNBJHOFr8wq)
[^2]: Stoney Williamson, M.D. [Diabetic Retinopathy Treatment in Hattiesburg, Mississippi](https://www.hattiesburgeyeclinic.com/services/eye-conditions/diabetic-retinopathy/)
[^3]: National Kidney Foundation [How are CKD, CVD, and Diabetes Related? | The Kidney Disease, Heart Disease, and Diabetes Connection](https://youtu.be/rLxTozspBxk?si=iyM6R9sl2b6VPEXF)
[^4]: Dr. Ford Brewer [Alzheimer should be called Type 3 Diabetes](https://www.youtube.com/live/SObnLvd-87s?si=6tInkhCgAUM6le0f)
[^5]: Dr. Casey Peavler [The Dangerous Link Between High Blood Sugar, Diabetes, And Cancer](https://youtu.be/GyhI40W0hkc?si=nrrwlPgb8ojiRUMz)
