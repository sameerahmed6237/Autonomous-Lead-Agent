# Autonomous AI Lead Generation Agent

## Project Overview
An intelligent agent built with n8n that automates the qualification of biotech leads. It bypasses standard scraping limitations and uses scientific validation (PubMed API) to score candidates based on their publication history.

## Key Features
* **Custom Search Logic:** Uses Google Search operators to find niche roles (e.g., "Director of Toxicology") without expensive LinkedIn APIs.
* **Scientific Validation:** Cross-references candidates with the PubMed/NIH database to verify research activity.
* **Scoring Algorithm:** Custom JavaScript engine that scores leads (0-100) based on Role, Location, and Science.
* **Scalability:** Implemented with Batch Loops and Rate Limiters to handle high volumes.

## How to Use
1.  Import `lead-gen-agent.json` into n8n.
2.  Add your SerpApi Key.
3.  Run the workflow.

## Video
View Demo on Google Drive: [Demo](https://drive.google.com/drive/folders/1xMHzIVOFvt_ptOrLLs1zuVnHkKxA3IZJ?usp=sharing)

## Spreadsheet
Google Sheets: [Sheets](https://docs.google.com/spreadsheets/d/1Uvs05OAai_olmbxu2EC5Zl7oheEQRhabH77jQEke5fE/edit?usp=sharing)
