# Text Summarizer with Hugging Face Models and Flask

## Overview

Welcome to the Text Summarizer project! This application utilizes the power of Hugging Face Models to generate concise summaries of inputted text. The graphical user interface (GUI) is built using Flask, providing an easy and interactive way to summarize text.

## Features

- **Summarize Text**: Enter your text in the provided area and click the "Summarize" button to generate a summary.
- **Adjustable Summary Length**: Customize the length of the generated summary using a range slider.
- **Copy to Clipboard**: Easily copy the generated summary to the clipboard with the click of a button.
- **Clear Input**: Reset the input area to start afresh.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- Requests

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Run the Flask app:

```bash
flask run
```

2. Open your web browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000).

3. Enter your text, adjust the summary length, and click "Summarize" to generate a summary.

## GUI Customization

The GUI has been designed for a user-friendly experience. However, feel free to customize it further according to your preferences. You can modify the HTML and CSS files in the `templates` and `static` directories, respectively.

### Dark Theme

To change the theme to dark mode, modify the CSS in the `static/css/style.css` file. For example:

```css
body {
    background-color: #121212; /* Dark background color */
    color: #ffffff; /* White text color */
    /* Add any additional styling for dark mode */
}

/* Customize as needed */
```

## Credits

This project is made possible by the following technologies:

- [Hugging Face Models](https://huggingface.co/models)
- [Flask](https://flask.palletsprojects.com/)
- [Tailwind CSS](https://tailwindcss.com/)

## License

This project is licensed under the [MIT License](LICENSE).
