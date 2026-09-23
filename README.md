# Google Gemini AI Assistant

A simple full-stack web project that connects a browser chat interface to Google's Gemini API.

## Features
- Clean chatbot interface
- Send questions to Gemini
- Displays Gemini responses
- Clear chat button
- Responsive design
- API key kept on the server in `.env`

## Requirements
- Node.js 20 or later
- A Gemini API key

## Run the project

1. Extract the ZIP file.
2. Open a terminal inside the project folder.
3. Run:

```bash
npm install
```

4. Create a file named `.env` by copying `.env.example`.
5. Put your Gemini API key in `.env`:

```text
GEMINI_API_KEY=YOUR_KEY_HERE
```

6. Start the project:

```bash
npm start
```

7. Open:

```text
http://localhost:3000
```

## Important
Never upload `.env` or your real API key to GitHub. The `.gitignore` file already excludes `.env`.

The project uses the official `@google/genai` JavaScript SDK.
