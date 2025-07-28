# 🚀 Adobe India Hackathon 2025 – Round 1B

Smart PDF analyzer that extracts the most relevant sections based on a user persona and task from a set of PDF documents.

---

## 📌 Use Case

Given a **persona** and a **job to be done**, the script processes a collection of PDFs and outputs a structured `output.json` with:
- Most relevant sections (titles, pages)
- Important refined sentences (subsections)
- Complete metadata

---

## 🧠 Examples

| Collection | Persona           | Job                                                                 |
|-----------:|-------------------|----------------------------------------------------------------------|
| 1          | Travel Planner     | Plan a 4-day trip for 10 college friends                            |
| 2          | HR Professional    | Create and manage fillable forms for onboarding                     |
| 3          | Food Contractor    | Prepare a vegetarian buffet menu including gluten-free items        |

---

## ⚙️ Run Locally

Install requirements:
```bash
pip install -r requirements.txt
