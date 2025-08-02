# Resume & Cover Letter Generator (AI-Powered)

A simple web app built using **Flask** and **OpenAI GPT** that helps you generate a professional resume and cover letter in seconds, based on your input.

![Demo Screenshot](insert-screenshot-link-if-any)
<img width="1920" height="1020" alt="Screenshot 2025-08-02 093633" src="https://github.com/user-attachments/assets/72ea0136-d2a9-4b5e-85e4-566e6add543d" />
<img width="1920" height="1020" alt="Screenshot 2025-08-02 093649" src="https://github.com/user-attachments/assets/f0c4650a-4cc7-4b41-9c8f-0f5a73d60989" />
<img width="1920" height="1020" alt="Screenshot 2025-08-02 093703" src="https://github.com/user-attachments/assets/ea640278-8ca6-48b4-abd3-15d46d63cb23" />


## 🚀 Features

- ✨ AI-generated resume content
- 📝 Personalized cover letter generation
- ⚡ Fast and responsive UI
- 🌙 Dark/Light mode toggle
- 💾 Input history saved locally
- 🔒 API key is kept secure via `.env` file

---

## 📁 Project Structure

resume_cover_gen_ai/
│
├── app.py # Flask backend
├── templates/
│ └── index.html # Frontend UI
├── .env # API key stored securely (not uploaded to GitHub)
├── .gitignore
└── README.md

---

## 🛠️ Tech Stack

- Python + Flask
- OpenAI API (GPT models)
- HTML + Tailwind CSS
- JavaScript (for interactivity)

---

## 🔧 Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/resume_cover-gen-ai.git
   cd resume_cover-gen-ai
2. CREATE A VIRTUAL ENVIRONMENT python -m venv venv
venv\Scripts\activate  # On Windows

3. INSTALL DEPENDECIESpython -m venv venv
venv\Scripts\activate  # On Windows

4.Add your OpenAI API key
Create a file named .env and add:OPENAI_API_KEY=your_api_key_here
OPENAI_API_KEY=your_api_key_here
5.RUN THE APPOPENAI_API_KEY=your_api_key_here
6.
Open your browser and go to:
http://localhost:5000

