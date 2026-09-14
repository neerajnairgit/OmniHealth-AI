# 🏥 OmniHealth AI — Clinician-Verified Smart AI Triage Platform

**OmniHealth AI** is a web-native, clinician-validated AI symptom triage engine designed to bridge the gap between automated health checking and professional medical oversight. It provides patients with real-time, consumer-friendly urgency evaluations while offering clinicians a seamless human-in-the-loop portal to review, modify, and cache clinical decisions.

---

## ✨ Key Features

### 👨‍👩‍👧‍👦 1. Patient Triage Portal
* **Intuitive Symptom Intake:** Simple inputs for age, gender, symptom duration, discomfort level (1–10 scale), and interactive multi-symptom selection chips across high-, moderate-, and low-risk categories.
* **Consumer-Friendly Guidance:** Explains complex health assessments using clear, non-technical language tailored for patient understanding.
* **Direct Urgency Callout:** Highlights clear, actionable advice (e.g., *Immediate Emergency Care*, *Urgent Care within 24–48 hours*, or *Home Rest*) instantly.
* **Risk & Confidence Analytics:** Displays AI confidence percentages alongside dynamic risk weight distributions (Critical %, Moderate %, Low %).
* **Warning & Escalation Protocols:** Provides explicit lists of progression symptoms to monitor and step-by-step guidance on what to do if conditions worsen.

### 🩺 2. Clinician Review Portal (Human-in-the-Loop)
* **Secure Access:** Password-protected portal for healthcare professionals.
* **Interactive Assessment Override:** Clinicians can review pending patient assessments, edit urgency ratings, alter reasoning, modify recommended actions, and update progression symptoms.
* **Cached Protocol Memory:** Once approved, verified clinical protocols are stored in memory so identical future symptom presentations return 100% clinician-verified assessments immediately.

### 📊 3. Step 3 • Quality Assurance & Verified Clinical Database
* **Live Analytics Dashboard:** Real-time metrics comparing AI predictions against clinician ground-truth decisions.
* **Performance Tracking:** Tracks total cases reviewed, overall agreement rate %, low urgency agreement %, and high urgency agreement %.
* **Case History Log:** Displays a complete history log of past cases, highlighting AI-Clinician agreements and clinician override instances.

---

## 🛠️ Technology Stack

* **Frontend:** Standard HTML5, CSS3 (CSS Variables, Flexbox, CSS Grid)
* **Logic & Analytics:** Pure Client-Side Vanilla JavaScript (ES6+)
* **Typography & Icons:** Inter (Google Fonts), Inline SVG Icons
* **Deployment:** Zero external dependencies—runs directly in any modern web browser or static hosting platforms (GitHub Pages, Vercel, Netlify).

---

## 🚀 Quick Start / How to Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/omnihealth-ai.git](https://github.com/your-username/omnihealth-ai.git)
