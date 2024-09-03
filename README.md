# Smart Similar Generator

Have you ever searched for the wrong word and wished you could find results for what you actually intended to search for? The Smart Similar Generator addresses this problem by using advanced algorithms to find suitable synonyms and similar words.

## Overview

The Smart Similar Generator uses text-mining and natural language processing (NLP) techniques to generate synonyms and similar words for product names. This tool enhances search functionality and improves user experience by suggesting relevant terms based on the input.

## Features

- **Generate Synonyms and Similar Words**: Automatically find synonyms and similar terms for both English and Persian words.
- **Excel Integration**: Read input words from an Excel file (`Input_words.xlsx`) and write the generated synonyms and similar terms to a new Excel file (`synonyms_similars.xlsx`).

## How It Works

1. **Input Processing**: Reads product names from an Excel file.
2. **Synonym Generation**: Utilizes NLP tools to generate synonyms and similar words.
3. **Output**: Saves the results in a new Excel file for easy access and further use.

## Technologies Used

- **Gensim**: Used for generating synonyms and similar words for English terms. Gensim leverages the Word2Vec technique for NLP. Learn more about [Word2Vec](https://en.wikipedia.org/wiki/Word2vec) and [Gensim](https://en.wikipedia.org/wiki/Gensim).

- **text-mining.ir**: An API used for processing Persian text, providing tools for generating synonyms and similar terms. For more information, visit [text-mining.ir](https://text-mining.ir/).

- **itertools**: A Python library for creating iterators for efficient looping. Learn more about [itertools](https://docs.python.org/3/library/itertools.html).

- **Levenshtein**: A library used for measuring orthographic similarity between two words. Read more about [Levenshtein](https://pypi.org/project/python-Levenshtein/).

- **spaCy**: A library for tokenizing product names, helping to break text into manageable units. Learn more about [spaCy](https://en.wikipedia.org/wiki/SpaCy).


## Usage

1. **Prepare Your Data**: Create an Excel file named `Input_words.xlsx` with a list of words or product names.
2. **Run the Script**: Execute the script to process the input file and generate synonyms and similar words.
3. **Check the Results**: The results will be saved in a new Excel file named `synonyms_similars.xlsx`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Additional Resources

- [Word2Vec](https://en.wikipedia.org/wiki/Word2vec): Learn more about the Word2Vec technique used in NLP.
- [Gensim](https://en.wikipedia.org/wiki/Gensim): Read about the Gensim library for topic modeling and document similarity.
- [text-mining.ir](https://text-mining.ir/): Explore the API used for processing Persian text.
- [itertools](https://docs.python.org/3/library/itertools.html): Documentation for the Python library used for efficient looping.
- [Levenshtein](https://pypi.org/project/python-Levenshtein/): Information about the library for measuring orthographic similarity.
- [spaCy](https://en.wikipedia.org/wiki/SpaCy): Details about the spaCy library for tokenization and NLP.
