# WEEK 6 – LLM Baseline Evaluation

This folder contains the Week 6 practical for evaluating a locally hosted large language model using Ollama and Python.

## Tools and technologies
- Python 3.14
- Ollama
- Llama 3.2
- JSON question set
- Python `requests` package

## Project files
Add the practical source files and final evaluation output to this folder:
- `main.py` – baseline evaluation script
- `golden_set.json` – evaluation questions and expected answers
- `requirements.txt` – Python dependencies
- `baseline_results.csv` – generated evaluation results
- `WEEK6_LLM_Baseline_Evaluation_Report.pdf` – practical report

## Run
From this folder, install the listed dependencies and run:

```powershell
python -m pip install -r requirements.txt
python main.py
```

Make sure the Ollama service is running and the required model is available locally before starting the evaluation.
