# How computes store data
Computes can store multiple types of data such as images, text, audio files, videos, executable files, and so forth. In the end, it does not matter what we store in our computer everything is stored using a **binary representation**. Binary systems represent information and data exclusively using sequences of *0's* and *1's*. For instance, *0* represents the number 0 in a binary system, *1* represents the number 1, *10* represents the number 2, *11* represents the number 3, *100* represents the number 4, *101* represents the number 5, and so forth.

Each element (0 or 1) that is part of a binary sequence like for instance *10010* is called a **bit**. When a binary sequence has exactly 8 bits we say that we have a **byte** (e.g., *10101110*). A text character like '*a*', '*b*' or '*c*' are represented using at least a sequence of 1 byte (8 bits). For example, the character *'a'* would be represented by *01100001*. A string of text is no more than a sequence of bytes, with as many bytes as characters in the text. A string like "*Hello!*" would be represented using at least 6 bytes (one per each character): 
*01001000 01100101 01101100 01101100 01101111 00100001*

If internally text is nothing more than a sequence of 0's and 1's, how come that engines like Google or chatbots are able to interpret those binary sequences and understand their meaning? This is all called thanks to an artificial intelligence technology named as **natural language processing**

# Natural Language Processing
Natural Language Processing aims at **processing, understanding, and generating** human communication. It is clear that we, as humans, do not use sequences of 0's and 1's to communicate with others. At least, it is not natural to us. We use human communication or natural languages like English, Spanish, French, or Japanese to communicate with others, either writing or speaking.

Ideally, we would like computers to understand how we talk and how we write, because saying or typing "I want restaurants in a radius of 1 mile" is actually easier than navigating a bunch of menus and setting multiple options for such a simple search. Also, if possible, we want the computer to tell us about the restaurants that it has found instead of browsing many results. However, a computer needs to understand and generate our language for that matter.

How can a computer understand our communication, say a sentence like "*John hit the ball*". If you remember school, we can analyze sentences to find the subject, the predicate, the direct object, and other syntactic terms in a sentence. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/ParseTree.svg/1024px-ParseTree.svg.png" width="50%" alt="Syntactic analysis">

A computer must carry out a similar analysis. In the first decades of natural language processing, this analysis was carried out using man-created static rules called **grammars** that we would use to match parts in a sentence with syntactic terms like the subject and predicate. However, very soon people realized that language was so flexible that it was very difficult to represent all its flexibility. Researchers found that in order to analyze natural language, it was easier to use large databases with annotated text (i.e., labelled with the syntatic terms like subject, predicate, direct object) and use **statistics** and **probabilistic methods** to extract flexible grammar rules or patterns that frequently help us to identify parts in a sentence from data. 

In addition to that, once the computer has identified the role of words in a sentence, a computer needs to know their semantics: what they mean. This analysis is called **semantic analysis**, and it is one of the most complex parts in natural language processing as language and words are often ambiguous. 

There are two main areas of study in natural language processing:
- Natural language understanding, whose aim is to make computer capable of understanding the human language.
- Natural language generation, whose aim is to transform data stored in a computer into a message in human language.

These technologies are a vital part in search engines, chatbots, automatic translation and voice interfaces, but their applications include any domain where one needs a computer to understand or generate our language!

# Research more on Natural Language Processing!

Now it is time to kick off your research. Watch the following resources and look for additional explanations on natural language processing:

<p align="center">
<a href="https://www.youtube.com/watch?v=jubBtD-C9rw"><img align="center" src="https://img.youtube.com/vi/jubBtD-C9rw/0.jpg" alt="NLP I"></a>
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=IKftaqRFyxE"><img align="center" src="https://img.youtube.com/vi/IKftaqRFyxE/0.jpg" alt="NLP II"></a>
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=3Q8wacwA4gs"><img align="center" src="https://img.youtube.com/vi/3Q8wacwA4gs/0.jpg" alt="NLP III"></a>
</p>

<p align="center">
<a href="https://www.lifewire.com/applications-of-natural-language-processing-technology-2495544"><img align="center" src="https://fthmb.tqn.com/8OsPHsqT-QGA3314o8zAqyxR6cQ=/768x0/filters:no_upscale()/GettyImages-498637581-57b9bf7b5f9b58cdfdbd783b.jpg" width="50%" alt="NLP III"></a>
</p>





