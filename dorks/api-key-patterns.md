# ☠️ Secret Graveyard — GitHub Dorks

A collection of GitHub search queries for cybersecurity
research and defensive secret detection.

## 1. Python Environment Variables

extension:py os.getenv

Purpose: Find Python files that read environment variables.

## 2. API Documentation

filename:README.md API

Purpose: Find README files discussing API integration.

## 3. Configuration Examples

filename:config.example

Purpose: Find example configuration files.

## 4. Python Source Files

extension:py language:python

Purpose: Find Python source files for security reviews.

## 5. GitHub Workflow Files

path:.github/workflows

Purpose: Find workflow files that can be reviewed for
unsafe handling of credentials.

## 6. Environment File Examples

filename:.env.example

Purpose: Find example environment files.

## Defensive Research Rules

- Never use exposed credentials.
- Never publish actual API keys.
- Redact secrets in reports.
- Use authorized test environments.
- Report genuine exposures responsibly.
