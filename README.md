# Template Repo

Creates the ideal folder structure

```
your-project/
│
├── .git/                  # (auto-created by git init)
├── .aider.conf             # Your main aider settings
├── .aider_configs/         # (optional) extra Aider style configs
│    ├── backend.json
│    ├── frontend.json
│    ├── ai_agents.json
│    └── refactor.json
├── specs/                  # Your architect prompts
│    └── ...spec
│
├── chat.md                 # Aider chat log (saved automatically)
├── src/                    # Your main source code
│    └── ...code
│
├── tests/                  # Your test files
│    └── ...test
│
├── README.md               # Project overview
├── requirements.txt        # Python project dependencies (if Python)
├── .gitignore              # Ignore temp files, API keys, local data
└── notes/                  # (optional) architecture sketches, helper docs
     └── design.md
```
