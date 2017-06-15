# Chatbot using Python and AIML

This is a very simple chatbot written in Python 3 and AIML (Artificial Intelligence Markup Language). In order to run the chatbot (run the start.py file), install the AIML package:

```
pip install aiml
```
However this package only works with Python 2, so if you're using [PyCharm](https://www.jetbrains.com/pycharm/) with Python 3.x, you can install [Python 2.7.x](https://www.python.org/downloads/) and go to Run > Edit Configurations > Replace Python3 to Python2. But this may not work, and then you'll need to download [PyAIML](https://github.com/weddige/pyaiml3) (an interpreter for AIML).
After you have unpacked the PyAIML, copy all the py files in the aiml file and paste in the aiml file located on your computer (if you have installed Anaconda, go to: User/Anaconda3/Lib/sites-package/aiml).

This chatbot is a retrieval-based model (use a repository of predefined responses and some kind of heuristic to pick an appropriate response based on the input and context) and the predefined responses are totally based on the A.L.I.C.E. Project. We've been used all the AIML code files provides by A.L.I.C.E. Foundation, available at:

* [The Annotated A.L.I.C.E. AIML](http://www.alicebot.org/aiml/aaa/)



![alt text](https://raw.githubusercontent.com/heitorb/Searching_on_Twitter_using_Python/master/python.png) ![alt text](https://raw.githubusercontent.com/heitorb/Chatbot_using_Python_and_AIML/master/alice.jpg)
