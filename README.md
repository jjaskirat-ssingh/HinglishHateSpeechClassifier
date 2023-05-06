# HinglishHateSpeechClassifier

Classifying tweets into Non-Offensive, Hate Speech and Abusive using classical supervised machine learning algorithms.

#### Hinglish: 
Hinglish is a common tongue found in casual conversations where a combination of Hindi and English phrases are used together in the same context.
In NLP parlance, it’s called code-mixing.

#### Code-mixing:
Code-mixing refers to fluid alteration between two or more languages in a given utterance. This phenomenon is ubiquitous and more natural in multilingual communities, and is highly prevalent in social media platforms.

Developing tools that can comprehend mixed texts can have a multitude of advantages, ranging from socially responsible NLP applications such as moderating abusive content in social media to improve naturalness of ubiquitous technologies such as conversational AI assistants and further to develop socio-cultural studies around human cognition, such as why and when people code-mix.

Example: 
 T1 : “My life is revolving around ‘bhook lagri hai’ and ‘zyada kha liya”’ 
 Translation: My life is revolving around ‘I am hungry’ and ‘I ate too much’

#### Hate Speech Vs Abusive Speech:
Hate speech is an act of offending a person or a group as a whole on the basis of certain key attributes such as religion, race, sexual orientation, gender, ideological background, mental and physical disability. Whereas, Abusive speech is offensive speech with a vague target and mild intention to hurt the sentiments of the receiver.

#### Dataset:
Puneet Mathur, Rajiv Shah, Ramit Sawhney, and Debanjan Mahata. 2018. Detecting Offensive Tweets in Hindi-English Code-Switched Language. In Proceedings of the Sixth International Workshop on Natural Language Processing for Social Media, pages 18–26, Melbourne, Australia. Association for Computational Linguistics.

#### Approach:
 - Cleaning and Preprocessing the tweets.
 - Generate new features from the cleaned data.
 - Try different models using the extracted features. 
 - Build a custom stacking classifier to increase the overall performance.
