AI Blog Generator
Description

AI Blog Generator is a web application built with Python, Streamlit, LangChain, and Google Gemini. It enables users to generate well-structured, high-quality blog posts by providing a topic and selecting the desired tone, length, and target audience.

Features
Generate AI-powered blog posts
Choose different writing tones
Select blog length (Short, Medium, Long)
Target different audiences
Adjust creativity using the temperature slider
Markdown-formatted output
Simple and intuitive user interface
Tech Stack
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
Create and Activate a Virtual Environment

Windows

python -m venv venv
venv\Scripts\activate

macOS/Linux

python -m venv venv
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
Configure Environment Variables

Create a .env file in the project root and add your Google Gemini API key:

GOOGLE_API_KEY=your_google_api_key
Run the Application
streamlit run app.py

Open your browser and visit:

http://localhost:8501
Usage
Enter a blog topic.
Select the desired tone.
Choose the blog length.
Select the target audience.
Adjust the temperature if required.
Click Generate Blog.
View the generated blog and copy it as needed.
Example

Input

Topic: Artificial Intelligence
Tone: Professional
Length: Medium
Audience: Students

The application generates a structured blog with:

Title
Introduction
Multiple headings
Practical examples
Conclusion
Key takeaways
Future Enhancements
Download blogs as PDF or DOCX
SEO-friendly content generation
Blog history
Multi-language support
AI-generated cover images
One-click copy and download
Contributing

Contributions are welcome. If you would like to improve this project:

Fork the repository.
Create a new branch.
Commit your changes.
Push the branch.
Submit a Pull Request.
License

This project is licensed under the MIT License.
