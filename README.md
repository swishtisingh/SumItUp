<!DOCTYPE HTML>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div>
        <img src="sumitup.tiff" alt="Banner Image" class="banner">
    </div>

# SumItUp - Summarizing Videos in a Snap 🎥✨

Welcome to **SumItUp**, a web app designed to transform YouTube video transcripts into concise, insightful summaries. Using advanced AI capabilities powered by Google's Gemini Pro and Streamlit, SumItUp simplifies the way you consume content by summarizing key points in just a few clicks.

---

## Table of Contents 📚
- [Overview](#overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Installation and Usage](#installation-and-usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Overview 📜
With so much information available on YouTube, finding time to watch entire videos can be challenging. **SumItUp** bridges this gap by extracting transcripts from YouTube videos and generating concise summaries in bullet-point format, all within 250 words. Whether you're a student, professional, or casual viewer, SumItUp saves you time and enhances your productivity.

---

## Features 🌟
- Extracts YouTube video transcripts using **YouTube Transcript API**.
- Generates concise summaries using **Google Gemini Pro**.
- Provides point-wise, human-readable summaries for quick consumption.
- Displays the video thumbnail for a visual reference.
- User-friendly interface powered by **Streamlit**.

---

## How It Works ⚙️
1. Input the YouTube video URL.
2. The app retrieves the transcript via the **YouTube Transcript API**.
3. The transcript is processed by **Google Gemini Pro** to generate a summarized output.
4. View the detailed notes directly on the app.

---

## Technologies Used 💻
- **Python**: Core programming language.
- **Streamlit**: Frontend framework for the app interface.
- **YouTube Transcript API**: For fetching video transcripts.
- **Google Gemini Pro**: Generative AI for creating summaries.
- **dotenv**: To manage environment variables.

---

## Installation and Usage 🚀
### Prerequisites
- Python 3.7 or higher
- A valid **Google API key** with access to **Gemini Pro**

### Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/srishtisingh/SumItUp.git
    cd SumItUp
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add your **Google API key**:
     ```
     GOOGLE_API_KEY=your_google_api_key
     ```

5. **Run the application**:
    ```bash
    streamlit run app.py
    ```

6. Open the app in your browser at `http://localhost:8501`.

---

## File Structure 📂
```plaintext
.
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── LICENSE                 # License file
```

 <h2 id="license">License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>

## Author

### Srishti Singh
Data Scientist and Machine Learning Enthusiast
Feel free to connect with me on [LinkedIn.](https://www.linkedin.com/in/srishti-singh-921aa52aa/)

### Happy Coding!
