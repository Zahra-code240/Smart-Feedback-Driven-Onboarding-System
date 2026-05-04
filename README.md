
# 🔁 Smart Client Onboarding System with Feedback Loop (n8n)

🚀 This project is an upgraded version of a basic client onboarding system.

Previously, the system only sent welcome and terms emails.  
Now, it has been enhanced with a **feedback-driven automation system** that collects responses, analyzes them, and takes action automatically.

---

## 🎥 Project Demo

https://youtu.be/LI50EEk-H_U
---

## 🔥 Features

### ✅ Onboarding Automation
- Sends welcome email automatically
- Sends terms & services email
- Uses dynamic client data

### 🔁 Feedback System (NEW 🚀)
- Sends feedback request after a delay
- Collects responses via Tally form
- Stores data in Google Sheets

### 🧠 Smart Decision Logic
- Automatically detects new feedback
- Applies condition-based actions:

| Rating | Action |
|--------|--------|
| ⭐ < 3 | Sends apology email |
| ⭐ ≥ 3 | Requests testimonial |

---

## 🧩 Workflow Overview

```

Client Form → Welcome Email → Wait → Feedback Email
↓
Tally Form → Google Sheets → n8n Trigger → IF Condition → Auto Email

```

---

## 🛠 Tech Stack

- **n8n** – Automation workflows  
- **Google Sheets** – Data storage & trigger  
- **Tally** – Feedback form  
- **Gmail** – Email automation  

---

## 📸 Screenshots

### 🔹 Onboarding Workflow
<img width="1920" height="1020" alt="Screenshot 2026-05-04 212259" src="https://github.com/user-attachments/assets/b8e73037-ace3-4261-bbb8-d8c8dd689053" />

### 🔹 Email Example
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/11492f33-d48a-4353-bdbe-7f1b74fcb058" />


### 🔹 Google Sheets Data
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/045d7d62-81e1-4788-91d3-229bc06d4eea" />


---

## 🚀 How to Run This Project

### 1️⃣ Import Workflow
- Download `workflow.json`
- Import into n8n

### 2️⃣ Connect Services
- Connect Gmail account
- Connect Google Sheets account

### 3️⃣ Setup Tally Form
- Create feedback form (Email, Rating, Feedback)
- Connect Tally to Google Sheets

### 4️⃣ Run Workflow
- Submit onboarding form
- Wait for feedback email
- Submit feedback
- Check automated response

---

## 💡 Key Concept

👉 This is not just automation.

It creates a **feedback loop system**:

- Collect feedback  
- Analyze responses  
- Take action automatically  
- Improve continuously  

---

## 🔁 Upgrade from Previous Version

| Feature | Old System | New System |
|--------|------------|------------|
| Welcome Email | ✅ | ✅ |
| Terms Email | ✅ | ✅ |
| Feedback Collection | ❌ | ✅ |
| Smart Decision Logic | ❌ | ✅ |
| Continuous Improvement | ❌ | ✅ |

---

## 📌 Use Cases

- Freelancers onboarding clients  
- Agencies managing customer experience  
- SaaS onboarding systems  
- Automated feedback handling  

---

## 🚀 Future Improvements

- AI-based feedback analysis  
- Dashboard for insights  
- Slack alerts for negative feedback  
- CRM integration  

---

## 📣 Connect with Me

- LinkedIn: https://www.linkedin.com/in/zahra-bashir-a80a54286/ 
- GitHub: https://github.com/Zahra-code240  

---

## ⭐ Support

If you found this project useful:
- Give it a star ⭐
- Share your feedback
- Fork and improve it 🚀
```

