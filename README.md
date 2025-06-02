# Financial Summary using LLM (t5-small)

This project demonstrates how to use a lightweight transformer model (`t5-small`) to summarize structured financial data into professional, human-readable text.

##  Sample Use Case
Automate monthly report summaries from Excel data like:
- Rent paid on time: ₹45,000
- Utilities slightly higher than usual: ₹12,000
- Travel expense for official visit: ₹8,000
- Office supplies: ₹3,000 (One-time)

##  Tech Stack
- Python
- HuggingFace Transformers (`t5-small`)
- Jupyter Notebook
- Pandas

##  Output
> _"This month's financials include: Rent ₹45,000 (Paid on time), Utilities ₹12,000 (Slightly higher than usual)..."_

##  Getting Started
```bash
pip install transformers pandas
