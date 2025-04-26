### 🛠️ FundiGpt SMS Bot (Africa's Talking Integration)

A smart conversational SMS bot that helps users learn about construction and building materials, built with Africa's Talking API and a Retrieval-Augmented Generation (RAG) system.
Designed to deliver simple, friendly, and language-flexible answers via SMS.
### 🌟 Features

    `📚 Construction Knowledge`: Educates users on construction processes, materials, and tools.

    `🛠️ Material Suggestions:` Guides users to choose the right building materials.

    `🌍 Language Adaptability:` Automatically replies in the user's language (Swahili or English).

    `🧠 RAG System Integration`: Intelligent retrieval of accurate answers from a custom knowledge base.

    `📲 SMS-based Access:` Works seamlessly through Africa’s Talking SMS API.

    `🛡️ Security Layer:` Protects sensitive interactions and configurations.

🚀 Tech Stack

   ` Python 3.10+ 🐍

    Africa's Talking API for SMS messaging

    FastAPI / Flask (for API endpoints)

    OpenAI and Gemini models for AI-powered answers

    Docker and docker-compose for containerization

    Thread-safe database (threads_db) for session management`

### 📦 Project Structure

```.
├── app
│   ├── Bot_Data/                 # Knowledge base text files
│   ├── config.py                  # Configuration settings
│   ├── decorators/                # Security decorators
│   ├── services/                  # AI service integrations and payment handlers
│   ├── utils/                     # WhatsApp and utility helpers
│   └── views.py                   # Main API routes and logic
├── docker-compose.yml             # Docker orchestration
├── Dockerfile                     # Docker image setup
├── example.env                    # Environment variables template
├── README.md                      # Project overview
├── requirements.txt               # Python dependencies
├── run.py                         # Application entry point
└── threads_db/                    # Conversation/session management
```
### 🔥 Getting Started

    Clone the repository

```
sh
git clone git@github.com:Jelius47/Africas_talkingFundi_sms.git
```
### Prepare environment variables

    Copy .env from example.env and fill in your API keys (Africa’s Talking, OpenAI/Gemini).

### Install dependencies

```
sh
pip install -r requirements.txt
```

### Run locally

```
sh
python run.py
```

#### Or using Docker:

    ```
    sh
    docker-compose up --build
    ```

    Start chatting via SMS! 📩

### 🛠️ Core Components
Component	Description
`Bot_Data/Fundi.txt`	Custom text knowledge base for construction topics.
`services/	`Integrations with AI models and payment handling services.
`decorators/`	Request validation and security layers.
`utils/`	Utilities for WhatsApp formatting and helper functions.--if you wil use whatsApp

### 🤝 Contributions

All contributions are welcome!
Feel free to open issues, submit feature requests, or create pull requests to improve the project.
📜 License

Licensed under the MIT License — see the LICENSE file for details.
💬 About the Developer -- `jeliusheneriko47@gmail.com`

### Built with ❤️ by Jelius
Focused on creating AI-powered tools for social impact, education, and business automation.
