# Text-To-Music-Generator
Text to Music Generation App
Description
This application is a Text to Music Generator built using Meta's Audiocraft library. It leverages the Music Gen small model to generate music based on user-provided text prompts. The app is built with Streamlit, providing an interactive web interface for users to generate and listen to music.

Features
Generate music from text prompts.
Utilizes Meta's Music Gen small model for high-quality music generation.
Interactive web interface built with Streamlit.
Option to download the generated music.
Installation
Prerequisites
Python 3.x
Streamlit
Meta's Audiocraft library
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/shalatjohnson/text-to-music-generation.git
Navigate to the project directory:

bash
Copy code
cd text-to-music-generation
Install the required dependencies:

bash
Copy code
pip install streamlit
pip install audiocraft
(Optional) If you need to install any additional dependencies specific to the Music Gen model or other parts of the app, follow the instructions in the Audiocraft documentation.

Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Open the URL provided by Streamlit (usually http://localhost:8501) in your web browser.

Enter a text prompt in the provided input field and click "Generate Music" to create a music piece based on your prompt.

Listen to the generated music and use the download option if available.

Project Structure
app.py: Main Streamlit application script.
README.md: This file with project details and instructions.


Acknowledgements
Meta's Audiocraft library for music generation capabilities.
Streamlit for providing an easy-to-use web interface.


