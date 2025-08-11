# ASL-Sign-Companion

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A Python-based tool for converting written English phrases into their corresponding American Sign Language (ASL) signs. This project serves as a practical guide for learners, demonstrating how to process natural language input, match it with a structured ASL sign dictionary, and display the relevant sign information, including a video demonstration.

## Features

- **Natural Language Processing:** Uses a generative AI model to parse user input and extract key words and phrases.
- **Structured Data:** Stores ASL sign information (description, media URLs) in a clean, extensible JSON format.
- **Dynamic Display:** Renders GIF-based demonstrations of ASL signs directly in the console or a Jupyter/Colab notebook.
- **Robust Parsing:** Includes advanced logic to handle various model response formats, ensuring reliable data extraction.

## Getting Started

### Prerequisites

To run this project, you will need:

-   Python 3.8 or higher
-   A Google API Key for the Gemini API
-   The Google Generative AI Python library: `pip install google-generativeai`
-   (Optional, but recommended for notebook display) IPython: `pip install ipython`

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Jamm1e/AI-ASL-Chatbot
    cd asl-sign-chatbot
    ```

2.  **Set up your environment:**
    Create a `.env` file in the project's root directory to store your API key securely:

    ```ini
    GOOGLE_API_KEY="YOUR_API_KEY"
    ```

    You can get a free API key from the [Google AI Studio](https://aistudio.google.com/app/apikey).

3.  **Place your data file:**
    Ensure your `asl_signs.json` file (containing your ASL sign data) is in the root directory.
