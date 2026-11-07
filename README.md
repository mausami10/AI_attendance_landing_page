# 🎓 VirtualClass | AI Powered Attendance System

A modern landing page for **VirtualClass**, an AI-powered attendance system that uses computer vision and voice biometrics to take classroom attendance in seconds.

### 🌐 [Live Demo → ai-attendance-landing-page-psi.vercel.app](https://ai-attendance-landing-page-psi.vercel.app)

### 🚀 [Try the App → virtualclass-main.streamlit.app](https://virtualclass-main.streamlit.app/)

---

## ✨ About the Project

VirtualClass replaces manual roll calls with two AI-driven methods:

- **FaceID attendance:** one class photo, and every student is identified.
- **Voice ID attendance:** students say "Present" one by one, and their voice is matched against stored embeddings.

This repository contains the **landing page** that introduces the product, walks through the teacher and student journeys, and links to the main Streamlit application.

## 🧩 Page Sections

| Section | What it shows |
|---|---|
| **Hero** | Product intro and a *Start AI Attendance* call to action |
| **Innovative Features** | AI Face Analysis, Sequential Voice ID, QR-Driven Roster |
| **The Teacher's Journey** | 6 steps: Secure Login, Dashboard, Course Management, FaceID Attendance, Voice ID Attendance, Actionable Records |
| **Advanced Tech Stack** | Streamlit & Flask, Face Registration, Voice Embeddings, Supabase Cloud |
| **The Student's Journey** | 3 phases: Instant Enrollment, Biometric Registration, Personal Dashboard |
| **Footer** | Navigation links and branding |

The design is responsive, with breakpoints for desktop, tablet and mobile.

## 🛠️ Tech Stack

**This landing page**

- [Flask](https://flask.palletsprojects.com/) with Jinja2 templates
- HTML5 and CSS3 (custom styling, Google Fonts: *Outfit* and *Climate Crisis*)
- Deployed on [Vercel](https://vercel.com/)

**The VirtualClass app (separate repository)**

- Streamlit for the interface
- `face_recognition` and Dlib for facial biometrics
- Resemblyzer and Librosa for voice embeddings
- Supabase (PostgreSQL) for storage and authentication

## 📁 Project Structure

```
AI_attendance_landing_page/
├── app.py                 # Flask app (serves the landing page)
├── templates/
│   └── index.html         # Landing page template
└── static/
    ├── css/
    │   └── style.css      # Styles
    ├── js/
    │   └── script.js      # Scripts
    └── img/
        ├── logo.png
        ├── app_logo.png
        └── demo/          # App screenshots
```

## ▶️ Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/mausami10/AI_attendance_landing_page.git
   cd AI_attendance_landing_page
   ```

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   # Windows (PowerShell)
   venv\Scripts\Activate.ps1
   # macOS / Linux
   source venv/bin/activate
   ```

3. **Install Flask**

   ```bash
   pip install flask
   ```

4. **Start the app**

   ```bash
   python app.py
   ```

5. Open **http://127.0.0.1:5002** in your browser.

## 👩‍💻 Author

**Mausami Chaudhari**

- GitHub: [@mausami10](https://github.com/mausami10)

## 📄 License

This project is for educational and portfolio purposes.

---

⭐ If you like this project, consider giving the repository a star!