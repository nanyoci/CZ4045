# Task 3.1
The source code can be found in SourceCode/task3-1/.

## Links to Third-party Libraries
Note: The code to install the libraries can be found in SourceCode/task3-1/domain_specific_dataset_analysis.ipynb (first few cells). So, you don't need to download them individually.

- nltk (https://www.nltk.org/install.html)
	- NLTK packages used:
		- punkt
		- wordnet
		- averaged_perceptron_tagger
- beautifulsoup4 (https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)
- pdfminer.six (https://pdfminersix.readthedocs.io/en/latest/tutorial/install.html)
- numpy (https://numpy.org/install/)
- pandas (https://pandas.pydata.org/getting_started.html)
- matplotlib (https://matplotlib.org/users/installing.html)
- seaborn (https://seaborn.pydata.org/installing.html)
- requests (https://requests.readthedocs.io/en/master/)

## How to Setup and Use Our System
Open and run SourceCode/task3-1/domain_specific_dataset_analysis.ipynb in Jupyter Notebook (https://jupyter.org/install.html) or Google Collaboratory (https://colab.research.google.com/).

## Explanations of Sample Outputs
The sample outputs can be found in the output cells in SourceCode/task3-1/domain_specific_dataset_analysis.ipynb. The output files (including images, JSON and CSVs) can be found in SourceCode/task3-1/. There is one folder for each domain and one folder (between-domains/) for comparisons between domains.

# Task 3.2 and 3.3
The source code can be found in SourceCode/task3-2&3-3/.

## Links to Third-party Libraries
- spacy (https://spacy.io/usage)
- textblob (https://textblob.readthedocs.io/en/dev/index.html)
- pandas (https://pandas.pydata.org/getting_started.html)
- matplotlib (https://matplotlib.org/users/installing.html)

## How to Setup and Use Our System
Open and run SourceCode/task3-2&3-3/NN_ADJ_Pair.ipynb in Jupyter Notebook (https://jupyter.org/install.html) or Google Collaboratory (https://colab.research.google.com/).

## Explanations of Sample Outputs
Task 3.2 and 3.3 outputs are found in the SourceCode/task3-2&3-3/output folder.
1. DependencyParseExample.svg is an example of Dependency Parsing of a sentence with spaCy.
2. noun_adj_pairs.csv contains the noun adjective pairs from approach 3 and is used for pair ranking.
3. noun_adj_pairs_has_break contains the noun adjective pairs from approach 1.
4. noun_adj_pairs_no_break contains the noun adjective pairs from approach 2.
5. plot_rate_count.png show the count of each review rating (1 to 5) out of the 30 reviews.
6. plot_sentiment.png is the sentiment polarity value of all reviews.
