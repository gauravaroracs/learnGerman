# German Vocab Logger (n8n)

A personal n8n workflow that captures new German vocabulary, enriches it, and logs it for study.

## Why I built this
I wanted a frictionless way to collect German vocabulary on the go, enrich each entry with context, and keep a clean study log without manual copy/paste.

## What it does
- Captures words/phrases (Telegram trigger or manual run)
- Normalizes and enriches entries (definition, examples, metadata)
- Logs the result in a structured store (e.g., Google Sheets)

## Workflow export
- Final workflow JSON: `workflows/german-vocab-logger-final.json`
- Drafts and iterations: `workflows/archive/`

## Demo
- Screenshots: `screenshots/` (add your workflow canvas + sample output)
- Optional: short video/GIF link

## How to import into n8n
1. Open n8n.
2. Go to **Workflows** -> **Import**.
3. Select `workflows/german-vocab-logger-final.json`.
4. Reconnect credentials for any nodes that require them.

## Setup notes
- This export includes credential references but no secrets.
- Re-authenticate your own credentials in n8n (Telegram, Google Sheets, etc.).
- Update any environment variables or node parameters to match your environment.

## Tech
- n8n
- Telegram Bot API
- Google Sheets

## Roadmap (optional)
- Add spaced repetition reminders
- Add pronunciation audio via TTS
- Push entries to Anki

## Project structure
- `workflows/` n8n workflow JSON exports
- `screenshots/` workflow and output screenshots
