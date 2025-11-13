# 🤖 n8n Agents Collection by Brian Richard

Welcome to my collection of **n8n automation workflows** — a set of smart, efficient, and modular agents designed to simplify repetitive tasks and bring intelligent automation to life.

Each agent (workflow) is built using [n8n](https://n8n.io/), an open-source workflow automation tool, and can be imported directly into any n8n instance — whether self-hosted or cloud-based.

---

## 🧩 What This Repository Contains

This repository is organized into two main sections:

| Folder | Description |
|---------|--------------|
| **/agents** | Contains all exported n8n workflow `.json` files. Each file represents a complete automation agent ready to import into your workspace. |
| **/docs** | Contains the documentation (`.md` files) explaining what each agent does, how to set it up, required integrations, and usage tips. |

---

## 📦 Overview of Included Agents

| Agent Name | Description |
|-------------|-------------|
| **AUTO SOCIAL** | Automates social media posting using AI-generated content and images. |
| **Automated LinkedIn Content Creation with GPT-4 and DALL-E for Scheduled Posts** | Generates professional LinkedIn posts with AI text and visuals, schedules, and publishes automatically. |
| **X _ FB automation** | Cross-posts AI-generated content on X (Twitter) and Facebook following each platform’s formatting rules. |
| **✨🤖 Automate Multi-Platform Social Media Content Creation with AI** | Centralized automation to create, design, and publish content across multiple platforms using GPT-4 and DALL·E. |

---

## 🚀 How to Use These Agents

### **1. Open your n8n Instance**
Go to [n8n.io](https://n8n.io) or your self-hosted dashboard.

### **2. Import Workflow**
- Click the **Import Workflow** button.  
- Upload any `.json` file from the `/agents/` folder.

### **3. Configure Credentials**
Set up your required API keys and credentials (e.g., **Gmail**, **Google Sheets**, **OpenAI**, etc.).

### **4. Activate and Run**
Enable the workflow to start automating instantly.  
You can also schedule it, connect triggers, or run it manually for testing.

---

## 🧰 Prerequisites

Before using these agents, make sure you have:

- ✅ An active **n8n account** or **self-hosted instance**
- 🔑 The relevant **API credentials** (e.g., Gmail, LinkedIn, OpenAI)
- 💻 **Node.js** (optional, for local setup)
- 🌐 **Internet connectivity** for integrations
- 🧠 Basic understanding of n8n workflows (nodes, triggers, and connections)

---

## 🧩 Folder Structure

n8n-agents/
│
├── agents/                     # All exported .json workflows from n8n
│   ├── AUTO SOCIAL.json
│   ├── Automated LinkedIn Content Creation with GPT-4 and DALL-E for Scheduled Posts.json
│   ├── X _ FB automation.json
│   └── ✨🤖Automate Multi-Platform Social Media Content Creation with AI.json
│
├── docs/                       # Documentation for each agent
│   ├── AUTO SOCIAL.md
│   ├── Automated LinkedIn Content Creation with GPT-4 and DALL-E for Scheduled Posts.md
│   ├── X _ FB automation.md
│   └── Automate Multi-Platform Social Media Content Creation with AI.md
│
├── assets/                     # (Optional) Screenshots, images, or flow diagrams
│   ├── AUTO SOCIAL.png
│   ├── LinkedIn Agent Demo.png
│   └── Overview Diagram.png
│
├── README.md                   # Main repository overview and usage guide
│
└── LICENSE                     # (Optional) Open-source license (MIT, Apache 2.0, etc.)
