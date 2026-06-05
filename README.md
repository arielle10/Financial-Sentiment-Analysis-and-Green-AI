# Financial Sentiment Analysis and Green AI

## Overview

This project compares SimpleRNN and LSTM neural networks for financial sentiment classification while evaluating both predictive performance and environmental impact. Using the Financial PhraseBank dataset, models classify financial news statements as positive, neutral, or negative.

## Objective

The primary goal was to examine the tradeoff between model accuracy and computational sustainability. In addition to standard performance metrics, carbon emissions and training efficiency were measured using CodeCarbon.

## Project Materials 
- [Final Research Report](Financial_Sentiment_Green_AI_Report.pdf)
- [Code Notebook - HTML](Financial_Sentiment_Green_AI_Notebook.html)
- [Code Notebook - ipynb](Financial_Sentiment_Green_AI_Notebook.ipynb)

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

## Results

| Model        | Accuracy | Emissions (kg CO₂) |
|--------------|----------|------------------|
| SimpleRNN (16) | 0.75      | 0.001002 |
| SimpleRNN (32) | 0.72      | 0.000402 |
| LSTM (16)      | 0.63      | 0.000013 |
| LSTM (32)      | 0.62      | 0.000012 |

SimpleRNN achieved the highest accuracy, while LSTM models produced substantially lower emissions and faster training times. The results demonstrate the importance of considering both predictive performance and environmental cost when selecting deep learning architectures.

## Key Findings

* Energy consumption depended more on hardware efficiency and training behavior than on model size alone.
  
* Although LSTM models contained more parameters, they trained substantially faster on the Apple M2 Pro system and produce significantly lower estimated carbon emissions.
  
* SimpleRNN(16) achieved the highest classification accuracy but required the longest training time and generated the highest emissions.
  
* LSTM models provided the strongest balance between predictive performance and sustainability, with only minor differences between the
  16- and 32-unit configurations.

* Results demonstrate that model selection should consider runtime efficiency, hardware interaction, and environmental impact in addition to predictive accuracy.

  


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
