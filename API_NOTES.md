# Gemini API Notes

The backend reads `GEMINI_API_KEY` from `.env`, so the secret is not exposed in browser JavaScript.

The model is configurable with `GEMINI_MODEL`.

If the selected model name is unavailable for your API account, change `GEMINI_MODEL` to a currently supported Gemini model available to your account.

Never commit `.env` to GitHub.
