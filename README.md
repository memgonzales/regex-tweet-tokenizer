# RegEx-Based Tweet Tokenizer
![badge][badge-jupyter]
![badge-python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white)
![badge][badge-pandas]
![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=flat&logo=Twitter&logoColor=white)

This project is a **general-purpose regular expression-based tokenizer for tweets**. In order to highlight the power and limitations of a purely regular expression-based approach, tokenization is performed by **pattern matching with a *single* regular expression**; conditional statements and substitutions are deliberately not utilized.

All the scripts are placed inside a [Jupyter notebook](https://github.com/memgonzales/regex-tweet-tokenizer/blob/master/RegEx-Based%20Tweet%20Tokenizer.ipynb), which also includes a detailed write-up covering the following:
- Definition of a token (and the underlying rationale)
- Design decisions in the implementation of the tokenizer
- Walkthrough of the implementation of the tokenizer
- Descriptive statistics of the corpus after tokenization
- Analysis of the power and limitations of the tokenizer
- Comparative analysis with the state-of-the-art [NLTK TweetTokenizer](https://www.nltk.org/api/nltk.tokenize.casual.html) 
- Performance (running time) of the tokenizer
- Analysis of the most frequent tokens

This is a major course output in an introduction to natural language processing class under Mr. Edward P. Tighe of the Department of Software Technology, De La Salle University.

## Built Using
This project is a Jupyter notebook, with the following Python libraries and modules used:

Library/Module |	Description |	License
-- | -- | --
[`pandas`](https://pandas.pydata.org/)	| Provides functions for data analysis and manipulation	| BSD 3-Clause "New" or "Revised" License
[`csv`](https://docs.python.org/3/library/csv.html)	| Implements classes to read and write tabular data in CSV format | Python Software Foundation License
[`regex`](https://pypi.org/project/regex/)	| Provides additional functionality over the standard [`re`](https://docs.python.org/3/library/re.html) module while maintaining backwards-compatibility	| Apache 2.0 License
[`nltk`](https://www.nltk.org/) (For comparative analysis of resulting tokenization)	| Provides interfaces to corpora and lexical resources, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning	| Apache License 2.0

## Author
- <b>Mark Edward M. Gonzales</b> <br/>
  mark_gonzales@dlsu.edu.ph <br/>
  gonzales.markedward@gmail.com <br/>

The [dataset of tweets](https://github.com/memgonzales/regex-tweet-tokenizer/blob/master/tweets_for_pa2.csv) was scraped by Mr. Edward P. Tighe of the Department of Software Technology, De La Salle University. All the tweets in this dataset are public tweets collected via the [Twitter API](https://developer.twitter.com/en/docs/twitter-api).

[badge-jupyter]: https://img.shields.io/badge/Jupyter-F37626.svg?&style=flat&logo=Jupyter&logoColor=white
[badge-pandas]: https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white
[badge-numpy]: https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white
[badge-scipy]: https://img.shields.io/badge/SciPy-654FF0?style=flat&logo=SciPy&logoColor=white
