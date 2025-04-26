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
hat 

I Built and Tried:
- Created a working Binder-hosted app using Python and Jupyter Notebook
- Integrated Hugging Face’s inference API and handled real-time prompt/response flow
- Implemented input validation, dynamic prompt generation, and error handling
- Iterated on 10+ prompt formats to guide the model toward better structured output
- Tested alternative models (like `flan-t5-large`, `bloomz`, and `mistral`) to explore scaling
- Switched to HuggingChat as a temporary solution for better results

 Why I Chose to Archive the Generator Logic:
- `flan-t5-base` struggled with long-form multi-day generation
- Token limitations and formatting issues caused frequent repetition
- Better models like Mixtral performed well but could not be fully integrated due to browser/API constraints

Key Takeaways:
- Learned the strengths and limitations of open-weight LLMs like `flan-t5`
- Practiced prompt engineering, real-time API debugging, and user experience design
- Applied professional GitHub practices (version control, Binder integration, error logging)
