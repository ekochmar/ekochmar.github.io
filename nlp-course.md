---
layout: page
title: NLP course
permalink: /nlp-course/
---

This is the webpage for the [Introduction to Natural Language Processing](https://www.bath.ac.uk/catalogues/2022-2023/cm/CM30320.html) course that I'm teaching at the University of Bath this semester (Fall 2022).

**Prerequisites**: The course assumes programming knowledge of Python and some familiarity with Machine Learning algorithms; it does not require any prior knowledge of linguistics or Natural Language Processing.

The course closely follows the material of my new book, "**Getting Started with Natural Language Processing**” (available on [Manning](https://www.manning.com/books/getting-started-with-natural-language-processing?utm_source=linkedin&utm_medium=author&utm_campaign=book_kochmar_getting_10_1_19) and [Amazon](https://www.amazon.co.uk/Getting-Started-Natural-Language-Processing/dp/1617296767/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=)).
It covers a wide range of topics in NLP and provides you with fundamental knowledge of NLP concepts as well as practical skills. 
By the end of this course, you will be able to build your own NLP application in an end-to-end manner.

<a name="top"></a>
# Contents:
- [Overview](#overview)
- [Learning outcomes](#learning-outcomes)
- [Reading list](#reading-list)
- Material: [Week 1](#week1), [Week 2](#week2), [Week 3](#week3), [Week 4](#week4), [Week 5](#week5), [Week 6](#week6), [Week 7](#week7)


<a name="overview"></a> 
# Overview

This is a semester-long course with one 2-hour long lecture per week. 
In addition to lectures, students are provided with detailed handouts and practical programming exercises.

Each week addresses a different NLP application and discusses it in detail, introducing relevant **NLP concepts and techniques**. 

**Applications and topics** covered include, among others:

- Information retrieval
- Information extraction
- Text classification
- Topic modelling
- Word embeddings
- Semantic models

[[To the top](#top)]

<a name="learning-outcomes"></a> 
# Learning outcomes

1. Demonstrate knowledge of the **fundamental principles** of natural language processing.
2. Demonstrate understanding of **key algorithms** for natural language processing.
3. Write **programs** that process language.
4. Design your own **end-to-end projects** in NLP.
5. Evaluate the **performance** of programs that process language. 
6. Assess feasibility and appropriateness of **novel NLP approaches** presented in literature.

[[To the top](#top)]

<a name="reading-list"></a> 
# Reading list

- Ekaterina Kochmar (2022). **Getting Started with Natural Language Processing**. 
Manning Publications, ISBN: 9781617296765. URL: [Manning](https://www.manning.com/books/getting-started-with-natural-language-processing?utm_source=linkedin&utm_medium=author&utm_campaign=book_kochmar_getting_10_1_19); 
[Amazon](https://www.amazon.co.uk/Getting-Started-Natural-Language-Processing/dp/1617296767/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=);
for the students at the University of Bath, the book is available via the university's library service.
- Dan Jurafsky and James H. Martin (2009). **Speech and Language Processing** (2nd edition). 
Prentice-Hall Inc., Upper Saddle River, NJ, USA. ISBN: 0131873210. 
URL: [2nd edition](https://github.com/rain1024/slp2-pdf/tree/master/chapter-wise-pdf); 
[3rd edition](https://web.stanford.edu/~jurafsky/slp3/)
- Steven Bird, Ewan Klein, and Edward Loper (2009). **Natural Language Processing with Python**. 
O'Reilly Media, Inc. ISBN: 978-0-596-51649-9. 
URL: [NLTK book](http://www.nltk.org/book/)

[[To the top](#top)]

<a name="week1"></a> 
# Week 1: Introduction to Natural Language Processing

This week's material will **introduce** you to the field of Natural Language Processing, 
first via overviewing its history and the way the field and its algorithms developed over decades, 
then by presenting and discussing the **most popular NLP applications and techniques** used to tackle NLP tasks, 
and finally by linking the NLP techniques and concepts to other fields and approaches.

In addition, in the course of this week you will make your first practical steps in implementation of an NLP algorithm. 
You will learn how to structure an NLP project from the beginning to end and you will focus on the first crucial step in an NLP application – **tokenization**. 
You will learn why this is challenging and how a tokenizer can be implemented in practice. 
Finally, we will conclude with the remarks on language use and word distribution, 
and observations on the implications this has for NLP algorithms. 
You will also run some **frequency analysis** yourself – such analysis is often an important step in the preliminary data investigation, 
which may inform and help you shape your approach to the specific NLP task you are working on.

- [Handout](https://drive.google.com/file/d/1JZKcb35nCIpWnyrOh0ishHyrbWLU1AdD/view?usp=sharing) for Week 1
- [Slides](https://drive.google.com/file/d/18ZwmPMy-v-kJ2WYoLVCgyNuuPuWMUlP2/view?usp=sharing) on Introduction to NLP
- Programming exercises:
	- [Tokenization.ipynb](https://colab.research.google.com/drive/1FqqmP1ux40fmuikDGmnriIqwzeGsV7UT?usp=sharing)
	- [FrequencyAnalysis.ipynb](https://colab.research.google.com/drive/1OZf4KGBhZctl_zGLLbZv-u-qqCnDV4gg?usp=sharing)
- Sample solutions:
	- For [Tokenization.ipynb](https://colab.research.google.com/drive/1KcYLNzrlS98kqwErzZRM7hQKBkAjZzM5?usp=sharing)
	- For [FrequencyAnalysis.ipynb](https://colab.research.google.com/drive/1K3NN3SXDlBSt3wEfet4Y8DmXek0WT4vm?usp=sharing)


[[To the top](#top)]


<a name="week2"></a> 
# Week 2: Introduction to Information Retrieval

This week, we will "zoom in" on one of the popular and widely used NLP applications – **Information Search** or **Information Retrieval (IR)**. 
We will look closely into each step involved in this application, and by the end of this week you will be able to implement an information search algorithm yourself.

Information search is not only a popular application (you may recall that it helps you find relevant information on the Internet as well as in a collection of documents on your computer), but also a suitable one to be working on in Week 2. 
Besides learning a few practical aspects about the information search algorithms, you will also learn about such fundamental NLP concepts and techniques as **vector-based representations**, **lemmatization** and **stemming**, and **term and document weighting**. 
These concepts and techniques are used across multiple tasks in NLP, and you will be using them again and again in the next weeks.

- [Handout](https://drive.google.com/file/d/1eJiFnpjtvJZTAhMxqVF0_SSKTNAnk3IR/view?usp=sharing) for Week 2
- [Slides](https://drive.google.com/file/d/1SiWOGf9911aki29r1KqMbn8aKaTRw1X3/view?usp=sharing) on Introduction to IR
- Programming exercises:
	- [Data](https://drive.google.com/file/d/1ru80Kxi8BD2NizRuQQwN0EOLbaQLSol7/view?usp=sharing)
	- [TermWeighting.ipynb](https://colab.research.google.com/drive/1ZUrQ_Mx-4oAbsPWoqjVYSm3ll7uiLIZr?usp=sharing)
	- [EndToEnd.ipynb](https://colab.research.google.com/drive/1MlJiUVC_4cN5YZVYP-8mojJdEThquCHk?usp=sharing)
- Sample solutions:
	- For [TermWeighting.ipynb](https://colab.research.google.com/drive/1w8Oefxz_1l3J2efR8AF6ULiH62WPGw82?usp=sharing)
	- For [EndToEnd.ipynb](https://colab.research.google.com/drive/1GkB6uqpgGRDkGKTXx8IwNe7KXtwOW_w-?usp=sharing)


[[To the top](#top)]


<a name="week3"></a> 
# Week 3: Part-of-Speech Tagging

This week and next week will follow up with another popular and widely used NLP application – **Information Extraction**.

In addition to searching for a set of documents that answer your information need, which is performed by Information Retrieval algorithms, you may be interested in getting a precise answer to a specific question. 
For example, if you Google for "artificial intelligence", the search engine will come back with a long list of pages discussing various aspects of artificial intelligence, from the definition and an overview of the field, to specific techniques and applications. 
However, if you are interested in the definition only, you would ask "**What** is Artificial Intelligence?" and expect to get a specific answer giving such a definition. 
Information Extraction (IE) is the NLP task that addresses such challenges.

As with IR, there is a reason for why we are talking about IE relatively early in the course on NLP: while working on an IE algorithm, you will also learn about fundamental NLP concepts and techniques, starting this week with **part-of-speech tagging**. 
This week, we will focus on how this NLP task is solved: specifically, we will discuss **sequence modelling** approaches used in NLP, look into the theory behind such models, and learn how part-of-speech tagging is solved using a sequence model.

- [Handout](https://drive.google.com/file/d/1gZ4r_awH3nURP9DhXYR7MgjH7cSaCy4b/view?usp=sharing) for Week 3
- [Slides](https://drive.google.com/file/d/1qqVrAVyZrot0yhCAz6c02-oVHbdR8lqQ/view?usp=sharing) on PoS tagging
- Homework on the Viterbi algorithm:
	- [Task](https://drive.google.com/file/d/1Pm-S7qPEgsoMOaKG7EKQIpw3kAzoiu_Q/view?usp=sharing)
	- [Solution](https://drive.google.com/file/d/1IpJudJHOAeBTSWjYI2C7rUXz-tlv7vhE/view?usp=sharing)
- Programming exercises:
	- [PoS tagging](https://colab.research.google.com/drive/1Eu0MNeIdjDmJ7VMK-uZLeKk8geYfbOT5?usp=sharing)

[[To the top](#top)]

<a name="week4"></a> 
# Week 4: Syntactic Analysis 

Last week we started looking into another popular and widely used NLP application – **Information Extraction (IE)**. 
A reminder: while Information Retrieval algorithms help you find a set of documents that generally answer your information need, IE algorithms are used to identify precise answers to specific questions. 

Last week, we focused on part-of-speech tagging – the task that helps you identify what category (part of speech) a word belongs to. 
This week we will continue looking into the challenges that have to be solved in order to implement an IE application. 
Specifically, we will focus on how to detect the grammatical relations that link words of different parts of speech to each other and identify the roles that different groups of words play in a sentence. 
We will look into **chunking** and **parsing**. 
The final section then will bring the concepts and techniques studied over these two weeks together and show you how to implement an IE application in practice.

- [Handout](https://drive.google.com/file/d/1hLg6uHxX9UI3uCInPegILcjV0g8lbQum/view?usp=sharing) for Week 4
- [Slides](https://drive.google.com/file/d/1bVwzOzU1-1PokphHvUDIv3ozdHvbPURn/view?usp=sharing) on Syntactic analysis
- Programming exercises:
	- [InformationExtraction.ipynb](https://colab.research.google.com/drive/1J086XEd3fL6Rgc98NyxYKnzSoJKQeeqD?usp=sharing)
- Sample solutions:	
	- For [InformationExtraction.ipynb](https://colab.research.google.com/drive/1zKU26KAU-SCSjZyIQq_wC3MiIlp7FFvr?usp=sharing)

[[To the top](#top)]

<a name="week5"></a> 
# Week 5: Text Classification Approaches

This week you will build upon the knowledge acquired over the previous weeks and will start working on the applications at the intersection of machine learning (ML) and NLP. 
You may recall from Week 1 that ML is widely used in many NLP tasks. 
This week, you will start with one of the most popular frameworks – **supervised machine learning**, and specifically **text classification tasks**. 
Classification is an activity in which we humans engage on a regular basis: it is concerned with identification of groups of objects or phenomena on the basis of their traits, similarities, features or other criteria. 
Often, the categories are clearly defined, and the features are easy to determine; however, in some cases, classification may be a challenging task even for humans.
While a computer can perform classification too, within a supervised learning framework, it needs to be "told" what the classes are and which features may distinguish between these classes.

This week, you will focus on two popular text classification tasks – **sentiment analysis**, concerned with classifying texts into those expressing positive and negative sentiment, and **topic classification**, concerned with classifying texts based on their topic.

- [Handout](https://drive.google.com/file/d/1NPvjy3eEsGNLymXoO7-zn5qGnKwKu-MB/view?usp=sharing) for Week 5
- [Slides](https://drive.google.com/file/d/1yY6sVmrtgNaGIRHjTVE2T7G36d6KYzeJ/view?usp=sharing) on Text classification approaches
- Programming exercises:
	- [AuthorProfiling.ipynb](https://colab.research.google.com/drive/1hYkylMZlUZz5s9c64rSaPqh54fBGKglf?usp=sharing)
	- [TopicClassification.ipynb](https://colab.research.google.com/drive/1fupzst59thAH2wTFyW0iI3_3zfVTNPte?usp=sharing)
- Sample solutions:	
	- For [AuthorProfiling.ipynb](https://colab.research.google.com/drive/1xOIi0sT-Tpielxu5Akmw-NRFAk7mz1PI?usp=sharing)
	- For [TopicClassification.ipynb](https://colab.research.google.com/drive/1INm3IiA2pbeiz4HLVPQvMd7T_xr2geuy?usp=sharing)

[[To the top](#top)]

<a name="week6"></a> 
# Week 6: Unsupervised approaches in NLP

This week you will continue learning about the application of the machine learning approaches to NLP. 
One of the key aspects that allow you to frame a task as a supervised machine learning task is the availability of clearly defined classes and, importantly, data that is annotated with such classes, for example, by domain experts. 
Then a machine learning algorithm can be trained on such labelled data, and it can learn to associate the features with the classes. 
Despite the fact that the amount of such labelled training data is consistently growing, enabling researchers and practitioners to develop further ML and NLP applications, data annotation is a challenging, time-consuming and often expensive task. 
An alternative to this framework is **unsupervised machine learning**. 
Unsupervised approaches are useful not only in cases where labelled data is unavailable or hard to collect, but also for the tasks where classes are not known in advance or can change over time. 

This week, you will learn about the applications of unsupervised machine learning in NLP and, continuing with the theme of topic analysis, you will apply two unsupervised methods in practice – **k-means clustering** for topic analysis and **Latent Dirichlet allocation** (LDA) for **topic modelling**.

- [Handout](https://drive.google.com/file/d/1XgaGg9d6eBklY8ioYAIdh91S0cLr2xdZ/view?usp=sharing) for Week 6
- [Slides](https://drive.google.com/file/d/1d1fGu60KWS2fbA5P3N4W9d2mAxF4Eid7/view?usp=sharing) on Unsupervised approaches in NLP
- Programming exercises:
	- [TopicClustering.ipynb](https://colab.research.google.com/drive/1u9AaE1BHvKnDuqkgNHUDwphaIHcAglPU?usp=sharing)
	- [TopicModelling.ipynb](https://colab.research.google.com/drive/1ec898KkQNRwURsfhPR6hY0SiLj5zwq5M?usp=sharing)
- Sample solutions:	
	- For [TopicClustering.ipynb](https://colab.research.google.com/drive/138R6xRmst3PIzNRIqTYtZSNTcowRAHVH?usp=sharing)
	- For [TopicModelling.ipynb](https://colab.research.google.com/drive/1BBRx81n41hzVNhMKvIJGR32Vh7BWXSg9?usp=sharing)

[[To the top](#top)]


<a name="week7"></a> 
# Week 7: Semantics and meaning representation

All approaches discussed so far essentially used words as symbols devoid of any particular meaning. 
While it is true that the algorithms you have been looking into did not need to know what a word means to use it as an informative feature in a particular task (e.g., a spam filter does not actually need to understand what the word *lottery* means to associate it with the spam class), it is a simplistic view of language, and word meaning plays a central role in more challenging, natural language understanding and reasoning tasks.

The subfield of linguistics and NLP that studies meaning in language is called **semantics**, and this course would not have been complete without the discussion of the methods of semantic analysis and meaning representation. 

- [Handout](https://drive.google.com/file/d/11y50RTi0NKX81GhLusEGfS1u_R5QspVA/view?usp=sharing) for Week 7
- [Slides](https://drive.google.com/file/d/1K3WNEU0s36RMzdG29OsUm-PY38AxxofW/view?usp=sharing) on Semantics and meaning representation
- Programming exercises:
	- [TopicClustering.ipynb](https://colab.research.google.com/drive/1u9AaE1BHvKnDuqkgNHUDwphaIHcAglPU?usp=sharing)
	- [TopicModelling.ipynb](https://colab.research.google.com/drive/1ec898KkQNRwURsfhPR6hY0SiLj5zwq5M?usp=sharing)
- Sample solutions:	
	- For [TopicClustering.ipynb](https://colab.research.google.com/drive/138R6xRmst3PIzNRIqTYtZSNTcowRAHVH?usp=sharing)
	- For [TopicModelling.ipynb](https://colab.research.google.com/drive/1BBRx81n41hzVNhMKvIJGR32Vh7BWXSg9?usp=sharing)

[[To the top](#top)]


