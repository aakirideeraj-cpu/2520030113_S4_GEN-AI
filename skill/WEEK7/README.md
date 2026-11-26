# WEEK 7 – Next-Token Probability Analysis

## Objective
Inspect next-token logits, probabilities, and the top-5 candidate tokens using the GPT-2 model from Hugging Face Transformers.

## Files
- `main.py` – loads GPT-2, evaluates four prompts, prints the top-5 next-token candidates, and saves the results.
- `requirements.txt` – Python dependencies.
- `week7_probability_results.csv` – generated automatically when the program runs successfully.

## Setup
Run these commands from the WEEK7 folder:

```powershell
python -m pip install -r requirements.txt
python main.py
```

The first run downloads the GPT-2 model from Hugging Face, so an internet connection is required. PyTorch model loading and inference may take some time depending on the computer.

## Output
The program creates `week7_probability_results.csv` with these columns:
- Prompt
- Rank
- Candidate Token
- Token ID
- Probability

The practical uses four prompts and displays the five highest-probability next-token candidates for each prompt.
