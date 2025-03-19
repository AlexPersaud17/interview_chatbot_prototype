# Interview Prep Chatbot
This project is a prototype for an Interview Prep Chatbot built with Streamlit and OpenAI's GPT-4. The chatbot assists users in preparing for interviews by simulating an interview environment and providing feedback after the interview is completed.

## Features
Personal Information Setup: Collects user data, such as name, experience, and skills.
Company & Position Setup: Allows users to choose the company, position, and their level (Junior, Mid-level, Senior).
Chatbot Interaction: The chatbot simulates an interview scenario by asking questions based on the user's information and responses.
Feedback Generation: After the interview, users can get feedback on their performance from the chatbot.
## Installation
To run the project locally, follow the steps below.

## Prerequisites
- Python 3.x
- Streamlit
- OpenAI API key
1. Clone the Repository
git clone https://github.com/AlexPersaud17/interview_chatbot_prototype.git

2. Install Dependencies
Navigate to the project folder and install the necessary dependencies using pip.

cd interview_chatbot_prototype
pip install -r requirements.txt

3. Set Up OpenAI API Key
Create an .env file or add your OpenAI API key in st.secrets if you're using Streamlit's Secrets Management.

Example for .env:

ini
Copy
Edit
OPENAI_API_KEY=your-api-key-here
4. Run the Streamlit App
Run the app with Streamlit:

streamlit run app.py

How to Use
Setup: Fill in your personal information (name, experience, skills), company, position, and level.
Start Interview: Once the setup is complete, the chatbot will begin the interview process.
Answer Questions: The chatbot will ask questions related to your role, experience, and skills. Provide your answers.
Feedback: After the interview, you can request feedback on your performance. The chatbot will generate a score and provide constructive feedback.
Technologies Used
Streamlit: Framework for creating web applications quickly.
OpenAI GPT-4: AI model used for generating interview questions, responses, and feedback.
Python: Programming language used for backend logic.
Streamlit_js_eval: Used to reload the page after completing the interview.
Future Improvements
More dynamic question generation based on the user's profile.
Additional companies and positions for a broader interview preparation experience.
