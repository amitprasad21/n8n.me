<div align="center">
  <h1>🚀 Automated Workflows & AI Agents Mastery</h1>
  <p><strong>A continuously growing repository of powerful n8n automations, AI agents, and workflow systems designed for maximum efficiency.</strong></p>

  [![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-ff6c37?logo=n8n)](https://n8n.io/)
  [![OpenAI](https://img.shields.io/badge/OpenAI-GPT_Powered-412991?logo=openai)](https://openai.com/)
  [![Status](https://img.shields.io/badge/Status-Actively_Updated-00B050?style=flat-square)]()
</div>

<br />

Welcome to my Automation Hub! This is my personal collection of automated processes and AI-powered workflows. I strongly believe in the power of automation to eliminate repetitive tasks and streamline operations. **I continuously update this repository with new automations, tools, and best practices as I build them.** 

Whether you're looking to automate your inbox, extract intelligence from PDFs, or deploy multi-agent AI frameworks, you'll find real-world examples here.

---

## 🔥 Featured Automations & Use Cases

Here are a few of the most powerful workflows in this repository and how you can use them:

### 1. 🧠 Smart Email Classifier + AI Support Agent (`Smart Email Classifier + Support Draft...json`)
**What it does:** This workflow watches your Gmail inbox, intelligently parses incoming emails using LangChain and OpenAI, and categorizes them (e.g., Support, Order Query, Job Opportunity, Spam). Depending on the category, it completely routes your workload:
- **Support / Order emails** are handled by an AI Agent that queries a Vector Database (RAG) containing company knowledge and automatically drafts a support reply directly in your Gmail.
- **Job Opportunities or Urgent Tasks** trigger immediate Telegram alerts so you never miss an important opportunity.
**Why it's useful:** Completely eliminates manual email sorting. It drastically improves response times to customers while letting you focus only on the emails that matter.

### 2. 🧾 Autonomous Invoice Parsing System (`Invoice Parsing Workflow (1).json`)
**What it does:** Monitors a Google Drive folder for newly uploaded PDF invoices. Automatically downloads them, extracts complex, unstructured data using OpenAI Information Extractor models, structures the data into required JSON formats, and logs all critical details (Invoice Number, Amount, Client, Date) into a Google Sheet. It then uses AI to write a natural language email summarizing the addition to notify the billing team.
**Why it's useful:** Saves hours of manual data entry in accounting and billing departments. It handles inconsistent PDF layouts seamlessly thanks to LLM-based extraction.

### 3. 🕸️ Intelligent Web Scraping Pipeline (`Web Scraping.json`)
**What it does:** Demonstrates three robust layers of data extraction: 
1. **Raw HTTP Requests** for fast, simple sites.
2. **Firecrawl Integration** for scraping Javascript-heavy modern sites into clean Markdown or JSON formats without getting IP blocked.
3. **Apify Website Content Crawler** for large-scale, complex scraping operations handling authentication or deep-site rendering.
**Why it's useful:** Whether you are building AI training datasets, tracking competitor pricing, or curating newsletters, this automation provides you with the right tool depending on complexity.

### 4. 🤖 Agentic Frameworks (`4 Agentic Frameworks.json` & `Ai Agent.json`)
**What it does:** Workflows structured specifically to utilize modern multi-agent systems via prompt engineering and modular LLM orchestration. 
**Why it's useful:** Takes tasks beyond one-shot processing. By using agentic logic, the AI can plan, retrieve tools, and reflect on outputs autonomously before completing complex workflows bridging multiple software platforms.

---

## 📂 Full Operations Directory

This repository hosts workflows designed for diverse use cases:

- **AI Agents & Prompting Engine**  
  - 🤖 `4 Agentic Frameworks.json`  
  - 📝 `AI Agent Prompting.json`  
  - 🧠 `Ai Agent.json`

- **Email Mastery**  
  - 📧 `Amit Smart Email Assistant - Working Version.json`  
  - 📨 `Draft Email n8n.json`  
  - 🗂️ `Smart Email Classifier + Support Draft + Job_Assignment Alerts.json`

- **Data Processing & Utilities**  
  - 📄 `AskAnythingFormPDF.json` (Conversational PDF interaction)  
  - 💵 `Invoice Parsing Workflow (1).json`  
  - 🕷️ `Web Scraping.json`

- **Knowledge & Best Practices**  
  - 🛡️ `Error Handling.json`  
  - 💡 `Tips.json`  
  - 🎓 `learnn8n.json`
  - 🖼️ **Prompt Engineering Resources:** Features highly detailed images containing rules and best practices for multi-agent reasoning.

---

## 🚀 How to Use These Workflows

Using these files is incredibly simple if you have [n8n](https://n8n.io/):

1. Clone or download this repository.
2. Open your local or cloud instance of **n8n**.
3. In your n8n workspace, click **Import from File...** or simply copy the JSON code and paste it into the n8n canvas.
4. **Connect Credentials:** Some nodes (like Gmail, OpenAI, Supabase, Google Drive, Telegram, Apify) will require you to map your own credentials and API keys.
5. Click **Test Workflow**!

---

## 🔄 Updates & Contributions

**This repository is a living breathing workspace.** 
I am constantly exploring the bleeding edge of workflow automation, agentic AI, and APIs. Expect regular optimizations to existing files and the addition of brand-new automations entirely. 

*If these workflows helped streamline your business or life, feel free to star the repo or use them as a foundation to build something amazing!*
