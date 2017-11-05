# How computes store data
Computes can store multiple types of data such as images, text, audio files, videos, executable files, and so forth. In the end, it does not matter what we store in our computer everything is stored using a **binary representation**. Binary systems represent information and data exclusively using sequences of *0's* and *1's*. For instance, *0* represents the number 0 in a binary system, *1* represents the number 1, *10* represents the number 2, *11* represents the number 3, *100* represents the number 4, *101* represents the number 5, and so forth.

Each element (0 or 1) that is part of a binary sequence like for instance *10010* is called a **bit**. When a binary sequence has exactly 8 bits we say that we have a **byte** (e.g., *10101110*). A text character like '*a*', '*b*' or '*c*' are represented using at least a sequence of 1 byte (8 bits). For example, the character *'a'* would be represented by *01100001*. A string of text is no more than a sequence of bytes, with as many bytes as characters in the text. A string like "*Hello!*" would be represented using at least 6 bytes (one per each character): 
*01001000 01100101 01101100 01101100 01101111 00100001*

If internally text is nothing more than a sequence of 0's and 1's, how come that engines like Google or chatbots are able to interpret those binary sequences and understand their meaning? This is all called thanks to an artificial intelligence technology named as **natural language processing**

# Natural Language Processing
Natural Language Processing aims at **processing, understanding, and generating** human communication. It is clear that we, as humans, do not use sequences of 0's and 1's to communicate with others. At least, it is not natural to us. We use human communication or natural languages like English, Spanish, French, or Japanese to communicate with others, either writing or speaking.
