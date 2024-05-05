# LLM Agent for Python Coding Assistance

## Introduction
This project aims to develop a Large Language Model (LLM) based agent to assist in coding tasks for the Python programming language. The agent is designed to provide code suggestions, debugging tips, and documentation assistance based on user queries.

## Features
1. **Code Completion:** Generate code snippets based on partial input provided by the user.
2. **Debugging Assistance:** Suggest fixes for common syntax or logical errors in the user's code.
3. **Documentation Retrieval:** Provide explanations or documentation for specific Python functions or libraries upon user request.

## Requirements
- Python 3.x
- Tkinter (Python GUI library)
- Google Generative AI API
- IPython (for displaying Markdown)
- ctypes (for adjusting DPI)
- threading (for smooth user experience during API calls)
  
## Installation
1. Clone this repository to your local machine.
2. Install the required Python packages using pip:
3. Obtain a Google API key and replace `GOOGLE_API_KEY` in the code with your key.

## Usage
1. Run the Python script `llm_agent.py`.
2. Select a valid Python file (.py) using the "Open .py File" option.
3. Choose an option from the provided radio buttons:
- Code Completion
- Debugging Assistance
- Documentation Retrieval
4. Follow the prompts and input any necessary information.

## Testing
Basic testing has been conducted to ensure the agent's functionality:
- Unit tests for individual features.
- User testing to assess overall usability.

## Evaluation and Optimization
The agent's performance has been evaluated based on accuracy, response time, and relevance of output. Suggestions for optimization include:
- Optimizing API calls to reduce response time.
- Fine-tuning the model on a larger corpus of Python code.
- Implementing user feedback mechanisms for continuous improvement.

## Contributing
Contributions are welcome! Feel free to submit pull requests with improvements, bug fixes, or additional features.

## Acknowledgements
Special thanks to Google Generative AI for providing access to the Gemini-Pro model.

