# ☠️ Secret Graveyard: Secret Pattern Research

## 1. OpenAI API Credentials

Purpose:
Understand how OpenAI credentials can accidentally
be included in source code.

Common risk locations:
- Python scripts
- JavaScript files
- Configuration files
- Public Git history

Prevention:
Store credentials in environment variables.

## 2. Anthropic API Credentials

Purpose:
Understand risks associated with exposed AI service keys.

Common risk locations:
- Application configuration
- Development scripts
- Public repositories

Prevention:
Use environment variables and rotate exposed keys.

## 3. Azure Credentials

Purpose:
Learn how developers can accidentally expose
cloud application credentials.

Common risk locations:
- Application settings
- Deployment files
- CI/CD configuration

Prevention:
Use a secrets manager and restrict permissions.

## 4. General Secret Detection

Tools:
- TruffleHog
- GitHub Secret Scanning

## 5. Responsible Research

- Scan only authorized targets.
- Never use exposed credentials.
- Never publish secret values.
- Redact sensitive evidence.
- Report genuine exposures responsibly.
