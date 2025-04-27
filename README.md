# Automation Project

Ett projekt för att bygga en automationslösning med Python, Terraform och enkel webbfrontend.

## Struktur

- `backend/` – Python-skript och logik
- `infrastructure/` – Terraformkod för infrastruktur
- `webapp/` – HTML/CSS/JS-mallar och statiska filer
backend/
├── config.py              ← Environment settings
├── utils/                 ← Shared helper functions
├── models/                ← (If you use Pydantic / DB schemas)
└── .env                   ← Env variables for dev

## Setup

```bash
cd backend
pip install -r requirements.txt
```

Terraform:

```bash
cd infrastructure
terraform init
terraform apply
```

## TODO

- [ ] Lägg till CI/CD?
- [ ] Dockerisering?
