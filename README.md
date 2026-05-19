# 📸 Instagram Lead Generation Automation

<p align="center">
  <strong>Automatically discover targeted Instagram business leads and store them in Airtable using n8n, Apify, and no-code automation.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge&logo=n8n" />
  <img src="https://img.shields.io/badge/Apify-Web%20Scraping-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Airtable-CRM-blue?style=for-the-badge&logo=airtable" />
  <img src="https://img.shields.io/badge/Instagram-Lead%20Generation-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  <img src="https://img.shields.io/badge/No--Code-Workflow-red?style=for-the-badge" />
</p>

---

## 🚀 Project Overview

This project is a fully automated **Instagram Lead Generation System** built with **n8n**.

Simply enter a target niche and location (for example, `Dentists in Pune`) through a web form, and the workflow will:

* 🔍 Search Google for relevant Instagram business profiles
* 🕸️ Scrape business data using Apify
* 🧹 Clean and structure the extracted information
* 📊 Store all leads automatically in Airtable
* 🚀 Create a CRM-ready database for outreach campaigns

> ⏱️ What normally takes hours of manual prospecting is completed in just a few minutes.

---

## ✨ Features

* 📝 Form-based input for niche and location
* 🌍 Works for any industry and city
* 📸 Extracts Instagram profile URLs
* 👤 Captures business names and usernames
* 📄 Collects bios and descriptions
* 📈 Retrieves follower counts
* 🖼️ Saves profile images
* 📊 Stores leads in Airtable
* ⚡ Fully automated end-to-end
* 🧩 Built entirely with no-code tools

---

## 🏗️ Workflow Architecture

```text
Niche + Location Input Form
            ↓
      n8n Form Trigger
            ↓
   Apify Google Search Scraper
            ↓
        Wait for Results
            ↓
   JavaScript Data Cleaning
            ↓
      Airtable Storage
            ↓
     Structured Lead Database
```

---

## 🛠️ Tech Stack

| Technology | Purpose                          |
| ---------- | -------------------------------- |
| n8n        | Workflow orchestration           |
| Apify      | Google search and web scraping   |
| Airtable   | Lead storage and CRM             |
| JavaScript | Data cleaning and transformation |
| Instagram  | Lead source                      |

---

## ⚙️ How It Works

### 1️⃣ Submit Search Criteria

The user enters a business niche and target location.

**Example:** `Dentists in Pune`

### 2️⃣ Search Instagram Profiles

Apify searches Google and finds relevant Instagram business accounts.

### 3️⃣ Wait for Scraping Completion

The workflow pauses until Apify returns the results.

### 4️⃣ Clean and Structure Data

JavaScript extracts and formats key information.

### 5️⃣ Store in Airtable

Each lead is saved to Airtable in a structured table.

### 6️⃣ Ready for Outreach

The resulting database can be used for email, DM, and sales campaigns.

---

## 📊 Extracted Data Fields

* Business Name
* Instagram Username
* Instagram Profile URL
* Bio / Description
* Followers Count
* Profile Image
* Search Query
* Date Added

---

## 📂 Project Structure

```text
instagram-lead-generation/
├── workflow.json
├── README.md
├── docs/
│   └── architecture.md
└── .gitignore
```

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/instagram-lead-generation.git
cd instagram-lead-generation
```

### 2. Import Workflow into n8n

* Open n8n
* Click **Import from File**
* Select `workflow.json`

### 3. Configure Credentials

Add the following credentials:

* Apify API Token
* Airtable Personal Access Token
* Airtable Base ID and Table Name

### 4. Activate the Workflow

Publish and enable the workflow.

### 5. Submit a Search Query

Use the form to enter your target niche and location.

---

## 📥 Example Input

```text
Dentists in Pune
```

## 📤 Example Output

Airtable table populated with targeted Instagram leads ready for outreach.

---

## 🎯 Use Cases

### 📈 Digital Marketing Agencies

Generate qualified leads for client acquisition.

### 💼 Freelancers

Find local businesses that need SEO, ads, websites, or automation.

### 🚀 Sales Teams

Build targeted prospect lists at scale.

### 🤝 Outreach Campaigns

Use leads for cold email, Instagram DM, and LinkedIn campaigns.

### 🔍 Competitor Research

Analyze businesses in specific niches and locations.

---

## 📈 Performance Benefits

| Task                 | Manual Time | Automated Time |
| -------------------- | ----------: | -------------: |
| Search and discovery |   30–60 min |        2–5 min |
| Data collection      |     1–2 hrs |        1–3 min |
| CRM entry            |   20–40 min |        < 1 min |
| **Total**            | **2–3 hrs** |    **3–8 min** |

---

## 🔒 Security Best Practices

* Never commit API keys or tokens.
* Store secrets in n8n credentials.
* Blur tokens in screenshots.
* Rotate exposed credentials immediately.

---

## 🚀 Future Enhancements

* 📧 Automated cold email sending
* 💬 Instagram DM automation
* 🧠 AI lead scoring
* 📞 Contact enrichment
* 🗂️ Notion and Google Sheets integration
* 📊 Analytics dashboard

---

## 🏷️ Recommended GitHub Topics

```text
n8n
automation
lead-generation
instagram
instagram-scraper
apify
airtable
crm
no-code
sales-automation
workflow-automation
prospecting
```

---

## ⭐ Support the Project

If you find this project useful:

* ⭐ Star the repository
* 🍴 Fork the project
* 🛠️ Contribute improvements
* 📢 Share it with others

---

## 👨‍💻 Author

**Mohammad Shahnawaz**

* GitHub: [https://github.com/Shahnawaz9493](https://github.com/Shahnawaz9493)
* LinkedIn: [https://www.linkedin.com/in/mohammad-shahnawaz-22981121a/](https://www.linkedin.com/in/mohammad-shahnawaz-22981121a/)

---

## 📄 License

This project is licensed under the MIT License.
