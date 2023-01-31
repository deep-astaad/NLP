# Natural language Processing
#### Lab Assignments based on the NLP Theory

Natural Language Processing (NLP) is the computerized approach to analyzing text that is based on both a set of theories and a set of technologies. And, being a very active area of research and development, there is not a single agreed-upon definition that would satisfy everyone, but there are some aspects, which would be part of any knowledgeable person’s definition. The definition I offer is: 

- Total 5 Labs
- Implemented in Python
- ✨Used NLTK, spaCy, pandas, numpy, tkinter libraries to make it simple✨ 

## Summary

- Generats morpheme (root word) of given word
- Analyse Morphological form  of given word
- Generates different forms of the given word
- Implementation of N-Grams model
- POS tagging using HMM and Viterbi Algorithm

### Lab 1
The objective of the experiment is to learn about morphological features of a word by
analysing it.
Analysis of a word into root and affix(es) is called as Morphological analysis of a word.
It is mandatory to identify root of a word for any natural language processing task.

### Lab 2 
A word can be simple or complex. For example, the word 'cat' is simple because one
cannot further decompose the word into smaller part. On the other hand, the word
'cats' is complex, because the word is made up of two parts: root 'cat' and plural suffix '-s'

The objective of the experiment is to generate word forms from root and suffix
information.

### Lab 3
Morphology is the study of the way words are built up from smaller meaning bearing
units i.e., morphemes. A morpheme is the smallest meaningful linguistic unit.
These morphemes can either be a root word(play) or affix(-ed).
Combination of these morphemes is called morphological process.

### Lab 4
N-grams are continuous sequences of words or symbols or tokens in a document. In technical terms, they can be defined as the neighbouring sequences of items in a document. They come into play when we deal with text data in NLP(Natural Language Processing) tasks.
Calculated the probabilities of the given sentence (N Gram)

### Lab 5
The purpose of the Viterbi algorithm is to make an inference based on a trained model and some observed data.
Calculated State Transition Probability Matrix, Emission Probability Matrix
and applied Viterbi algorithm for POS tagging

## Tech

python libraries and word-banks that are used :

- [NLTK] - NLTK is a leading platform for building Python programs to work with human language data.
- [spaCy] - spaCy is designed specifically for production use and helps you build applications that process and “understand” large volumes of text
- [tkinter] - The tkinter package (“Tk interface”) is the standard Python interface to the Tcl/Tk GUI toolkit.
- [pyinflect] - A python module for word inflections that works as a spaCy extension.
- [pandas] - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language.
- [numpy] - NumPy offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.


## Installation

Requires [Python](https://www.python.org/) (latest version) to run.

Install the libraries required to run the code.


For spaCy...
```sh
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
```

For pandas...

```sh
pip install pandas
pip3 install pandas
```

For tkinter...

```sh
pip install tk
```

For inflect...

```sh
pip install inflect
```

For numpy...
```sh
pip install numpy
```
