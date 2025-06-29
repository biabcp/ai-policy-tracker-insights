# ai-policy-tracker-insights
Automate insights, completeness checks, and risk flags for Notion-based AI policies using Azure AI
# AI Policy Tracker Insights  
_An AI Governance Utility by AGI GRC_

This tool helps AI-first startups and tech teams analyze and improve their AI governance policies using Azure OpenAI and Notion. It reads AI policy documents from your Notion-based tracker, evaluates them against the NIST AI Risk Management Framework (AI RMF), and provides actionable insights, risk flags, and compliance alignment scores.

---

## 🔍 Key Features

- ✅ Ingest AI policy content from Notion or CSV
- 🧠 Use Azure OpenAI to classify and summarize policy themes
- 📊 Detect gaps or weak spots based on NIST AI RMF, ISO/IEC 42001, and the EU AI Act
- ⚠️ Flag risks and compliance misalignments
- 📝 Output markdown reports or generate insights into Notion

---

## 🛠 Tech Stack

| Component      | Tool/Service                    |
|----------------|---------------------------------|
| AI Model       | Azure OpenAI (GPT-4 or GPT-3.5) |
| Backend Logic  | Python 3.10+                    |
| Data Source    | Notion API / CSV                |
| Output Format  | Markdown / JSON / Notion API    |
| Hosting (opt)  | Streamlit / Azure Web App       |

---

## 📁 Project Structure

