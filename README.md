# Natural Language Processing

## Real and Fake news

Project made with my classmate Alexandre Olivier during our master’s in business Analytics and Big Data at IE school of human science and technology.

Binary classification of real and fake tweets using NLTK pre-processing and divers machine learning algorithms such as SDG classifier, Linear SVM, PassiveAgressive etc.

Best in sample score 93.5% accuracy – Out of sample score unknown (keep hidden by the professor, but according to his feedback we were on the top 5% of the class).

Note: the aim was to use NLTK pipeline for the text pre-processing and we were not allowed to use more “advance” technics such as LSTM or other Deep learning architectures for this project.

Note: the aim of the project was to use NLTK pipeline for the text pre-processing. Thus, we were not allowed to use more “advance” technics such as LSTM or other Deep learning architectures.




## Seq2Seq (machine translation)

Created a prototype of a machine translation from French to English by adding an emoji at the end of the translation.

-Seq2seq model: Encoder - decoder LSTM with 3 layers (trained locally) with a clean dictionary of 40000 words and sentences- Bleu score of 50%
-Emojifier model: Encoder – decoder LSTM with GLOVE for synonym -Accuracy of 78%
-Application: summary of the data and models that could be used as the back end of future prototype

**Our methodology**:

![alt text](https://github.com/viretc/Natural-Language-Processing/blob/master/Seq2seq/Images/meto1.PNG)

![alt text](https://github.com/viretc/Natural-Language-Processing/blob/master/Seq2seq/Images/meto2.PNG)


Thank you to Annie Pi for the presentation and to Anchal Jaiswal for helping me with the emoji model
