# AzureOpenAI-ChatConsole
A simple console application for chatting with Azure OpenAI models. It uses Azure AI Project authentication to provide secure and seamless access to deployed LLMs. Designed for users who want a minimal, fast, and reliable way to test prompts and model outputs without a UI.

**## 🚀 Features**
- Interactive CLI chat interface  
- Uses your Azure OpenAI deployed model  
- Supports conversation history  
- Secure authentication via Azure `DefaultAzureCredential`  
- Clean, minimal project structure.

**📁 PROJECT STRUCTURE**
azure-chat-cli/
│
├── main.py
├── requirements.txt
├── README.md
├── .env.example
└── src/
    └── __init__.py

  **  🟦 requirements.txt**
python-dotenv
azure-identity
azure-ai-projects
openai

**🟦 .env.example**
# Rename this file to .env and fill in your Azure credentials

PROJECT_ENDPOINT=https://<your-project-name>.api.cognitive.microsoft.com
MODEL_DEPLOYMENT=<your-model-deployment-name>

**🟦 src/init.py**
# Package initializer (empty)

**Create a virtual environment**
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

**Install dependencies**
pip install -r requirements.txt

**Create .env**
Rename .env.example → .env, then fill in:

PROJECT_ENDPOINT=https://project56727676-resource.services.ai.azure.com/api/projects/project56727676
MODEL_DEPLOYMENT=gpt-4o

**▶️ Run the Chatbot**
python main.py


Type anything to chat with the AI.
Type quit to exit.

**🧠 Powered By**

Azure OpenAI

Azure Identity

Azure AI Projects

Python
