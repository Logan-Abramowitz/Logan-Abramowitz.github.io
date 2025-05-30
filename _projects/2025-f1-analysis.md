---
layout: project
title: Predict to Get Picked
description: Prediction Models for Formula 1 Constructors
technologies: [SQL, Python, Machine Learning]
image: /assets/images/f1-coverphoto.jpg
---

Throughout the spring semester of 2025 I worked on a group project for my Practical Tools for Operations Research, Machine Learning and Data Science class, ORIE 3120. I worked in a group of four to analyze trends and create prediction models from Formula 1 data. This was a semester long project that went through many iterations and pivots overall culminating in a thirteen page report from over eighty hours of work.

Early on in the semester, each of us preformed basic data exploration on datasets of our choice and wrote recommendation memos to our teammates regarding the depth of analysis we believed could be done on our particular data set. From these memos and a group discussion, we collectively agreed to dig in deep to the F1 data set. This was due to a variety of factors such as the scale of the records, number of tables, number of features with those tables, and relatively few null values.

Now that we had our data set, we needed a goal to guide our research. We decided that we were going to investigate "fairness" within F1 as a governing body of F1 such as the FIA would stand to benefit from our findings. To start our investigation, we each asked one descriptive question and searched for the answers within the data set. I looked into the average lap times of many different circuits to understand that a drivers overall average lap time can be highly influenced by which circuits they race on. Later I would go on to normalize these findings by dividing the length of the circuits by the average lap times to get average speeds. From these initial investigations we found that there were in fact large discrepancies between circuits in both average lap times and average lap speeds meaning that circuits where drivers raced would be a factor to keep in mind as they could be a source of "unfairness".



For more details on our project, please read our [final report]({{ "/assets/F1_Analysis.pdf" | relative_url }}).
