*
* Kevin Mu, Jonathan Miller, Stella Pantela, and Dianna Hu
* CS187 - Computational Lingustics
* Final Project (TextTiling) - Group Implementation
* README
*

---- -- - - - - -  -   -
Setup Instructions
---- -- - - - - -  -   -
0) If nltk is already installed, skip to step 5.

1) Run "python ez_setup.py"
2) Run (sudo) "easy_install pip"
3) Run (sudo) "pip install -U nltk"
4) Run "python", then type "import nltk"
5) Type "nltk.download()". A new window should open,
   showing the nltk Downloader.
6) Click the "corpora" tab.
7) Select "Stopwords Corpus" (stopwords) 
   and "WordNet" (wordnet), and click Download.
8) Close the nltk downloader and exit python.


---- -- - - - - -  -   -
Running Instructions
---- -- - - - - -  -   -
1) cd into the project directory
2) Run python "mu_project_part1.py <infile> <tokens_outfile> <scores_outfile>"
    a) The infile is the file containing the original text
    b) The tokens_outfile is the file where you want the tokenized 
       pseudo-sentences to be written.
    c) The scores_outfile is the file where you want the computed 
       block similarity scores to be written.

    e.g., mu_project_party1.py infile.txt, tokens.txt, scores.txt


---- -- - - - - -  -   -
Implementation of the Texttiling Algorithm
---- -- - - - - -  -   -
We decided to split our work so that we all have an clear idea of how 
to specifically implement one of the parts above while looking at the 
rest as well. 
