Powered by [Croct](https://croct.com/) (simulating)

[About Croct](About.md)
### Sumary
- [Introduction :speech_balloon:](#introduction-speech_balloon)
- [New in development? :computer:](#new-in-development-computer)
  - [About CQL :mag:](#about-cql-mag)
  - [Examples of CQL :grey_exclamation:](#examples-of-cql-grey_exclamation)
- [Implementation process :round_pushpin:](#implementation-process-round_pushpin)
  - [Step :one: - Gathering data :bar_chart:](#step-one---gathering-data-bar_chart)
  - [Step :two: - Defining a personalization strategy and goal :dart:](#step-two---defining-a-personalization-strategy-and-goal-dart)
  - [Step :three: - Implementing :wrench:](#step-three---implementing-wrench)
- [Satisfaction survey and integration time :star:](#satisfaction-survey-and-integration-time-star)


# Introduction :speech_balloon:
Documentation designed for developers to facilitate integration with Croct
This documentation can be used for three types of areas (Marketing, Product and Engineering) that can use Croct to drive revenue with more targeted messaging and to increase short-term customer lifetime value
# New in development? :computer:
Croct created a programming language for non-developers! It's called [CQL - Contextual Query Language](https://www.loc.gov/standards/sru/cql/)
## About CQL :mag:
An intuitive query language that allows anyone, **even those who never touched code before**, to query information and make decisions without dealing with code, data processing, or other complicated stuff.

It's like [SQL](https://www.w3schools.com/sql/), but for non-developers. Here are some examples that can be used for searching using CQL:
* page's title
* user's name

## Examples of CQL :grey_exclamation:
* With page's title
    ```text
    dc.title any API
    ```
* With user's name
    ```text
    dc.creator any Caio
     ```
# Implementation process :round_pushpin:
The implementation process consists of only three steps. This flow is for all cases.
## Step :one: - Gathering data :bar_chart:
It consists of gathering the information that will feed the personalization engine and **it is common to all the other steps**
## Step :two: - Defining a personalization strategy and goal :dart:
This is the time to define the audience, whether it is an experiment or not (such as an A/B test), decide what will be personalized, and what metrics will help measure the result of the personalization
## Step :three: - Implementing :wrench:
In this last step the implementation of personalization happens, and eventually the tracking to measure the results.

# Satisfaction survey and integration time :star:
Please take 5 minutes of your time to fill out our satisfaction survey and integration time :link:[here](https://pt.surveymonkey.com/r/DX3KQ3H). This survey is so we can find our shortcomings and improve our work to better serve you.