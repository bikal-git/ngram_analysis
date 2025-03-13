# Customer Support Chat N-Gram Analysis

## Overview
This project analyzes a simulated customer support chat using natural language processing (NLP) techniques. The script extracts and visualizes the most common bigrams and trigrams in the conversation, providing insights into frequently occurring phrases in customer interactions.

## Features
- Preprocesses text by removing punctuation and converting it to lowercase.
- Tokenizes customer chat messages.
- Extracts bigrams and trigrams from the conversation.
- Counts and visualizes the most frequent n-grams using bar plots.
- Provides textual output of the most common bigrams and trigrams.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install nltk matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```
2. Run the script:
   ```bash
   python script.py
   ```
3. The script will generate bar plots for the most common bigrams and trigrams in the conversation.

## Output
- **Visualizations**: Bar charts displaying the most common bigrams and trigrams.
- **Text Output**: A printed list of the most frequent bigrams and trigrams.

## Example
Sample output:
```plaintext
Most Common Bigrams: [(('order', 'id'), 2), (('new', 'order'), 2), ...]
Most Common Trigrams: [(('i', 'received', 'the'), 1), (('i', 'need', 'a'), 1), ...]
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [NLTK](https://www.nltk.org/) for text processing.
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for visualization.

## Author
[Bikal Khanal](https://github.com/your-username)

