# TruffleHog — Secret Detection Guide

## Purpose

TruffleHog helps identify potential secrets in source code
and repositories.

## What It Can Detect

- API keys
- Access tokens
- Passwords
- Private keys
- Other credentials supported by its detectors

## Basic Usage

Scan a repository you own:

trufflehog git file:///path/to/your/repository

Replace the example path with the actual local path
to your authorized test repository.

## Safe Testing

1. Create a test repository.
2. Add sample code containing a fake credential.
3. Scan the repository.
4. Review the findings.
5. Record the results without publishing sensitive values.

## Important Safety Rules

- Never use someone else's credentials.
- Never attempt to authenticate with discovered keys.
- Never commit real credentials to this project.
- Redact secrets in reports.
- Report genuine exposures responsibly.
