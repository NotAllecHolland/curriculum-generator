# curriculum-generator

Requirements
This project uses:

-requests
-getpass (for secure API key input)

Install dependencies locally (optional):

bash pip install -r requirements.txt

How it works

1. User inputs a topic (e.g., "math") and number of days (e.g., 15)

2. A structured prompt is created

3.The prompt is sent to Hugging Faces google/flan-t5-large model

4.The response is parsed and displayed as a 15-day curriculum


########
Updates
########
24 April 2025
switched from falcon-7b (too large for Hugging Face free tier) to google/flan-t5-large
improved prompt formatting for better curriculum generation
added Hugging Face API error handling and increased token limit for longer responses


