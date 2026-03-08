# Prompt for Claude / Copilot

You are an expert **GitHub documentation designer** and **technical writer**.

Create a **high-quality interactive GitHub README.md file** for a project that uses **Reddit to discover ideas, jobs, discussions, startup opportunities, and insights based on user interests**.

The README must be written entirely in **Markdown (.md format)** and should render properly on **GitHub**.

The goal is to make the README:

- visually engaging  
- interactive  
- unique  
- easy to follow  
- visually inspired by Reddit conversations and communities  

---

# Project Concept

The repository builds a **Reddit intelligence engine** that scrapes and analyzes Reddit to extract:

- startup ideas  
- job opportunities  
- freelance gigs  
- technical discussions  
- market problems  
- product ideas  
- trending topics  

The system organizes these insights based on user interests such as:

- AI / Machine Learning  
- DevOps  
- Cloud  
- Startups  
- Remote jobs  
- Indie hacking  
- Tech discussions  

---

# README Requirements

The README must include the following visual and interactive elements.

---

## 1. Project Header

Include:

- Reddit logo  
- project banner  
- animated badges  
- GitHub shields badges  

Example badges:

- Python  
- AI Powered  
- Open Source  
- Reddit API  
- Automation  

---

## 2. Visual Introduction Section

Explain the project idea clearly using:

- icons  
- emojis  
- colored sections  
- simple explanations  

Make it visually appealing.

---

## 3. Architecture Diagram

Include a **Mermaid architecture diagram** showing:
 - Reddit → Scraper → Data Processing → AI Classification → Insight Extraction → Opportunity Feed

 
The diagram should be clean and readable.

---

## 4. Workflow Diagram

Include another **Mermaid workflow diagram** explaining the pipeline:

1. Scrape Reddit posts  
2. Filter useful signals  
3. Categorize content  
4. Extract ideas and opportunities  
5. Store insights  
6. Display results  

---

## 5. Reddit Signal Sources Section

Display a **table listing subreddits used**, such as:

- r/startups  
- r/AppIdeas  
- r/remotejobs  
- r/devops  
- r/machinelearning  
- r/Entrepreneur  

Explain what kind of insights come from each.

---

## 6. Interactive Interest Categories

Create a section showing **interest-based discovery**.

Example table:

| Interest | Insights Discovered |
|---------|---------------------|
| AI | tools, models, research |
| DevOps | jobs, architecture discussions |
| Startups | business ideas |
| Remote Work | global job opportunities |

Use icons and tables to make it visually engaging.

---

## 7. Example Output

Show an example **JSON output** of extracted signals.
```
  {
  "source": "r/startups",
  "title": "Looking for a tool that summarizes long PDFs",
  "category": "Startup Idea",
  "confidence": 0.87,
  "tags": ["AI","SaaS","product idea"],
  "signal": "Problem statement"
  }
```
  
---

## 8. Repository Structure

Show a folder structure tree explaining:

- scraper  
- processing  
- AI modules  
- storage  
- dashboard  

Example structure:
```
reddit-intelligence-engine
│
├── scraper
├── processing
├── ai
├── storage
└── dashboard
```


---

## 9. Visual Pipeline Diagram

Add another **Mermaid flowchart** showing system workflow.

---

## 10. Use Cases Section

Explain how this project can be used for:

- startup discovery  
- job discovery  
- market research  
- idea generation  
- developer insights  

---

## 11. Animations and Visual Design

Make the README visually engaging by using:

- collapsible sections (`<details>`)
- badges  
- icons  
- emojis  
- colored separators  
- diagrams  
- visual layouts  

Avoid large plain text blocks.

---

## 12. Future Roadmap

Include upcoming features such as:

- AI summarization  
- opportunity ranking  
- automated alerts  
- sentiment analysis  
- opportunity dashboards  

---

# Important Constraints

The README must:

- be written entirely in **valid Markdown**
- render properly on **GitHub**
- contain **Mermaid diagrams**
- include **logos and badges**
- look visually engaging
- be structured cleanly

The final output should look like a **modern open-source project README**.

Do **not output explanations** — output only the **final README.md content**.

---

# Optional Enhancement

Add a **Vision section** explaining why Reddit is one of the best sources for discovering:

- real-world problems  
- startup opportunities  
- emerging technology trends  
- community-driven insights  

Make the README feel like a **modern AI-powered open-source project**.