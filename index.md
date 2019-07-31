# Creative Writing with Computation and Machine Learning

Anderson Ranch Summer 2019

Instructor: [Allison Parrish](http://www.decontextualize.com/)

Computational tools and statistical analysis are often deployed as a method to “read” texts. But what about using these same techniques to write them? In this workshop, students use techniques from natural language processing to tear language at its digital seams and lovingly re-articulate it with computer programming—like postmodern Frankenstein-poets. Through a series of pre-written (but easily modifiable) programs, students are introduced to text analysis and language generation with the Python programming language. Students make automated “big Dada” cut-ups, undertake poor digital humanities based on word counts and part-of-speech tagging and exploit vector arithmetic to write poetry.

In addition to reading and workshopping the work we make in class, we will publish a small class zine! Students will submit 1–3 finished pieces, which we'll assemble into a publication on the last day of the workshop.

## Requirements

You'll need to bring a laptop with you. Please install [Anaconda](https://www.anaconda.com/download/) (Python 3.7+, 64-bit) on your computer before the first session.

## Schedule

### Session 01

* Course overview and introductions
* Activity: Invent digital text from scratch
* [Jupyter Notebook basics](https://github.com/aparrish/rwet/blob/master/jupyter-notebook-tutorial.ipynb)
* Python introduction
* [Remixing classic poetry generators](https://github.com/aparrish/rwet/blob/master/some-poetry-generators.ipynb)

Assignment: Many well-known poetry generators, especially those from the beginning of the computational era, work by drawing randomly from a limited vocabulary of strings and composing those strings using straightforward string manipulation techniques. Create your own poetry generator using these techniques. Use one of the generators implemented in the "Some poetry generators" notebook as a starting point for your creation. Don’t be afraid to break things.

### Session 02

* Reading and workshop from session 1
* Difficult texts in performance
* Composing text with grammars: [Tracery tutorial](http://air.decontextualize.com/tracery/), [Tracery in Python](https://github.com/aparrish/rwet/blob/master/tracery-and-python.ipynb) (supplementary: [Tracery and data](https://gist.github.com/aparrish/73c19a36b9cdcf604d04e95020418cd4), [Tracery advanced techniques](http://catn.decontextualize.com/public/notebooks/propp-inspired-tracery.html))
* Afternoon excursion: Building a corpus

Assignment: Use Tracery in Jupyter Notebook to create a text generator that mimics an existing genre of text.

### Session 03

* Reading and workshop from session 02
* A history of automatic writing
* Python: [Predictive text and text generation](https://github.com/aparrish/predictive-text-and-text-generation/blob/master/predictive-text-and-text-generation.ipynb)
* Using Runway to caption photos and generate text from GPT-2

Assignment: Use predictive models to generate text: either a Markov chain or an RNN, or both. How does your choice of source text affect the output? Try combining predictive text with other methods we’ve used for analyzing and generating text: use RNN-generated text to fill Tracery templates, or train a Markov model on the output of parsing parts of speech from a text, or some other combination. What works and what doesn’t? How does RNN-generated text “feel” different from Markov-generated text? How does the length of the n-gram and the unit of the n-gram affect the quality of the output?

### Session 04

* Reading and workshop from session 3
* [A Reasonable Introduction to Natural Language Processing & the Vectorized Word](https://gist.github.com/aparrish/697b7f56ac28f4e59af77a66ac573b8f)
* [Introduction to word vectors](https://github.com/aparrish/rwet/blob/master/understanding-word-vectors.ipynb) ([Binder version](https://mybinder.org/v2/gh/aparrish/rwet/master?filepath=understanding-word-vectors.ipynb))

Assignment: Use the parts of text that you extracted with spaCy to make a composition, and/or use semantic similarity to cut-up/remix a text.

### Session 05

* Reading a workshop from session 4
* Zine preparation