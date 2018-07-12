# FastAi-ML
ML Notebooks of FastAi

About this course
Teaching approach
This course is being taught by Jeremy Howard, and was developed by Jeremy along with Rachel Thomas. Rachel has been dealing with a life-threatening illness so will not be teaching as originally planned this year.

Jeremy has worked in a number of different areas - feel free to ask about anything that he might be able to help you with at any time, even if not directly related to the current topic:

Management consultant (McKinsey; AT Kearney)
Self-funded startup entrepreneur (Fastmail: first consumer synchronized email; Optimal Decisions: first optimized insurance pricing)
VC-funded startup entrepreneur: (Kaggle; Enlitic: first deep-learning medical company)
I'll be using a top-down teaching method, which is different from how most math courses operate. Typically, in a bottom-up approach, you first learn all the separate components you will be using, and then you gradually build them up into more complex structures. The problems with this are that students often lose motivation, don't have a sense of the "big picture", and don't know what they'll need.

If you took the fast.ai deep learning course, that is what we used. You can hear more about my teaching philosophy in this blog post or in this talk.

Harvard Professor David Perkins has a book, Making Learning Whole in which he uses baseball as an analogy. We don't require kids to memorize all the rules of baseball and understand all the technical details before we let them play the game. Rather, they start playing with a just general sense of it, and then gradually learn more rules/details as time goes on.

All that to say, don't worry if you don't understand everything at first! You're not supposed to. We will start using some "black boxes" such as random forests that haven't yet been explained in detail, and then we'll dig into the lower level details later.

To start, focus on what things DO, not what they ARE.

Your practice
People learn by:

doing (coding and building)
explaining what they've learned (by writing or helping others)
Therefore, we suggest that you practice these skills on Kaggle by:

Entering competitions (doing)
Creating Kaggle kernels (explaining)
It's OK if you don't get good competition ranks or any kernel votes at first - that's totally normal! Just try to keep improving every day, and you'll see the results over time.


To get better at technical writing, study the top ranked Kaggle kernels from past competitions, and read posts from well-regarded technical bloggers. Some good role models include:

Peter Norvig - http://nbviewer.jupyter.org/url/norvig.com/ipython/ProbabilityParadox.ipynb(more here -  http://norvig.com/)
Stephen Merity - https://smerity.com/articles/2017/deepcoder_and_ai_hype.html
Julia Evans - https://codewords.recurse.com/issues/five/why-do-neural-networks-think-a-panda-is-a-vulture (more here - https://jvns.ca/blog/2014/08/12/what-happens-if-you-write-a-tcp-stack-in-python/)
Julia Ferraioli - https://www.juliaferraioli.com/blog/2016/02/exploring-world-using-vision-twilio/
Edwin Chen - http://blog.echen.me/2014/10/07/moving-beyond-ctr-better-recommendations-through-human-evaluation/
Slav Ivanov - https://blog.slavv.com/picking-an-optimizer-for-style-transfer-86e7b8cba84b (fast.ai student)
Brad Kenstler - https://hackernoon.com/non-artistic-style-transfer-or-how-to-draw-kanye-using-captain-picards-face-c4a50256b814 (fast.ai and USF MSAN student)

Books:
The more familiarity you have with numeric programming in Python, the better. If you're looking to improve in this area, we strongly suggest Wes McKinney's Python for Data Analysis, 2nd ed. - https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1491957662/ref=asap_bc?ie=UTF8

For machine learning with Python, we recommend:

Introduction to Machine Learning with Python: From one of the scikit-learn authors, which is the main library we'll be using
https://www.amazon.com/Introduction-Machine-Learning-Andreas-Mueller/dp/1449369413
Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow, 2nd Edition: New version of a very successful book. A lot of the new material however covers deep learning in Tensorflow, which isn't relevant to this course
https://www.amazon.com/Python-Machine-Learning-scikit-learn-TensorFlow/dp/1787125939/ref=dp_ob_title_bk
Hands-On Machine Learning with Scikit-Learn and TensorFlow
https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291/ref=pd_lpo_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=MBV2QMFH3EZ6B3YBY40K

Syllabus in brief
Depending on time and class interests, we'll cover something like (not necessarily in this order):

Train vs test
Effective validation set construction
Trees and ensembles
Creating random forests
Interpreting random forests
What is ML? Why do we use it?
What makes a good ML project?
Structured vs unstructured data
Examples of failures/mistakes
Feature engineering
Domain specific - dates, URLs, text
Embeddings / latent factors
Regularized models trained with SGD
GLMs, Elasticnet, etc (NB: see what James covered)
Basic neural nets
PyTorch
Broadcasting, Matrix Multiplication
Training loop, backpropagation
KNN
CV / bootstrap (Diabetes data set?)
Ethical considerations
Skip:

Dimensionality reduction
Interactions
Monitoring training
Collaborative filtering
Momentum and LR annealing
