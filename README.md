# Punctuation_Prediction
**Objective**:
The main objective of this project is to build a model that can predict punctuation in text. This is a classification problem with a supervised learning technique. 

The task of predicting punctuation is crucial for enhancing the output of Automatic Speech Recognition (ASR) systems. It focuses on inserting the appropriate punctuation in text that lacks it.
 
What are the punctuations: We will predict the following seven punctuations.
1. Period, 
2. Question mark, 
3. Exclamation point, 
4. Comma, 
5. Colon,
6. Semicolon,
7. Hyphen 
**Proposing a new training dataset:**
I aim to find a novel dataset to train the model that was not previously used for punctuation prediction. I am proposing the TED Talk en dataset, which is a collection of over 4,000 TED talks, including scripts in many languages. I am using only the English version. The dataset was created by Miguel Corral Jr. and is available on Kaggle (ref: *). 

**A quick check of the TED Talk en dataset:**
The TED Talk dataset has 3,338 rows (after removing the missings), which means it contains 3,338 scripts from 3,338 presenters. 
The first row, which is the first script from the first presenter, has 2,153 words. 
Approximately, a total of 7,186,714 (3338 * 2153 = 7,186,714) words.

**Acknowledgments**:
This project is based on Punctuation Prediction (link: https://github.com/s-mostafa-a/punctuation-prediction-with-NER/tree/main) by SeyedMostafa Ahmadi. The code in this repository is licensed under the MIT License, the same as the original project. See the LICENSE file for the full license text.
