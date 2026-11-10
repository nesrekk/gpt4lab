# GPT-4 Lab (25CS2506 – Building Applications Using GPT-4)

Six beginner Python experiments that use a locally running [Ollama](https://ollama.com) model (`llama3.2`).

| # | Program | Data file |
|---|---------|-----------|
| 1 | `exp1_ecommerce_chatbot.py` – E-commerce chatbot | `products.csv` |
| 2 | `exp2_blog_generator.py` – AI blog content generator | – |
| 3 | `exp3_email_assistant.py` – Intelligent email assistant | – |
| 4 | `exp4_course_recommender.py` – Personalized course recommendation | `courses.csv` |
| 5 | `exp5_document_analyzer.py` – Document analyzer (summarize, query, export) | `ai.txt` |
| 6 | `exp6_medical_assistant.py` – Medical information assistant | `health_info.txt` |

All programs import `ask_ollama()` from `ollama_helper.py`.

## Setup

```bash
pip install requests
ollama list            # the model name in ollama_helper.py must match one listed here
ollama run llama3.2    # check the model works, then exit
```

## Run

```bash
python3 exp1_ecommerce_chatbot.py
```

Keep the helper, the data files and the programs in the same folder. Model answers vary between runs.
