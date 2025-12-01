🔗 Generate a Company Brochure From Any Website URL Using LLMs

This project uses a Large Language Model (LLM) to automatically create a polished company brochure from any website link you provide.

Just pass a URL → the model extracts the website’s textual content → analyzes the business → and outputs a clean, ready-to-use brochure-style summary.

Perfect for:

- Business analysis
- Rapid brand understanding
- Client onboarding
- Marketing prep
- Automated document generation

🚀 What This Project Does

✅ 1. Extracts Website Content

The helper script scraper.py cleans and extracts readable text from any website using BeautifulSoup.
It removes irrelevant elements like <script>, <style>, img, etc.
📌 Source: scraper.py

✅ 2. Sends Content to an LLM API

The notebook (project_1.ipynb) uses an intelligent LLM (your model of choice) to process the extracted website content.

The LLM analyzes:

- What the company does
- Services/products
- Target customers
- Unique value
- Contact info (if available)

✅ 3. Generates a Professional Brochure

The model outputs a well-structured brochure that may include:

- 🏢 Company overview
- 🛠️ Products & services
- ⭐ Key highlights
- 🎯 Target audience
- 🤝 Why choose them
- 📞 Contact or CTA

Your notebook formats the final output into a clean, readable brochure.

🛠️ Technologies Used

| Tool                | Purpose                    |
| ------------------- | -------------------------- |
| 🐍 Python           | Main programming language  |
| 🔗 Requests         | API calls & web fetching   |
| 🧼 BeautifulSoup    | Website content extraction |
| 🤖 LLM API          | Brochure generation        |
| 📘 Jupyter Notebook | Main application workflow  |
