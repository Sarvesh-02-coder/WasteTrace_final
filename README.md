# WasteTrace ♻️

WasteTrace is an AI-powered waste tracking and management system designed to help cities and municipalities efficiently detect, classify, and track waste collection activities. The platform enables citizens to report waste using images, while collectors and municipal authorities can monitor, verify, and manage waste tickets in real time.

---

## 🚀 Features

- 📸 **AI-based Waste Detection** using Google Gemini Vision
- 🧍 **Citizen Dashboard** to upload waste images and track status
- 🚛 **Collector Dashboard** to verify and collect reported waste
- 🏛️ **Municipality Dashboard** for centralized monitoring
- 🗺️ **Location-aware reporting** using browser geolocation
- 🔄 **Real-time status updates** synced with Firestore
- ☁️ **Cloud-hosted backend and frontend**

---

## 🧠 Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Zustand (state management)
- Tailwind CSS
- Deployed on **Vercel**

### Backend
- FastAPI (Python)
- Google Gemini Vision API (Image Classification)
- Deployed on **Render**

### Database
- Google **Cloud Firestore**

---

## 🧩 Google Technologies Used

- **Google Gemini API** – AI-powered image classification
- **Google Cloud Firestore** – NoSQL database for tickets, users, and logs
- **Google Cloud IAM** – Secure service account authentication

---

## 📁 Project Structure

```
WasteTrace/
├── main.py              # FastAPI entry point
├── tickets.py           # Ticket routes
├── db.py                # Firestore configuration
├── requirements.txt
├── src/                 # Frontend source code
├── public/              # Frontend public assets
```

---

## ⚙️ Environment Variables

### Backend (Render)
```
GOOGLE_API_KEY=your_gemini_api_key
GOOGLE_APPLICATION_CREDENTIALS_JSON=your_firestore_service_account_json
```

### Frontend (Vercel)
```
VITE_API_URL=https://wastetrace-bc.onrender.com
```

---

## 🧪 Running Locally

### Backend
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend
```bash
npm install
npm run dev
```

---

## 🌍 Live Deployment

- **Frontend:** https://waste-trace.vercel.app  
- **Backend:** https://wastetrace-bc.onrender.com

---

## 📌 Future Enhancements

- User authentication with Firebase Auth
- Analytics dashboard for municipalities
- Push notifications for collectors
- Offline image capture support

---

## 👨‍💻 Authors

- **Sarvesh Sapkal**
- **Shalvi Maheshwari**
- **Laukika Shinde**

---

♻️ *Building cleaner cities with AI & cloud technology*
