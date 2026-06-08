# 💌 TDC Matchmaker Dashboard

An internal matchmaking tool for **The Date Crew** team — manage client profiles, view biodata, and assign AI-scored matches.

🔗 **Live Demo**: [bright-dango-33dcc9.netlify.app](https://bright-dango-33dcc9.netlify.app)  
🔐 **Login**: `priya.sharma` / `tdc@2024`

---

## ✨ Features

- 🔐 Secure matchmaker login
- 👥 Client list with filters & search
- 📋 Full biodata view per client
- 🤖 AI-scored matches with compatibility explanations
- 📧 Send Match modal with personalized intro email
- 🌙 Dark mode support

---

## 🔄 App Flow

```
┌─────────────┐
│  Login Page │
└──────┬──────┘
       │ Authenticated
       ▼
┌─────────────────┐
│  Dashboard /    │
│  Client List    │
└──────┬──────────┘
       │ Click a client
       ▼
┌─────────────────┐
│  Client Detail  │
│  View (Biodata) │
└──────┬──────────┘
       │ View Matches
       ▼
┌──────────────────────┐
│  AI Match Engine     │
│  (Scored + Ranked)   │
└──────┬───────────────┘
       │ Click "Send Match"
       ▼
┌──────────────────────┐
│  Email Modal /       │
│  Match Confirmation  │
└──────────────────────┘
```

---

## 🧠 Matching Logic

| Client Gender | Logic Used |
|---|---|
| Male | Women who are younger, shorter, earn less, compatible on kids/relocation |
| Female | Compatibility on profession, values, lifestyle, languages, relocation |

---

## 🛠 Tech Stack

`HTML` · `CSS` · `Vanilla JavaScript` · `Netlify`

---

## 👩‍💻 Built by
**Sulochana Kumari** — Full Stack Developer Internship Assignment @ The Date Crew
