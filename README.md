# Digital-binder-agent
AI-powered Digital Binder Agent that automates weekly SharePoint binder updates by extracting data from local documents, validating required files, generating status reports, identifying missing information, and requesting approval before submission.


## project Structure:
digital-binder-agent/

├── docs/
│   ├── journal.md
│   ├── architecture.md
│
├── work_folder/
│
├── reports/
│
├── logs/
│
├── src/
│
│   ├── agents/
│   │
│   │   ├── extraction_agent.py
│   │   ├── validation_agent.py
│   │   ├── sharepoint_agent.py
│   │   └── report_agent.py
│
│   ├── readers/
│   │
│   │   ├── word_reader.py
│   │   ├── excel_reader.py
│
│   ├── models/
│   │
│   │   └── schemas.py
│
│   ├── main.py
│
│   └── config.py
│
├── tests/
│
├── .env
│
├── requirements.txt
│
└── README.md
