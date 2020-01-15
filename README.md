
## Data Science / Machine Learning Interview Questions

* Feel free to add more questions.
* Give a **star** and **fork** it if you find it helpful

Questions that were asked to me while interviewing for DS/ML internships. These questions are divided into various sections and are in no particular order. After going through so many interviews the advice I'd like to give is don't just focus on learning the techniques but understand them in depth and also their application in real world because these aspects are focus more during interview.

### Feature Engineering

* What is one hot encoding and why do we need it?
* How will you detect skewness in data and how to correct that?
* What are outliers? How to detect and remove them?
* Why do we need dimensionality reduction. 
* How do you deal with imbalanced datasets.
* A sample dataset will be given and you'll be asked what new features can you generate and how will they be helpful. 

### Feature Selection

* Why use Correlation? Which correlation method to use for continuous and categorical features?

### ML Models and Neural Networks

* What assumptions are made when using Linear Regression?
* What is Lasso and Ridge regression?
* What parameters will you tune in gradient boosted trees if you face a certain condition?
* Describe SVM. What are support vectors in SVM? What is the use of Kernels in SVM?
* Why do we need activation function, various activation functions and their output range?
* Different ways of stacking `n` regression models.
* Overfitting/Underfitting or Bias/Variance. Methods to deal with both.
* L1, L2 and Dropout Regularization
* Various Optimizers that you know about. What is special about them?
* How Grid Search and K Fold Cross Validation works? Why they are used?

### Metrics

* How will you measure accuracy of a regression model?
* What is Precision and Recall and when will you use which? Explain with example.
* What are the x and y axis of ROC curve? What does a line with angle 45* represent on ROC curve? Where will the line move if we make certain changes?
* Why F1 score is the Harmonic mean and not Arithmetic mean.
* Similarity metrics and their used cases. Why cosine similarity is preferred in NLP.

### Computer Vision

* What methods do you know of object detection? Brief explanation of how they work. Which would you use when.
* How would you solve a certain problem without any ML model (in my case I had trained a CNN to detect the numbers from hand gestures, so I was asked to solve it without any ML model)
* Difference b/w the famous CNN architectures such as VGG, ResNet, Inception.
* Which initialization techniques (Random, Xavier, He) do you know? Which activation function would you use with a certain initialization.
* Siamese Network, Triplet Loss. How to scale face recognition model.

### Natural Language Processing

* What problems does RNN solve.
* Word Embeddings and why we need them. I was given 4 choices and had to tell which relation would be easiest and hardest to pick using word embeddings:
	* king-man+woman=queen
	* 1+4-3=2
	* NaOH + HCl = NaCl + H2O
	* Can't remember the 4th option 😅
* Basic working of LSTMs and GRU (no one has gone in-depth on this topic just the overview).
* How FastText embeddings are trained, what problems does it solve?
* Count Vectorizer and TF-IDF.
* I was asked about Named Entity Recognition, not directly but through a practical problem statement.
* Brief description of Attention mechanism, its advantages and Local and Global Attention.

### Scalability

* How will you work on data with lots of features (say 10,000). Describe your steps.
* How will you handle categorical values with high cardinality / many unique values (such as zip codes, product ids etc.) 

### Unsupervised Learning

* Various types of clustering, their performance and used cases.
* PCA and LDA

### Frameworks

* 2 ways you can build models in TensorFlow/Keras.
* Shallow and Deep copy
* What does `.fit()` and `.transform()` functions do in Scikit Learn's estimators.

### Topics that has not been asked yet

* Interpretability in ML models
* Deployment of models
* GANs

### Miscellaneous

* Most of the companies send out some task to complete and discuss about your approaches on that task. So read about the methods and frameworks that you use in depth.
* Some companies also do live coding rounds. They can give you Algo/DS questions to code or they might also give you a simple dataset and ask you to write `pandas` queries for the given questions.
* Some companies call you for the interview without any notice so be prepared to give the interview at all times.
* They will also discuss about the projects that you have mentioned on your resume, so have a look at them and **don't lie**. Sometimes they also give you a choice to talk about a project that you are most confident about.
* Some people also ask questions from computer science subjects such as OS, Networking, Database (SQL queries) and Web development.
