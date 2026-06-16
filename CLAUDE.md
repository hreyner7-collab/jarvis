# JARVIS — Voice AI Assistant (Fully Local & Free)

## Overview
JARVIS (Just A Rather Very Intelligent System) is a voice-first AI assistant. Everything runs locally and free — no paid API keys needed!

## Quick Start
1. Install Ollama from ollama.com
2. Pull a model: `ollama pull llama3.2:3b`
3. Run `pip install -r requirements.txt`
4. Run `cd frontend && npm install`
5. Generate SSL certs: use Python or OpenSSL
6. Run backend: `python server.py`
7. Run frontend: `cd frontend && npm run dev`
8. Open http://localhost:5173

## Architecture
- **Backend**: FastAPI + Python
- **Frontend**: Vite + TypeScript + Three.js (audio-reactive orb)
- **LLM**: Ollama (local, runs llama3.2:3b)
- **TTS**: edge-tts (free, Microsoft Edge TTS)
- **Speech**: Web Speech API (browser built-in)

## No API Keys Required
- LLM: Ollama at localhost:11434 (free, local)
- TTS: edge-tts (free, no API key)
- Speech recognition: browser built-in (free)
