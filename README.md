# AI Content Generation API

This is a simple **Node.js + Express API** that integrates with **Google Gemini** models to process **text, images, documents, and audio files**.  
It allows you to send text prompts, upload files, and get AI-generated responses such as summaries, captions, transcripts, or other custom outputs.

---

## Features

- **Text Generation**: Send text prompts and receive AI-generated responses.
- **Image Analysis**: Upload images and get captions, descriptions, or answers to queries.
- **Document Summarization**: Upload documents (PDF, DOCX, etc.) to extract or summarize content.
- **Audio Transcription**: Upload audio files to get transcripts or AI-generated analysis.
- **Safe Response Parsing**: Includes an `extractText` utility to safely handle Gemini API responses.

---

## Tech Stack

- **Node.js** + **Express** – Backend server
- **Multer** – File upload handling
- **@google/genai** – Gemini API SDK
- **dotenv** – Environment variable management

---

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/ai-content-api.git
   cd ai-content-api
   ```

2. **Install dependencies**:

    npm install

3. **Create a .env file and add your Gemini API key**:

    GEMINI_API_KEY=your_api_key_here

4. **Start the server**:

    npm start

5. **The API will run on http://localhost:3000** by default.
