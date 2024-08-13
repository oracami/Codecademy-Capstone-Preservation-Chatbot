# LA-Conservancy-Chatbot
Written by Camille Elston
Codecademy username: @oranicole

I chose a retrieval chatbot because I want a chatbot that has pre-defined answers but allows for a diversity of inputs. A retrieval system was the best solution in this case. The LA Conservancy Chatbot takes the form of software, embedded into the official website. It offers a faster and easier way to get answers to common preservation questions. Creating the LA Conservancy Chatbot allows us to respond to more constituents more efficiently, and create more time for staff to handle complex issues. Our users can expect to get their answers quicker than if through traditional email.

User Scenario: a user visits our website to find more information about how to protect a resource. They find the chatbot and ask their question. The chatbot returns a list of resources they can use to protect the place they are concerned about.

Alternate Flow: a user visits our website and asks a question, but there is no correct answer. Currently, the chatbot will continue to provide one of the responses, however, the chatbot will continue to be developed to give users an option to reach out to staff if their answer is not met. The contact would primarily involve the user sending an email with precise contact information.

Techniques: I built the capstone using visual code. To start, I reviewed code from the rule-based and retrieval chatbot lessons and used it as a base framework for this chatbot. I updated the import names and installed the appropriate modules. For spacy, I downloaded and used de_core_news_lg. I then edited the code for more extensive use and better exit responses. The program will continue to be edited for functionality.

This capstone means a lot for me. I wanted to build a project that could be used within my workplace to make our job easier. In order to make this happen, I had to refresh the python I knew and learn more. Jumping off Codecademy platform was a real challenge - I learned how to create new environments, make sure my libraries were at the same licenses, make sure the correct kernels were running, and address any warnings that popped up in the terminal. Most of the process has been troubleshooting. I don't have any ethical concerns for this particular project; it is a closed domain program, and the responses are highly specific. 

Project Dependencies: 
import os
os.environ['SPACY_WARNING_IGNORE'] = 'W008'
import warnings
warnings.filterwarnings("ignore", message=r"\[W008\]", category=UserWarning)
import re
from collections import Counter
from nltk import pos_tag
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords
import spacy
word2vec = spacy.load('de_core_news_lg')
stop_words = set(stopwords.words("english"))

Use Sample: https://github.com/user-attachments/assets/17b156ed-43c1-471f-9840-dcefdfd8520c




