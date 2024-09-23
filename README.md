# TV-Series-AI-Analysis

This project demonstrates how to analyze your favorite TV series using Artificial Intelligence (AI), Large Language Models (LLMs), and Natural Language Processing (NLP). It includes data scraping, theme extraction, character network creation, text classification, and chatbot development to simulate character conversations.

## Features
- **Data Scraping:** Gather and scrape data from the web using Scrapy.
- **Zero-shot Classification:** Identify main themes using Hugging Face's Transformers.
- **Named Entity Recognition (NER):** Extract character names and entities with Spacy.
- **Character Network:** Visualize character relationships using NetworkX and Pyviz.
- **Text Classification:** Train a custom text classifier using Transformers.
- **Chatbot Creation:** Build a chatbot to imitate your favorite characters.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/TV-Series-AI-Analysis.git
    cd TV-Series-AI-Analysis
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Data Scraping:**
   - Use Scrapy to gather data from websites. Customize the spider in the `scrapy_spider.py` file.

2. **Theme Extraction:**
   - Use Hugging Face and Transformers to implement zero-shot classification for identifying the main themes.

3. **Character Network:**
   - Build and visualize a character network with NER models using Spacy, NetworkX, and Pyviz.

4. **Text Classification:**
   - Train a custom text classifier on a dataset of your choice using Hugging Face and Transformers.

5. **Character Chatbot:**
   - Build a chatbot to simulate conversations with your favorite TV series characters.

## Libraries Used
- [Scrapy](https://scrapy.org/)
- [Hugging Face](https://huggingface.co/)
- [Transformers](https://huggingface.co/transformers/)
- [Spacy](https://spacy.io/)
- [NetworkX](https://networkx.org/)
- [Pyviz](http://pyviz.org/)

## Contributing

Feel free to submit pull requests to improve this project or add new features!

## License

This project is licensed under the MIT License.
