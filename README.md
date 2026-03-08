📄 ATS Resume Analyzer
An AI-powered ATS (Applicant Tracking System) Resume Analyzer that helps job seekers optimize their resumes and increase their chances of getting shortlisted.

✨ Features

📎 Upload resume in PDF or DOCX format
📋 Paste any Job Description
📊 Get an ATS Score out of 100
💪 See your resume Strengths
⚠️ Find Missing Keywords
🛠️ Get Suggestions to Improve
📝 Get an AI-generated Improved Resume
📥 Download the improved resume as .docx
🎨 Clean Green Tech UI


🛠️ Built With
TechnologyPurposePythonCore programming languageStreamlitWeb UI frameworkGroq APIAI model (LLaMA 3.3)PyPDF2Read PDF filespython-docxRead & generate Word filespython-dotenvManage secret API keys

⚙️ Installation & Setup
1. Clone the repository
bashgit clone https://github.com/yourusername/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
2. Install dependencies
bashpip install streamlit groq PyPDF2 python-docx python-dotenv
3. Get your FREE Groq API Key

Go to 👉 https://console.groq.com
Sign up and create an API Key

4. Create a .env file
Create a file named .env in the project folder and add:
GROQ_API_KEY=your_groq_api_key_here
5. Run the app
bashstreamlit run app.py
6. Open in browser
http://localhost:8501

📁 Project Structure
📁 AI-Resume-Analyzer/
   ├── app.py          ← Main application
   ├── .env            ← Your secret API key (never shared)
   ├── .gitignore      ← Hides .env from GitHub
   └── README.md       ← You are here!

🔒 Security

API key is stored in .env file
.env is added to .gitignore so it's never pushed to GitHub
Never share your API key publicly


🙌 How to Use

Open the app in your browser
Upload your resume (PDF or DOCX)
Paste the job description you are applying for
Click Analyze My Resume
View your ATS Score, Strengths, Missing Keywords & Suggestions
Download your AI-improved resume as .docx


🤝 Contributing
Pull requests are welcome! Feel free to open an issue for suggestions or bugs.

📜 License
This project is open source and available under the MIT License.

👨‍💻 Author
Made with ❤️ by Harshith
