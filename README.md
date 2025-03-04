# A.I.M.E.D – Authenticity Inspector for Modern Employment Detection  

## 🔍 Overview  
A.I.M.E.D is a **job verification platform** designed to tackle **employment fraud** by ensuring job listings are **authentic and reliable**. It uses **ensemble learning models** and **community-driven verification** to detect fraudulent job postings, safeguarding job seekers from scams.  

## 🚀 Features  
- ✅ **Fraud Detection with Ensemble Learning** – Multiple machine learning models analyze job listings for suspicious patterns.  
- ✅ **Community Voting System** – Users can vote on job authenticity to improve verification accuracy.  
- ✅ **Company Profile Verification** – Cross-checks company details to ensure legitimacy.  
- ✅ **Login & Security Tracking** – Monitors login history and flags suspicious activity.  
- ✅ **Real-Time Alerts** – Notifies users of potentially fake job postings.  

## 🏗️ Tech Stack  
- **Backend:** Django 5.1.6  
- **Database:** SQLite  
- **Machine Learning:** Scikit-learn, OpenAI API  
- **Web Scraping:** SerpApi for job listings  
- **Authentication:** Django authentication system  

## 📂 Project Structure  
```
📦 A.I.M.E.D  
├── 📂 aimed/              # Main Django app  
│   ├── 📂 models/         # Database models  
│   ├── 📂 views/          # API views  
│   ├── 📂 templates/      # HTML templates  
│   ├── 📂 static/         # CSS, JS, and images  
│   └── 📂 ml/             # Machine learning fraud detection scripts  
├── 📜 requirements.txt    # Python dependencies  
├── 📜 README.md           # Project documentation  
├── 📜 manage.py           # Django management script  
└── 📜 db.sqlite3          # SQLite database  
```

## ⚡ Installation & Setup  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/aimed.git
   cd aimed
   ```

2. **Create a virtual environment & install dependencies:**  
   ```bash
   python -m venv job_venv  
   source job_venv/bin/activate  # (Windows: job_venv\Scripts\activate)
   pip install -r requirements.txt
   ```

3. **Run migrations & start the server:**  
   ```bash
   python manage.py migrate  
   python manage.py runserver  
   ```

4. **Access the platform:**  
   Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## 🛠️ Future Improvements  
- 📱 **Mobile App Integration** – Expanding A.I.M.E.D to Android & iOS.  
- 🔍 **Advanced Fraud Detection** – Enhancing ensemble learning with deeper NLP models.  
- 🔗 **API Integration with Major Job Portals** – Direct job verification via LinkedIn, Indeed, etc.  

## 👥 Contributing  
Contributions are welcome! Feel free to fork this repository, submit pull requests, or report issues.  

## 📜 License  
This project is licensed under the **MIT License**.  

## ✍️ Authors  
- **Sumit Prasad, B.Tech CSE, 6th Sem (Batch:- 2022-26), National Institute of Technology, Nagaland**:   
- **Bigit Krishna Goswami, M.Tech CSE, 4th Sem (Batch:- 2023-25), National Institute of Technology, Nagaland** https://github.com/Bigit1024
