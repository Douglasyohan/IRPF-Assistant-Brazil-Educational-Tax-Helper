# 🧾 IRPF Assistant (Brazil) — Educational Tax Helper

## 📌 Description

A simple, privacy-first web assistant designed to help Brazilian users understand and prepare for their Income Tax (IRPF) declaration. This tool does **not** file taxes — it educates and guides users through the process in a clear and accessible way.

---

## 🎯 Purpose

This project was built to reduce confusion around Brazilian income tax by:

* Explaining how IRPF works in simple terms
* Helping users understand if they may need to declare
* Guiding users step-by-step through their financial information
* Organizing data before using the official government system

---

## ⚠️ Disclaimer

> This application is **not affiliated with Receita Federal** and does **not replace official tools**.
> All results are **educational estimates only**.
> Users are fully responsible for their final tax declaration.

---

## 🧠 Core Concept

The system is designed around three pillars:

### 1. Education

Users first learn how income tax works before interacting with the assistant.

### 2. Assistance

A guided, conversational interface helps users input and understand their financial situation.

### 3. Decision Support

The system applies tax rules to provide insights such as:

* احتمال need to declare
* potential risks or alerts
* structured financial summary

---

## 🏗️ Project Structure

```
/
├── index.html
├── styles.css
├── script.js
├── /modules
│   ├── rules.js        # Tax rules engine (IRPF logic)
│   ├── assistant.js    # Conversational flow
│   ├── ui.js           # Interface rendering
│   └── storage.js      # Local data persistence
└── README.md
```

---

## ⚙️ Technologies

* HTML5
* CSS3
* Vanilla JavaScript
* LocalStorage (client-side only)
* Optional: PWA support

---

## 🔐 Privacy First

* No backend
* No data collection
* No external storage
* All user data stays in the browser

---

## 📊 Key Features

* 📘 Educational introduction (beginner-friendly)
* 🤖 Interactive assistant (step-by-step guidance)
* 📈 Basic tax estimation (non-official)
* ⚠️ Smart alerts (risk indicators)
* 📁 Data organization for official declaration
* 💾 Local save (via LocalStorage)

---

## 📌 Tax Rules Coverage (IRPF 2026)

The assistant considers:

* Annual income thresholds
* Exempt income scenarios
* Asset ownership
* Investments and stock market activity
* Capital gains (sale of assets)
* Foreign income

⚠️ All rules are simplified for educational purposes.

---

## 🚀 Deployment

This is a static application and can be deployed easily using:

* Netlify
* GitHub Pages
* Vercel (static mode)

### Example (Netlify):

1. Upload project files
2. Set publish directory to root
3. Deploy

---

## 📈 Roadmap

### MVP

* Core assistant
* Basic rules engine
* Educational content

### Next Steps

* PWA (offline support)
* Improved UX
* Expanded tax scenarios

### Future Vision

* Integration with economic data APIs
* Personalized insights
* Optional backend for advanced features

---

## 🧩 Contribution

This project is designed as a learning and utility tool. Contributions are welcome for:

* UX improvements
* Tax rule updates
* Accessibility enhancements

---

## 📎 License

MIT License — free to use and modify.

---

## 💡 Final Note

This project is not about replacing the tax system —
it's about making people **understand it better** before they use it.
