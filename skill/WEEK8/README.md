# WEEK 8 – Scaled Dot-Product Attention and Multi-Head Attention

## Objective
Implement Scaled Dot-Product Attention and Multi-Head Attention from scratch using PyTorch.

## Project files
- `main.py` – implements the attention calculation, optional causal masking, and a Multi-Head Attention module.
- `requirements.txt` – lists the required Python dependency.

## Setup and execution
Open a terminal in this WEEK8 folder and run:

```powershell
python -m pip install -r requirements.txt
python main.py
```

## Expected results
The program displays:
1. Query, Key, and Value tensor shapes.
2. Scaled dot-product attention weights and output.
3. The Multi-Head Attention input shape and number of heads.
4. Attention weights shape and final output shape.

With the sample input, the expected shapes are:
- Query, Key, Value: `torch.Size([1, 3, 4])`
- Scaled attention output: `torch.Size([1, 3, 4])`
- Multi-Head Attention input: `torch.Size([1, 3, 8])`
- Multi-Head Attention weights: `torch.Size([1, 2, 3, 3])`
- Multi-Head Attention output: `torch.Size([1, 3, 8])`

The tensors contain random values, so the numerical values can differ between runs. A fixed PyTorch seed is set to make this example reproducible.
