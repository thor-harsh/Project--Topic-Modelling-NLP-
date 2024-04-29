# Project--Topic-Modelling-NLP-

<table>
  
**In this project we will be working with a dataset of over 400,000 quora questions that have no labeled cateogry, and attempting to find 20 cateogries to assign these questions to. The .csv file of these text questions is attached above. We'll be grouping different reviews from questions from this csv file to various topics using NMF(Non-Matrix-Factorization) in Natural Language Processing.** <br></br>

We will perform three tasks to perform the final grouping of different reviews on topics:<br></br>

1: We will grab vocabulary of words <br>
2: Grabbing the topic<br>
3: Grabbing the words with highest probability for a given topic<br>

Here we will using TfIdfVectorization whereas in LDA(LatentDirichletAllocation) we have used CountVectorizer for creating the sparse matrix.<br></br>

**Before jumping to the code lets understand NMF(Non-Matrix-Factorization), and NLP(Natural Language Processing) First**...<br></br>


**What is NMF?** <br></br>

Non-negative Matrix Factorization (NMF) is a dimensionality reduction technique commonly used in Natural Language Processing (NLP) for topics extraction and document clustering. In NMF, a matrix representing the relationships between terms (words) and documents is factorized into two lower-dimensional matrices, typically referred to as the term-topic matrix and the topic-document matrix. <br></br>

**What is (NLP)Natural Language Processing**?<br></br>

NLP or Natural language processing is an interdisciplinary subfield of computer science and linguistics. It is primarily concerned with giving computers the ability to support and manipulate human language.<br></br>

NLP combines computational linguistics—rule-based modeling of human language—with statistical, machine learning, and deep learning models. Together, these technologies enable computers to process human language in the form of text or voice data and to ‘understand’ its full meaning, complete with the speaker or writer’s intent and sentiment.<br></br>

NLP drives computer programs that translate text from one language to another, respond to spoken commands, and summarize large volumes of text rapidly—even in real time. There’s a good chance you’ve interacted with NLP in the form of voice-operated GPS systems, digital assistants, speech-to-text dictation software, customer service chatbots, and other consumer conveniences. But NLP also plays a growing role in enterprise solutions that help streamline business operations, increase employee productivity, and simplify mission-critical business processes.<br></br>


**Important Note: Go through the quora_questions.csv file and get a proper understanding of it before jumping to the code.**


</table>

**So what are you waiting for...? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks!**


