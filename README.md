# Trinethra — Supervisor Feedback Analyzer
DeepThought Software Developer Internship Assignment

## What is this?
A web app that analyzes supervisor transcripts using AI and produces a structured Fellow performance report.

## Setup Instructions
1. Download and install Ollama from ollama.com
2. Open Command Prompt and run: ollama pull llama3.2
3. Start Ollama: ollama serve
4. Open index.html in your browser
5. Paste a supervisor transcript and click Run Analysis

## Ollama Model Used
- Model: llama3.2
- Reason: Small enough to run on most laptops, good language understanding

## Architecture
- Frontend: Pure HTML, CSS, JavaScript (single file)
- AI: Ollama running locally on port 11434
- No backend needed — browser calls Ollama API directly

## Design Challenges Tackled
1. Structured Output Reliability — cleaned and parsed JSON from LLM response
2. Showing Uncertainty — UI designed so intern treats output as draft not verdict

## What I Would Improve
- Add side-by-side view of transcript and analysis
- Highlight exact quotes in transcript when clicked
- Add confidence score for each evidence item

## Test Transcripts
Use the sample transcripts from sample-transcripts.json to test the app
