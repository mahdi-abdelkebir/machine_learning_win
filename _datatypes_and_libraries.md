

The libraries we have to use changes with the type data we're dealing with.
The most common datatypes are: images, text, tabular data.

# Text (NLP, Natural Language Processing):

## Usage:

Located at the intersection of data science and Artificial Intelligence (AI), this field is all about teaching machines how to understand human languages and extract meaning from text.

There’s a reason why tech giants like Google, Amazon, or Facebook are pouring millions of dollars into this line of research to power their chatbots, virtual assistants, recommendation engines, and other solutions powered by machine learning.

In the past, only experts could be part of natural language processing projects that required superior knowledge of mathematics, machine learning, and linguistics. Now, developers can use ready-made tools that simplify text preprocessing so that they can concentrate on building machine learning models.

Related tasks are document classification, topic modeling, part-of-speech (POS) tagging, word vectors, and sentiment analysis.

## Technical Terms: 

- Computational Linguistics: A branch of linguistics in which the techniques of computer science are applied to the analysis and synthesis of language and speech. A computational linguist researches, creates, and maintains models that help technology better process human language, in order to help computers follow human commands to a greater degree.

- Text corpora: A language resource consisting of a large and unstructured set of texts. Many corpora are designed to contain a careful balance of material in one or more genres.

## Libraires:

### NLTK (Natural Language Toolkit, Beginners): 

- Pros: Provides a practical introduction to programming for language processing, coming along with a suit of text processing libraries such as classification, tokenization, stemming, tagging, parsing, semantic reasoning. 
    
- Cons: Difficult to use and incredibly slow to meet the demands of NLP Python production usage.

### TextBlob (Beginners): 

- Pros: Helps in learning the most basic NLP tasks like sentiment analysis, pos-tagging, or noun phrase extraction. It's said that it's very helpful in designing prototypes.

- Cons: As slow as NLTK in production usage.

### CoreNLP: 

Developed at Stanford University and written in Java. It’s equipped with wrappers for many different languages, including Python.

- Pros: The library is really fast and works well in product development environments,. Moreover, some of CoreNLP components can be integrated with NLTK which is bound to boost the efficiency of the latter.

- Cons: Lack of customization options.

### Gensim:

- Pros: Supports primarily unsupervised text modeling, it can handle large text corpora and famed for its incredible memory usage optimization and processing speed, thanks to NumPy, and specializes in identifying semantic similarity between two documents. The tool's vector space modeling capabilities are also top notch.

- Cons: Cannot be used on its own.

### spaCy (Advanced): 

- Pros: Designed for production and offers the fastest syntactic parser available on the market today. Moreover, since the toolkit is written in Cython, it’s also really speedy and efficient. Morever, due to growing popularity of machine learning, spaCy as a key library means that the tool might start supporting more programming languages soon.

- Cons: Still a young library, unflexible and supports only 7 languages, however, due to growing popularity of machine learning, spaCy as a key library means that the tool might start supporting more programming languages too.

### Pattern: 

- Pros: Essentially a web miner and includes a DOM parser, a web crawler, as well as some useful APIs like Twitter or Facebook. It allows part-of-speech tagging, sentiment analysis, vector space modeling, SVM, clustering, n-gram search, and WordNet. 

- Cons: Only capable web mining tasks and unable to complete the more sophisticated NLP tasks, so it can only be an add-on.

### Scikit-learn: 

- Pros: Specialises in building machine learning models, offering developers a wide range of algorithms to build their models. It offers many functions for using the bag-of-words method of creating features to tackle text classification problems. The strength of this library is the intuitive classes methods. In addition, it has an excellent documentation that helps developers make the most of its features.

- Cons: Doesn't use neural networks for text preprocessing which means it cannot carry out more complex preprocessing tasks like POS tagging for your text corpora.



# Images (Image Processing):

## Usage:

A huge part of data is images. Data scientists need to (pre) process these images before feeding them into any machine learning models.

Image processing is the process of transforming images into digital forms before performing special operations on them, which yields valuable information. 

Once a business decides to utilize image processing, there are many potential applications. For example, image processing is often used in medical research and to develop accurate treatment plans. It can also be used to recover and reconstruct corrupt parts of an image, or to carry out face detection.


## Few Main Types: 

- Visualization: Objects not visible in the image are detected.

- Recognition: Detect objects present in the image.

- Sharpening and Restoration: Original images are enhanced.

- Pattern Recognition: The patterns in the image are measured.

- Retrieval: Find images that are similar to the original by searching a large database.


## Libraries:

### OpenCV: 

Developed by Intel in the year 2000, and used in many major companies like Google and Toyota, it's an open-source C++ library that also comes with a Python wrapper and can be used alongside NumPy, SciPy, and Matplotlib.

It's mostly used in computer vision tasks such as object detection, face detection, face recognition, image segmentation, etc. Morever, it contains a lot of other interesting functions that you may need in ML.

One of the best aspects of this library is that its constantly evolving thanks to its many contributors on Github, currently containing over 2,500 state-of-the-art and classic algorithms.

### Scikit-Image:

A free open-source library with minimum legal and licensing restrictions. 

This library is partly written in Cython, which is a programming language that is a superset of Python. This unique structure helps it achieve good performance. 

Scikit-Image, uses NumPy arrays as image objects, and offers many different algorithms for segmentation, color space manipulation, geometric transformation, analysis, morphology, feature detection, and much more. Could be used in real-world applications like consumer behavior prediction.

### SciPy (Advanced):

Originally designed for mathematical and scientific computations, SciPy is also a top open-source library for performing multi-dimensional image processing by importing the submodule scipy.ndimage. SciPy provides functions to operate on n-dimensional Numpy arrays. 

One of the main highlights of SciPy is that it provides access to high-level commands and classes for visualizing and manipulating data.

### Matplotlib (Beginner):

Simple and easy to use, this library is also open-source, usually used for 2D visualizations like scatter plots, histograms, and bar graphs, but it has proven to be useful for image processing by effectively pulling information out of an image. 

It's highly customizable and provides high-quality images and plots in various formats. However, it’s important to note that Matplotlib doesn’t support all file formats.

