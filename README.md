# Project Title
WhatsApp Group Chat Analysis

# Project Overview
This project involves analyzing WhatsApp chat data by exporting chats to a text file and then using Python to wrangle and analyze the data. The analysis includes 
exploring the chat data, cleaning and preparing the data, and performing visualizations to gain insights into the data. The project provides a better understanding of 
the patterns.

# Technologies Used
I'll be utilizing various libraries and packages, such as Pandas, Matplotlib, and NLTK, which can help with tasks such as data manipulation, visualization, and natural 
language processing.

# Data Sources
I used the exported WhatsApp chat text file from the group chat.

# Data Preparation
To prepare the data for analysis, I followed a few key steps. First, I exported the WhatsApp chat history as a .txt file and saved it to my local machine. I then used 
Python and the Pandas library to read in the data and convert it into a usable format for analysis.
Next, I performed some initial data cleaning to remove any unnecessary text, such as timestamps and system messages. I also identified and removed any duplicate messages 
that may have been sent multiple times. Once the data was cleaned, I created a new column to extract the date and time information from each message.
To gain a deeper understanding of the messages, I performed some text preprocessing using the Natural Language Toolkit (NLTK) library. This involved removing stop words, 
punctuation, and performing stemming and lemmatization to standardize the text. I also created a new column to calculate the word count for each message.
Finally, I grouped the messages by date and aggregated the word count for each day, allowing us to visualize the messaging trends over time.

# Conclusion
Through the analysis, we gained insights into the group's communication patterns, trends, and habits, revealing a fascinating look at how we communicate in today's digital age.
But what does this all mean for our future interactions? As we continue to rely on messaging as a primary mode of communication, it's essential to understand how our 
habits are changing and what they might look like in the future. With the power of data analysis, we can uncover these insights and use them to improve our 
communication, both online and offline. 

Overall, this analysis of a WhatsApp group chat serves as a reminder of the power of data and what it can reveal about our daily interactions. 
By continuing to explore and analyze our communication habits, we can gain valuable insights into ourselves and our relationships, ultimately leading to more 
meaningful and effective conversations in the future.

# Author
Shakir Abdulraqib Omotosho. Email: abdulraqibshakir03@gmail.com

# License
Copyright (c) [2023] [Abdulraqib Omotosho]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.







