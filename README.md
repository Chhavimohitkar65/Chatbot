# 🌟 Aawaz: Indian Railways Information Hub ChatBot🚆

Welcome to **Aawaz**, a Streamlit web application designed to provide essential information related to Indian Railways. With features like PNR status checking, live train status updates, and language translation, Aawaz aims to enhance user experience and accessibility.

## Features ✨

- **🌍 Language Selection**: Choose from Marathi, English, Tamil, and Hindi for an immersive experience.
- **📅 PNR Status**: Enter your PNR number to check the current status of your train journey.
- **🚨 Live Train Status**: Get real-time updates on any train by entering its train number.
- **🚉 Trains Between Stations**: Find trains operating between two specified stations on a selected date.
- **🔊 Recent Announcement**: Listen to recent announcements in your preferred language.
- **❓ Ask Anything**: Pose questions related to Indian Railways and receive answers powered by ChatGPT.
- **🎤 Text-to-Speech Functionality**: Enjoy voice-based announcements for a more interactive experience.

## Technologies Used ⚙️

- **Streamlit**: For building the web application.
- **Google Translate**: For language translation of user inputs and API responses.
- **Pydub**: For audio playback of announcements.
- **RapidAPI**: For accessing APIs to fetch PNR status and live train information.
- **Python**: Core programming language used for development.

## Getting Started 🚀

### Prerequisites 📋

Make sure you have the following installed:

- Python 3.x
- Streamlit
- Googletrans
- Requests
- Pydub
- A valid RapidAPI key for the APIs used in the project.

### Installation 🛠️

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Chhavimohitkar65/Aawaz.git
2. Navigate to the project directory:
   ```bash
   cd Aawaz

3. Install the required packages:
   ```bash
   pip install streamlit googletrans requests pydub

4. Set up your audio files in a designated folder (e.g., static) as needed.

5. Replace the RAPIDAPI_KEY variable in the code with your own RapidAPI key.

## Running the Application 🎉
- Run the application using the following command:
  ```bash
  streamlit run app.py
## Usage 🖥️
- Open your web browser and navigate to http://localhost:8501.
- Select your preferred language and desired option from the sidebar.
- Follow the prompts to interact with the application.
  

License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements 🙏
- Streamlit
- Google Translate API
- Pydub
- RapidAPI
  
Feel free to explore, use, and contribute to Aawaz. Happy coding! 💻
