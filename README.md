# 🌿 Serenity — Mental Health & Wellness Platform

A full-featured digital wellness companion for mood tracking, clinically-modeled mental health screening, guided breathing, reflective journaling, and crisis support — built with a focus on calm, accessible design and genuine self-awareness tools.

**Live demo:** [github-pages link]
**Stack:** HTML, CSS, JavaScript (vanilla) · LocalStorage for persistence

---

## ✨ Features

### 📊 Mood Tracker
- Daily mood logging with optional notes
- Animated 7-day trend chart with mood-specific color coding
- Streak tracking to encourage daily check-ins
- Full mood history log with timestamps

### 🧪 Clinical Self-Assessments — PHQ-9 & GAD-7
- Implements the **PHQ-9** (depression) and **GAD-7** (anxiety) screening tools used by clinicians worldwide
- Real-time answered-question tracking and validated scoring logic
- Automatic severity categorization (minimal → severe) with a visual severity-range breakdown
- Personalized, severity-matched recommendations
- Clear self-awareness disclaimer — not a diagnostic substitute for professional care

### 🤖 Sage — AI Wellness Companion
- Conversational chat widget with intent-detection across 12+ categories (anxiety, low mood, anger, sleep issues, gratitude, crisis language, and more)
- Context-aware, empathetic response selection with natural typing-delay simulation
- Quick-reply shortcuts and markdown-formatted responses
- Built-in crisis-keyword detection that redirects to helpline resources

### 📓 Guided Journal
- Curated reflective writing prompts (gratitude, self-compassion, growth, intention-setting)
- Live word count, autosave-style entry management, and a searchable saved-entries list

### 🧘 Guided Breathing Exercises
- Three techniques: 4-7-8 (sleep/calm), Box Breathing (focus), 5-5 (everyday use)
- Animated breathing circle with live phase countdown
- Session stats: cycle count and total duration tracking

### 🩺 Find a Therapist
- Filterable directory of mental health professionals by specialty (anxiety, depression, trauma)
- Full booking flow: session type, date, and time-slot selection
- Simulated end-to-end payment checkout with card formatting/validation and a booking confirmation receipt

### 🆘 Crisis Support
- Always-visible crisis helpline directory (iCall, Vandrevala Foundation, NIMHANS, emergency services)
- A confidential "talk to someone" contact form with validation

### 🎨 Design
- Fully responsive layout (mobile, tablet, desktop)
- Light/dark theme toggle with persisted preference
- Scroll-triggered fade-in animations throughout

---

## 🏗️ Architecture

```
Frontend (HTML, CSS, JavaScript)
        ↓
Component-style rendering (mood charts, assessments, chat, booking)
        ↓
LocalStorage persistence layer (moods, journal entries, theme)
        ↓
Client-side rule engine (Sage chatbot intent matching, PHQ-9/GAD-7 scoring)
```

No backend — all logic, scoring, and persistence run client-side.

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS (custom properties, responsive grid/flexbox, animations) |
| Logic | Vanilla JavaScript |
| Persistence | Browser LocalStorage |
| Fonts | DM Serif Display, Outfit (Google Fonts) |

---

## 🎯 Use Cases

- Daily mental health and mood tracking
- Self-screening for anxiety/depression symptoms ahead of a doctor's visit
- Guided stress and anxiety management
- Reflective journaling and self-awareness building
- Finding and booking a mental health professional

---

## 🔮 Future Enhancements

- 🔐 User authentication and account sync
- ☁️ Backend + database for cross-device data persistence
- 🤖 LLM-powered chatbot responses (replacing rule-based matching)
- 💳 Real payment gateway integration for therapist bookings
- 📱 Native mobile app
- 📈 Advanced longitudinal mood/assessment analytics

---

## 👨‍💻 Author

**Dhairya Kumar**
B.Tech Final Year Project — Computer Science (Cloud Computing)

---

## ⚠️ Disclaimer

Serenity is a self-awareness and wellness tool, not a substitute for professional medical diagnosis or treatment. The PHQ-9 and GAD-7 assessments are screening instruments, not diagnostic tools. If you or someone you know is in crisis, please contact a crisis helpline or emergency services immediately.
