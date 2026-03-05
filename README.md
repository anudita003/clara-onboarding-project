# Clara Onboarding Automation Project

## Overview
This project simulates an automation pipeline that converts demo call data and onboarding updates into a structured AI voice agent configuration.

## Pipeline Stages

### Stage 1 – Demo Call Processing
- Extract key account details from demo call transcript
- Generate structured Account Memo JSON
- Create initial Retell agent configuration (v1)

### Stage 2 – Onboarding Update
- Update business rules based on onboarding call
- Generate revised Account Memo JSON (v2)
- Update Retell agent configuration
- Record all changes in changelog

## Folder Structure

outputs/
accounts/
account_001/
v1/
memo.json
agent_spec.json
v2/
memo.json
agent_spec.json
changes.md

## Key Features
- Version controlled agent configurations
- Clear separation between demo assumptions and onboarding updates
- Structured JSON outputs
- Change tracking using changelog

## Technologies Used
- Git & GitHub
- VS Code
- JSON for structured data

## Future Improvements
- Integrate automated transcript parsing
- Use n8n workflow automation
- Add batch processing for multiple accounts