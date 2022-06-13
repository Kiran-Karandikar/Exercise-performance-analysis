# Exercise Performance Analysis using Data Mining Techniques

## [Preview]()

## Abstract
Strength Training techniques have been used in tailored routines during personalized training programs for athletes. During recent times, there has been a shift from tried and tested to evidence-based training routines. But with more advancement in the field of ML and IOT, more companies like HUDL, LongoMatch are leveraging this domain to gain more insights into the field of sports and we think this will be the same in the field of Strength Training.

In future, we think the ML model and a human expert will work together to make decisions productively for realistic short-term goal to long-term fruition. We intend to use historical work out data to gain insights about how to efficiently one can plan his future workout sessions. In our current project we discuss the current data gathering techniques used by athletes, processing methods for this data to be used in the model and proof-of-concept system for strength training based on Progressive Overload.

> Key-Words: Strength Training, Progressive Overload, Hypertrophy, proof-of-concept, Volume, Repetitions, Sets, Trend Analysis

## Introduction

The main technique emphasized in our strength training is Progressive Overload. Progressive overload is one of the key factors when it comes to reaching one’s strength or hypertrophy goals. Progressive overload takes multiple forms (sets, reps, time under tension, rest periods) but workout volume or exercise volume is one of the major components.

As discussed in the research done on Load Progression Strategy $^{[2]}$, the 3 commonly used techniques in progressive overloading are Volume, Intensity and Density. Where Volume is the number of sets or repetitions, intensity is the weight lifted and density is alternate rest periods. Here, the  prediction will be done on feature Volume - a continuous feature. Volume is given by the formula:

  ```
          Volume(V)= Sets * Reps *  Weight
  ```

Able to predict, one’s progression in terms of workout volume helps in fine tuning the exercise selection and programming. By examining one’s historical workout log, we can predict future performances or drop in performance. [Read more.](documents/project_report.pdf)

### Challenges

1. Small Data size
2. Summarizing the information against different levels of granularity.
3. Handling of missing value.

> Designed with passion as part of the curriculum for the course [B565 data mining](https://cgi.luddy.indiana.edu/~yye/b565/) in the spring of 2022

##### In association with:
- [Satyajeet Arun Sarfare](mailto:ssarfare@iu.edu)
