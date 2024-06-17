# Personal AI Assistant

Welcome to the Personal AI Assistant project! This Python-based application serves as a multi-lingual supportive chatbot capable of answering queries, playing songs, providing weather and news updates, and even generating code snippets. It accepts commands via both text and voice input, supporting multiple languages using Google Translate (via the `googletrans` library).

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Personal AI Assistant is designed to enhance user interaction through natural language processing. It leverages technologies such as Gemini for answering queries and integrates with various APIs for fetching weather updates, news feeds, and music streaming. The assistant supports voice commands using speech recognition, making it accessible and convenient for users to interact regardless of their language preference.

## Features

- **Multi-lingual Support**: Translate and respond in multiple languages using Google Translate (`googletrans`).
- **Query Answering**: Utilizes Gemini to answer a wide range of questions.
- **Video Player**: Plays songs based on user requests.
- **Weather Updates**: Fetches real-time weather information.
- **News Updates**: Provides current news headlines and summaries.
- **Code Snippets**: Generates code snippets for programming queries.
- **Voice Recognition**: Accepts commands via voice input, enabling hands-free interaction.

## Technologies Used

- **Python Modules**:
  - **Streamlit**: Web application framework for interactive data visualization.
  - **Google Translate API**: Integrated via `googletrans` for multi-lingual support.
  - **SpeechRecognition**: Library for performing speech recognition with support for multiple engines.
  - **Gemini**: AI-based service for answering general knowledge questions.
  - **Requests**: HTTP library for making API requests.
  
## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/personal-ai-assistant.git
   cd personal-ai-assistant
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   streamlit run app.py
   ```

5. **Open your browser and navigate to:**

   ```plaintext
   http://localhost:8501
   ```

## Usage

1. Open the application in your web browser after running `streamlit run app.py`.
2. Use the text input or voice recognition button to interact with the assistant.
3. Ask questions, request weather updates, play music, or request code snippets.
4. Enjoy seamless interaction with the assistant across multiple languages!

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request for any improvements or new features you'd like to add.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
