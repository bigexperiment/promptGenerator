# Prompt Generator

A simple web application that helps you generate prompts by combining your input text, resume, and job description.

## Features

- Three input fields for:
  - Prompt
  - Resume
  - Job Description
- Automatic saving of all inputs and results to browser's local storage
- One-click copy functionality for the generated text
- Clean, modern interface
- No installation required - just open the HTML file in a browser

## How to Use

1. Open `index.html` in your web browser
2. Enter your text in the three fields:
   - Prompt: Enter your main prompt text
   - Resume: Paste your resume content
   - Job Description: Paste the job description
3. Click the "Generate" button to combine all inputs
4. Use the "Copy Result" button to copy the generated text to your clipboard

## Data Persistence

All your inputs and the generated result are automatically saved to your browser's local storage. This means:
- Your data will persist between page reloads
- You can close and reopen the browser to find your last inputs
- No data is sent to any server - everything is stored locally

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Uses browser's localStorage for data persistence
- No external dependencies
- Works offline
