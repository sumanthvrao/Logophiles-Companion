# Logophiles-Companion
### A Customized Vocabulary Assistant


[![Python 3](https://img.shields.io/badge/python-3-blue.svg)](https://www.python.org/download/releases/3.0/)
[![Tkinter](https://img.shields.io/badge/tkinter-interface-green.svg)](https://docs.python.org/2/library/tkinter.html)

Code Repository: <a target="_blank" href="https://github.com/sumanthvrao/Logophiles-Companion" rel="noreferrer noopener">https://github.com/sumanthvrao/Logophiles-Companion</a>

*Logophiles Companion* is a Vocabulary Learning assistant which annotates non-trivial words (medium to hard words) with their corresponding definitions, as it occurs in a video. At the very core, it uses an Artificial Neural Network which classifies words based on the complexity, and Wordnet to fetch a semantically similar, simple word. This serves two purposes:

1. The user can understand the conversation better, without having to pause the video and look up the meaning.
2. Since we show both the word and the meaning (in the subtitles) the user can learn its meaning and improve their vocabulary.

Further, the neural net adjusts its weights over time to factor in the users improved vocabulary, and annotate the words accordingly.


## Tech Stack
 * Python Scikit-learn library
 * Python NTLK library
 * Python Tkinter GUI toolkit

## Downloading and Installing

1. Clone the code repositories
2. Run `dragdropinterface.py`.
3. Drop subtitle file into the window which has popped up.
4. The old subtitle file has been replaced by our ANN model.
5. Add it as subtitle file to the video player of your choice.

## Team
* Sumanth V Rao
* Suraj Aralihalli
* Tanmaya Udupa