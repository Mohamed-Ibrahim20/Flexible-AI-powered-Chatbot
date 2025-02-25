#  Scalable and Customizable Chatbot Framework

This project is a flexible and scalable chatbot framework that integrates multiple AI models,. It can dynamically integrate multiple Google chatbot models and allows for the easy customization of prompts based on task requirements, such as a customer service interaction. The chatbot also features memory capabilities and a user-friendly interface for seamless interactions, making it adaptable for a variety of use cases.

## Features

- **Multi-Model Integration:** Dynamically selects the most suitable Google chatbot model based on the task.
- **Prompt Customization:** Easily change the prompt to suit different interaction goals or use cases.
- **Memory Capabilities:** Retains conversation context for more engaging and coherent interactions.
- **User Interface:** Simple and intuitive interface built with Gradio for easy deployment and testing.
- **Scalable Architecture:** Designed to be easily scalable and adaptable for future integrations.

## Prerequisites

- Python 3.x
- Required libraries: - `google-api-python-client`, `gradio` ,`langchain` ,`requests` ,`numpy`  ,`pandas` and `gemini-flash`
- Access to Google’s chatbot APIs and Gemini 2.0 Flash services

## Installation

1. **Clone the repository:**
    
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
    
2. **Install dependencies:**
    
    ```bash
    cd your-repo-name
    pip install -r requirements.txt
    ```
    
3. **Configure API keys and settings:**  
    Update the configuration file (`config.json` or similar) with your API credentials and preferred settings.

## Usage

Run the chatbot implementation:

```bash
python chatbot.py
```

Customize the behavior by modifying the configuration to select different Google chatbot models as per the task requirements.

## Project Structure

```
├── README.md
├── chatbot.py         # Main chatbot implementation file
├── config.json        # Configuration file for API keys and settings
├── requirements.txt   # List of required Python packages
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.


