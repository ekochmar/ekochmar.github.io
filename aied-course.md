---
layout: page
title: AIED course
permalink: /aied-course/
---

This is the webpage for the **Generative AI-powered Educational Applications** course, a PhD-level elective course that I taught at MBZUAI in Spring 2026.

<a name="top"></a>
# Contents:
- [Overview](#overview)
- [Course outline](#course-outline)
- [Reading list](#reading-list)
- Material: [Week 1](#week1), [Week 2](#week2), [Week 3](#week3), [Week 4](#week4), 
[Week 5](#week5), [Week 6](#week6), [Week 7](#week7)


<a name="overview"></a> 
# Overview

This course covers a range of applications empowered by AI – from writing assistants to dialogue-based intelligent tutoring systems – 
across a range of subject domains, including but not limited to language learning and STEM subjects. 
We will cover topics surrounding content and feedback generation using generative AI, adaptation and personalization of AI-driven 
educational systems, multi-modal interactive approaches (including not only text-based but also speech and visual systems), 
agentic AI approaches to educational applications, generative AI model alignment with educational, age- and subject-specific aspects, 
and novel human-computer interaction opportunities in this domain. In addition to such novel opportunities, the course will delve 
into emerging challenges, focusing on ethical issues, societal impact and real-world integration of this technology, and evaluation.

[[To the top](#top)]

<a name="course-outline"></a> 
# Course Outline

- **Week 1**: Introduction, core tasks, fundamental concepts [[go to Week1](#week1)]
- **Week 2**: AI for writing assistance and language learning [[go to Week2](#week2)]
- **Week 3**: Intelligent Tutoring Systems [[go to Week3](#week3)]
- **Week 4**: Learner analytics and personalization [[go to Week4](#week4)]
- **Week 5**: LLM alignment for educational applications [[go to Week5](#week5)]
- **Week 6**: Agentic AI for educational applications [[go to Week6](#week6)]
- **Week 7**: Human-computer interaction and real-life applications [[go to Week7](#week7)]


[[To the top](#top)]

<a name="reading-list"></a> 
# Reading list

- [Opportunities for natural language processing research in education](https://link.springer.com/chapter/10.1007/978-3-642-00382-0_2) (Burstein, 2009)
- [Practical and ethical challenges of large language models in education: A systematic scoping review](https://bera-journals.onlinelibrary.wiley.com/doi/full/10.1111/bjet.13370) (Yan et.al., 2023)
- [COLING tutorial](https://coling2025-edu-llms.github.io)
- [BEA 2025 tutorial on LLMs for Education: Understanding the Needs of Stakeholders, Current Capabilities and the Path Forward](https://docs.google.com/presentation/d/1dPdHNRpQnNg0j1KGtbcfdZT9NiDhxdRCFxbsARiAU4I/edit?usp=sharing)
- [NeuIPS 2024 Workshop on Large Foundation Models for Educational Assessment](https://neurips2024edu.github.io)
- [AAAI 2024 Workshop on AI in Education](https://coling2025-edu-llms.github.io)
- [uWaterloo workshop on Generative AI in K-12 Education](https://uwaterloo.ca/artificial-intelligence-institute/events/workshop-generative-ai-k-12-education)
- [EDM 2024 Workshop: Leveraging Large Language Models for Next Generation Educational Technologies](https://sites.google.com/view/llmworkshopedm/home)
- [KDD 2024 Workshop on AI for Education (AI4EDU): Advancing Personalized Education with LLM and Adaptive Learning](https://ai-for-edu.github.io/workshop_kdd2024.html)
- [Grammatical Error Correction: A Survey of the State of the Art](https://direct.mit.edu/coli/article/49/3/643/115846/Grammatical-Error-Correction-A-Survey-of-the-State) (Bryant et al., 2023).
- [Exploring Effectiveness of GPT-3 in Grammatical Error Correction: A Study on Performance and Controllability in Prompt-Based Methods](https://aclanthology.org/2023.bea-1.18/) (Loem et al., 2023)
Analyzing the Performance of GPT-3.5 and GPT-4 in Grammatical Error Correction (Coyne et al., 2023)
GPT-3.5 for Grammatical Error Correction (Katinskaia et al., 2024)
Prompting open-source and commercial language models for grammatical error correction of English learner text(Davis et al., 2024)
Pillars of Grammatical Error Correction: Comprehensive Inspection Of Contemporary Approaches In The Era of Large Language Models (Omelianchuk et al., 2024)
Controlled Generation with Prompt Insertion for Natural Language Explanations in Grammatical Error Correction (Kaneko et al., 2024)
Large Language Models Are State-of-the-Art Evaluator for Grammatical Error Correction (Kobayashi et al., 2024)
Unraveling Downstream Gender Bias from Large Language Models: A Study on AI Educational Writing Assistance (Wambsganss et al., 2023)
SALMONN: Towards generic hearing abilities for large language models (Tang et al., 2024)
Can GPT-4 do L2 analytic assessment? (Bannò et al., 2024)
Automatic Pronunciation Assessment using Self-Supervised Speech Representation Learning (Kim et al., 2022)
A Study on Fine-Tuning wav2vec2.0 Model for the Task of Mispronunciation Detection and Diagnosis (Peng et al., 2021)
Incorporating uncertainty into deep learning for spoken language assessment (Malinin et al., 2017)
Automated speaking assessment: Using language technologies to score spontaneous speech (Zechner and Evanini, 2019)
The ‘communicative’ legacy in language testing (Fulcher, 2000)
MATHDIAL: A Dialogue Tutoring Dataset with Rich Pedagogical Properties Grounded in Math Reasoning Problems (Macina et al., 2023)
Is ChatGPT a Good Teacher Coach? Measuring Zero-Shot Performance For Scoring and Providing Actionable Insights on Classroom Instruction (Wang and Demszky, 2023)
Are We There Yet? - A Systematic Literature Review on Chatbots in Education (Wollny et al., 2021)
Teaching the science of learning (Weinstein et al., 2018)
Intelligent tutoring systems with conversational dialogue (Graesser et al., 2001)
The 2 sigma problem: The search for methods of group instruction as effective as one-to-one tutoring (Bloom, 1984)

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
	- [WordNetPractice.ipynb](https://colab.research.google.com/drive/1jK1TEXi8_s8_Nnb6VKy9mem6iCsJI7Bc?usp=sharing)
	- [AnalogySolver.ipynb](https://colab.research.google.com/drive/1sLK46LcSDaT7f165Gp4nJZf6GuZ8Z-Ys?usp=sharing)
- Sample solutions:	
	- For [AnalogySolver.ipynb](https://colab.research.google.com/drive/1s44G4TeUhNJp9p3fLXSJvCLCCxLM6i0J?usp=sharing)

[[To the top](#top)]
