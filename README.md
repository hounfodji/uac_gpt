# UAC Chatbot

## Description
UAC Chatbot is an intelligent conversational agent designed for the University of Abomey-Calavi (UAC). It uses advanced natural language processing and information retrieval techniques to provide accurate and relevant information about the university.

## Features
- Web scraping of UAC website for up-to-date information
- Natural language processing using Google's Gemini model
- Efficient document retrieval using Qdrant vector database
- Context-aware responses with Cohere's reranking system

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/uac-chatbot.git
   cd uac-chatbot
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Download the SpaCy French language model:
   ```
   python -m spacy download fr_core_news_sm
   ```

## Usage

1. Set up your environment variables:
   ```
   export GOOGLE_API_KEY="your_google_api_key"
   export COHERE_API_KEY="your_cohere_api_key"
   ```

2. Run the Jupyter notebook:
   ```
   jupyter notebook UAC_Chatbot.ipynb
   ```

3. Follow the instructions in the notebook to initialize and interact with the chatbot.

## Contributing
Contributions to improve UAC Chatbot are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- University of Abomey-Calavi for providing the information
- Google's Gemini model for natural language processing
- Cohere for embeddings and reranking capabilities
- Qdrant for vector storage and retrieval

## Contact
Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/yourusername/uac-chatbot](https://github.com/yourusername/uac-chatbot)