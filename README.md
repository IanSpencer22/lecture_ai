# Lecture AI Generator

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-API-green)

Lecture AI Generator is a Python-based application that allows users to upload various types of files (videos, text, PDFs, PowerPoint presentations) and interact with an AI to ask questions based on the uploaded content. The AI uses OpenAI's GPT-4o model to generate responses.

## Features

- **Transcribe Videos**: Convert video files to text using speech recognition.
- **Read Text Files**: Load and read plain text files.
- **Read PDF Files**: Extract text from PDF documents.
- **Read PowerPoint Files**: Extract text from PowerPoint presentations.
- **Analyze Content**: Tokenize and analyze the text content.
- **AI Interaction**: Ask questions based on the uploaded content and get responses from OpenAI's GPT-4o model.
- **User-Friendly GUI**: Simple and intuitive graphical user interface built with Tkinter.

## Installation

### Prerequisites

- Python 3.8+
- OpenAI API Key
- Required Python packages (listed in `requirements.txt`)

### Setup

1. **Clone the Repository**

    ```sh
    git clone https://github.com/IanSpencer22/lecture_ai_generator.git
    cd lecture_ai_generator
    ```

2. **Create a Virtual Environment (optional)**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**

    Create a `.env` file in the root directory and add your OpenAI API key:

    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```

## Usage

1. **Run the Application**

    ```sh
    python lecture_ai_generator.py
    ```

2. **Upload a File**

    - Click on the "Upload File" button.
    - Select a file from your system (supported formats: `.mp4`, `.mkv`, `.avi`, `.txt`, `.pdf`, `.pptx`).

3. **Interact with the AI**

    - Type your question in the input field and click "Send".
    - The AI will respond based on the uploaded content.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://www.openai.com/) for the GPT-4o model.
- [Tkinter](https://docs.python.org/3/library/tkinter.html) for the GUI framework.
- [MoviePy](https://zulko.github.io/moviepy/) for video processing.
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) for audio transcription.
- [PyPDF2](https://pypi.org/project/PyPDF2/) for PDF text extraction.
- [python-pptx](https://python-pptx.readthedocs.io/en/latest/) for PowerPoint text extraction.

---

Feel free to customize this `README.md` to better fit your project's needs!