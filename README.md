# curriculum-generator

For a more detailed explanation on how this project was intended to work and how I failed, and what the do those weird sentences mean at the end of this README, check out the medium story I wrote about this project:

https://medium.com/@content_titanium_crow_768/curriculum-generator-and-how-i-failed-making-it-b6093689a5b7


Requirements
This project uses:

-requests
-getpass (for secure API key input)


How it works

1. User inputs a topic (e.g., "math") and number of days (e.g., 15)

2. A structured prompt is created

3.The prompt is sent to Hugging Faces google/flan-t5-large model

4.The response is parsed and displayed as a curriculum based on the number of the days the user selected

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

  Other stuff:
- Learned the strengths and limitations of open-weight LLMs like `flan-t5`
- Practiced prompt engineering, real-time API debugging, and user experience design
- Applied professional GitHub practices (version control, Binder integration, error logging)

  
Problem, Solution, Repeat: A Modern Tragedy
Curriculum of Eternal Confusion
Day After Day: The Problem That Wouldn’t Die
Groundhog Day: Math Edition
Identify the Problem: A Love Story
The Neverending Problem feat. The Solution Cameo
The Epic Saga of Problem and Solution: Volume 1 of 1,000
Dualities in Infinite Loop 2025
Symphony of Redundancy No. 1
Dialectic of Problem and Solution, Untitled
Repetition as Resolution: A Study in Persistence
Cycles of Inquiry and Futility
Minimalist Curriculum: Echoes of an Unfinished Thought
Epistemological Feedback: An Iterative Reflection on Pedagogical Cycles
The Recursive Mind: Explorations in Cognitive Redundancy
Didactic Echoes: A Manifesto of Problem-Solution Paradigms
Curriculum in Crisis: A Meditation on Instructional Entropy
The Sisyphus Curriculum: An Allegory of Perpetual Problem Framing
Ontological Loops: The Architecture of Unresolved Learning
Pedagogical Refrains in an Age of Algorithmic Disillusionment
An Iterative Ontology of Problem Spaces in Didactic Temporalities
Recursive Optimism: A Semiotic Investigation into AIs Failure to Converge
The Semiotics of Futility: An Inquiry into Algorithmic Misunderstanding
Fractured Learning Horizons: A Study in Machine Cognitive Decay
Postmodern Curricula: Deconstructing the Linear Progression of Knowledge Acquisition

