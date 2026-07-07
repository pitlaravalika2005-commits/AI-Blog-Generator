AI Blog Generator
Overview

AI Blog Generator is a web application built using Python, Streamlit, LangChain, and Google Gemini. It allows users to generate high-quality blog posts by providing a topic and selecting the preferred tone, length, and target audience.

Features
Generate AI-powered blog posts
Multiple writing tones
Select blog length (Short, Medium, Long)
Choose the target audience
Adjustable creativity using the temperature slider
Markdown-formatted output
Simple and responsive user interface
Technologies Used
Python
Streamlit
LangChain
Google Gemini API
Python Dotenv
Project Structure
AI-Blog-Generator/
│── app.py
│── blog_generator.py
│── prompt.py
│── utils.py
│── requirements.txt
│── .env
└── README.md
Installation
Clone the Repository
git clone https://github.com/your-username/AI-Blog-Generator.git
cd AI-Blog-Generator
Create a Virtual Environment

Windows

python -m venv venv
venv\Scripts\activate

Linux/macOS

python -m venv venv
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
Configure the API Key

Create a .env file in the project directory and add your Google Gemini API key.

GOOGLE_API_KEY=your_google_api_key
Running the Application

Start the Streamlit application using:

streamlit run app.py

The application will open in your browser at:

http://localhost:8501
Usage
Enter a blog topic.
Select the desired tone.
Choose the blog length.
Select the target audience.
Adjust the temperature if needed.
Click Generate Blog.
View and copy the generated blog.
Future Improvements
Export blogs as PDF or DOCX
SEO optimization
Multiple language support
Blog history
Download generated blogs
AI-generated images
Contributing

Contributions are welcome. Feel free to fork the repository, make improvements, and submit a pull request.

License

This project is licensed under the MIT License.
