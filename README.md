# puntender
An experiment in computational humor comprehension using WordNet and ConceptNet, on the joke structure, "____ walks into a bar. The barman says, '_____'".

There are two main programs: one which analyzes the joke via [WordNet](https://wordnet.princeton.edu/) and another which uses [ConceptNet](http://conceptnet.io/). Both of these programs run using `python3`. If you do not have python3 installed, please follow one of these tutorials: [https://docs.python-guide.org/starting/installation/#python-3-installation-guides](https://docs.python-guide.org/starting/installation/#python-3-installation-guides)

Before running the programs, you should run the following command in the terminal to install the necessary modules and download the needed nltk packages. The jokes to be analyzed should be placed in the `jokes.txt` file, one on each line.
```bash
python3 setup.py
```
To run the WordNet analyzer, run
```bash
python3 wordnet_main.py
```
To run the ConceptNet analyzer, run
```bash
python3 conceptnet_main.py
```
