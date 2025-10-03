# CardmakerV2

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/Flask-2.x-black.svg)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A Flask-based web application that creates custom greeting cards by removing image backgrounds and adding personalized text overlays.

## ✨ Features

-   **Background Removal**: Automatically removes backgrounds from uploaded images using `rembg`.
-   **Custom Text**: Add wishes and name text with customizable font sizes.
-   **Random Styling**: Applies random colors and effects to text for visual variety.
-   **Responsive Design**: Works seamlessly on both desktop and mobile devices.
-   **Dark Theme**: Modern dark UI with smooth animations and a clean aesthetic.

## 🚀 Getting Started

Follow these instructions to get a local copy up and running.

### Prerequisites

-   Python 3.7+
-   pip (Python package installer)

### Installation & Setup

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/hemanthanala1/cardmaker.git](https://github.com/hemanthanala1/cardmaker.git)
    cd cardmaker
    ```

2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Application**:
    ```bash
    python app.py
    ```

4.  **Access the App**:
    Open your web browser and navigate to `http://localhost:5000`.

## 📝 How to Use

1.  **Upload an Image**: Choose a JPG, PNG, or other supported image file.
2.  **Enter Wishes**: Type your main message (e.g., "Happy Birthday").
3.  **Enter Name**: Add the recipient's name.
4.  **Adjust Fonts**: Use the sliders to control the font sizes for both text lines.
5.  **Choose Layout**: Select a single or double-line layout for your text.
6.  **Generate**: Click the **"Generate Card"** button to create your custom card.
7.  **Download**: Save the final image as a JPG file.

## 🛠️ Technical Details

-   **Backend**: Flask
-   **Background Removal**: `rembg` library
-   **Image Processing**: `Pillow` (PIL Fork) for text overlays and image manipulation.
-   **Frontend**: Vanilla JavaScript, HTML5, and Modern CSS.
-   **Font**: `Anton Regular` (included in the repository).

## 📁 File Structure

```plaintext
CardmakerV2/
├── app.py              # Flask backend logic
├── requirements.txt      # Project dependencies
├── Anton-Regular.ttf     # Custom font file
├── static/
│   ├── style.css         # Styling for the application
│   └── script.js         # Frontend JavaScript logic
└── templates/
    └── index.html        # Main UI template
