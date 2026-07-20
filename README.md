# sinux-ai
Sinux AI – Plateforme d'intelligence artificielle multimodale.
sinux-ai/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── frontend/              # Application Flutter
│   ├── lib/
│   ├── assets/
│   ├── pubspec.yaml
│   └── README.md
│
├── backend/               # API FastAPI
│   ├── app/
│   │   ├── main.py
│   │   ├── config.py
│   │   ├── database.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   ├── auth.py
│   │   ├── crud.py
│   │   └── services/
│   │       ├── llm_service.py
│   │       ├── memory_service.py
│   │       └── agent_service.py
│   └── requirements.txt
│
├── ai/
│   ├── models/
│   ├── prompts/
│   ├── agents/
│   └── memory/
│
├── database/
│   ├── migrations/
│   └── seeds/
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── sounds/
│
├── docs/
│   ├── architecture.md
│   ├── api.md
│   └── roadmap.md
│
└── deployment/
    ├── docker/
    ├── nginx/
    └── cloud/
