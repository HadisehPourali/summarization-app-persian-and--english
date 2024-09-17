# summarization-app-persian-and-english

# Multilingual Text Summarization

This project implements a multilingual text summarization tool using Hugging Face's API and Gradio for the user interface. It supports summarization in English and Persian, with automatic language detection and a fallback model for improved reliability.

Here is the link to the app in Hugginface Spaces: https://huggingface.co/spaces/ImHadis/summarization-app

## Features

- Summarizes text in English and Persian
- Automatic language detection
- Uses specialized models for each language
- Fallback model for improved reliability
- User-friendly interface with Gradio
- Example texts provided for both languages

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6+
- A Hugging Face API key

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/multilingual-summarizer.git
   cd multilingual-summarizer
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project root and add your Hugging Face API key:
   ```
   HF_API_KEY=your_api_key_here
   ```

## Usage

To run the application:

1. Execute the Python script:
   ```
   python app.py
   ```

2. Open your web browser and go to the URL provided in the console (typically `http://127.0.0.1:7860`).

3. Enter the text you want to summarize in the input box. The app will automatically detect whether it's English or Persian.

4. Click the "Submit" button to get the summary.

## Models Used

- English: `sshleifer/distilbart-cnn-12-6`
- Persian: `csebuetnlp/mT5_multilingual_XLSum`
- Fallback: `facebook/bart-large-cnn`

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

[MIT License](https://opensource.org/licenses/MIT)

## Contact

If you have any questions or feedback, please open an issue in the GitHub repository.
