# Financial Sentiment Analysis and Green AI

## Overview

This project compares SimpleRNN and LSTM neural networks for financial sentiment classification while evaluating both predictive performance and environmental impact. 
Using the Financial PhraseBank dataset, models classify financial news statements as positive, neutral, or negative.

## Objective

The primary goal was to examine the tradeoff between model accuracy and computational sustainability. In addition to standard performance metrics, 
carbon emissions and training efficiency were measured using CodeCarbon.

## Tools and Technologies

* Python
* TensorFlow / Keras
* CodeCarbon
* Financial PhraseBank Dataset
* Natural Language Processing (NLP)

## Models Evaluated

* SimpleRNN (16 units)
* SimpleRNN (32 units)
* LSTM (16 units)
* LSTM (32 units)

## Key Findings

## Key Findings

* Energy consumption depended more on hardware efficiency and training behavior than on model size alone.
* Although LSTM models contained more parameters, they trained substantially faster on the Apple M2 Pro system and produced significantly
  lower estimated carbon emissions.
* SimpleRNN(16) achieved the highest classification accuracy but required the longest training time and generated the highest emissions.
* LSTM models provided the strongest balance between predictive performance and sustainability, with only minor differences between the
  16- and 32-unit configurations.
* Results demonstrate that model selection should consider runtime efficiency, hardware interaction, and environmental impact in addition
  to predictive accuracy.


## Skills Demonstrated

* Deep Learning
* Natural Language Processing
* Model Evaluation
* Data Analysis
* Green AI
* Python Programming

## Author

Arielle Cameron
American University – B.S. Statistics and Data Science, Honors in Mathematical Sciences
