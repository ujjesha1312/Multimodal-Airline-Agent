# Multimodal Airline Agent  
An **AI-powered virtual assistant** for an airline called **FlightAI**.  
This assistant handles customer queries, provides **ticket prices**, generates **visual images of destinations**, and converts responses into **speech**.  
It demonstrates a **multimodal AI agent** using **OpenAI GPT-4, DALL·E, and TTS models**, built with **Python and Gradio**.  
## Features:  
- **Chatbot Support** – Polite, concise answers to customer queries  
- **Ticket Prices** – Fetch return ticket costs for cities like London, Paris, Tokyo, Berlin  
- **Image Generation** – AI-generated images of destinations via **DALL·E**  
- **Text-to-Speech** – Converts assistant responses into natural audio  
- **Gradio UI** – Interactive chat interface  

## Tech Stack:  
- **Python 3.9+**  
- **OpenAI GPT-4 (text + TTS)**  
- **OpenAI DALL·E (image generation)**  
- **Gradio** (UI framework)  
- **python-dotenv** (API key management)  

## Getting Started:

### 1.Clone the Repository  
```
git clone https://github.com/ujjesha1312/Multimodal-Airline-Agent.git
cd Multimodal-Airline-Agent
```
2. Create Virtual Environment
# Windows
```
python -m venv venv
venv\Scripts\activate
```
# macOS/Linux
```
python3 -m venv venv
source venv/bin/activate
```
3. Install Dependencies
```
pip install -r requirements.txt
```
4. Setup Environment Variables
Create a .env file in the project root:
```
OPENAI_API_KEY=your_openai_api_key_here
```
5. Run the App
```
python app.py
```
## Project Structure
```
Multimodal-Airline-Agent/
│
├── app.py             # Main application
├── requirements.txt   # Dependencies
├── .env.example       # Example environment variables
├── .gitignore         # Ignore files like .env, venv
└── README.md          # Project documentation
```
## Sample Output:
User: Hi, I want to book a ticket to London.
Assistant: A return ticket to London costs $799.

User: Can you show me London?
Assistant: Sure! Here’s an image of London.
(AI-generated picture of London appears in the Gradio app)

User: Can you say that in audio?
Assistant (Audio): “A return ticket to London costs $799.”

## Future Enhancements:
Add more destinations & real-time pricing
Export chat logs
Multilingual support
Integration with real airline APIs

-> Disclaimer:
This is a demo project for learning purposes.
Ticket prices and responses are not real.

