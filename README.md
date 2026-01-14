Hirely - AI Powered Smart Resume Ranker
Hirely 
 it is an AI-powered resume screening tool that runs entirely on your local machine. It allows you to upload a job description and multiple resumes, and then uses a local AI model (via Ollama) to rank candidates based on their fit.

✨ Features

Local-First AI: All processing is done locally. No data is sent to external servers, ensuring 100% privacy.

AI-Powered Ranking: Uses a Large Language Model (Llama 3) to analyze and score resumes against a job description.

Detailed Analysis: Provides a detailed breakdown for each candidate, including:
Overall match score (0-100)
Score breakdown (Experience, Skills, Education)
A concise AI-generated summary
Key strengths and weaknesses

Data Visualization:
A bar chart comparing all candidates' scores.
A doughnut chart showing the distribution of candidates (Top Tier, Promising, Needs Review).
Expandable Details: Click on any candidate card to load a more detailed AI analysis, including skills, work history, and education.

AI Interview Questions: Instantly generate behavioral, technical, and situational interview questions tailored to the candidate's specific resume and the job description.
File Support: Supports both .pdf and .docx file formats for job descriptions and resumes.
Modern UI: A clean, responsive, and animated interface built with TailwindCSS.

🛠️ Tech Stack

Frontend: HTML, TailwindCSS (via CDN), Vanilla JavaScript
AI: Ollama (running llama3)
JS Libraries:
Chart.js for data visualization.
pdf.js for parsing PDF files.
JSZip for parsing .docx files.

🚀 Getting Started

This project is a single HTML file and requires no complex setup. The only prerequisite is running a local Ollama server.

1. Prerequisite: Install & Run Ollama
You must have Ollama installed and running on your machine.

Download and install Ollama from ollama.com.
Pull the llama3 model. This is the model the app is configured to use.
ollama pull llama3
Ensure the Ollama server is running. The app is hardcoded to connect to http://localhost:11434, which is the default.

2. Run the Application
There is no web server to run. Simply open the index.html file in your web browser.

📖 How to Use

Add Job Description: Paste the full job description into the text box on the left, or upload a .pdf/.docx file.
Upload Resumes: Drag and drop one or more resumes (.pdf or .docx) into the upload area on the right.
Rank Resumes: Click the "Rank Resumes" button.
Review Results: The app will process all resumes and display:
A summary of the top-ranked candidates.
Comparative charts.
A detailed card for each candidate, sorted from highest to lowest score.
Get Details:
Click on a candidate's card to expand it and load a more detailed analysis.
Click the "✨ Gen. Questions" button to generate tailored interview questions for that candidate.
Click "View Resume" to open the original resume file in a new tab.

📄 License
This project is open-source and available under the MIT License.