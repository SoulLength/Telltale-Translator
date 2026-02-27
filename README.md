# Telltale

A real-time speech translator app. 

Telltale lets two people speak different languages to each other — it listens, translates, and reads the translation aloud.

## Repos

| | Repo |
|---|---|
| 🖥️ Frontend | https://github.com/SoulLength/telltale-fe |
| ⚙️ Backend | https://github.com/SoulLength/telltale-be |

## How it works

1. Speak or type in your language
2. The app translates using an OpenAI-compatible LLM
3. The translation is synthesized to speech via AWS Polly
4. The other person hears the result in their language

## Stack

- **Frontend** — Vanilla TypeScript, Vite, Web Speech API
- **Backend** — Node.js, Express, TypeScript
- **Translation** — OpenAI-compatible LLM
- **TTS** — AWS Polly
- **Deployment** — Docker

## License

GPL-3.0