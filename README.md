# ComicCraft AI – Comic Story Creator using Gemini Models

ComicCraft AI is a web application that turns a user's story idea into a structured comic script using Google Gemini models.

## Features
- Generate comic titles, characters, plot summaries, and panel-by-panel dialogue/narration.
- Gemini API integration through a small Node.js/Express backend.
- Simple responsive frontend.
- API key stays on the server.
- Demo mode works without an API key.

## Requirements
- Node.js 18+
- A Gemini API key from Google AI Studio (for live generation)

## Run
1. Open a terminal in this folder.
2. Run `npm install`.
3. Copy `.env.example` to `.env`.
4. Put your Gemini API key in `GEMINI_API_KEY`.
5. Run `npm start`.
6. Open http://localhost:3000

## Demo mode
If no API key is configured, ComicCraft uses a built-in sample generator so the UI can be demonstrated.

## Suggested project extensions
- Generate comic panel images with an image-capable model.
- Add user accounts and saved comics.
- Export comics to PDF.
- Add speech/dialogue generation.
