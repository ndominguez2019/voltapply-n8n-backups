# VoltApply – n8n Workflow Backups

This repository contains JSON backups of all n8n workflows built during the **VoltApply job automation sprint**.

VoltApply is a 14-day build focused on automating job applications using:
- 🧠 AI resume parsing (Gemini API)
- ⚙️ n8n workflow automation
- 🔁 Redis + FastAPI backend
- 🤖 Puppeteer-based LinkedIn automation

---

### 🔄 What's in This Repo

Each workflow is saved daily as a `.json` export from n8n.

📁 Folder structure:
/day-1/

setup.json
/day-2/

resume-upload.json
/day-3/

redis-integration.json
...

yaml
Copy code

---

### ✅ How to Use

1. Download any `.json` file
2. Import it into your [n8n](https://n8n.io/) instance
3. Add credentials and test

---

### 📅 Sprint Progress

| Day | Task                          | Status  |
|-----|-------------------------------|---------|
| 1   | n8n setup                     | ✅ Done |
| 2   | Resume upload + parsing       | ✅ Done |
| 3   | Redis integration             | ✅ Done |
| 4   | GitHub backup + automation    | 🚧 In Progress |

---

### 👤 Author

**Nicolas Dominguez**  
