# ReAct Agent - Lab 1

## Name
[Your Name]

## Track
[Frontend / Backend]

## Description
This project implements a minimal ReAct (Reason + Act) agent.

The agent:
- Takes a user query
- Thinks step-by-step
- Uses a calculator tool
- Returns final answer

## How to Run

1. Open the notebook in Google Colab
2. Install dependencies:
   pip install transformers accelerate
3. Run all cells

## Example Output

User: What is 12 multiplied by 8?

Thought:
I need to multiply 12 and 8

Action:
calculator

Action Input:
12 * 8

Final Answer:
96

## Tools Used
- Hugging Face Transformers
- Python

## Observations
- GPT2 has limited reasoning ability
- Tool calling improves accuracy