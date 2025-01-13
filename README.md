# Image-to-Text with Groq

This project is a web application that allows users to upload images and generate text descriptions using the [Groq Vision API](https://console.groq.com/docs/vision).

## Features

- Upload images or paste from the clipboard
- Enter a prompt to describe the contents of the image
- Select a model and set the maximum response tokens
- View the generated text description
- View and manage uploaded images
- Responsive design with a dark theme

## Getting Started

### Prerequisites

- A Groq API key. You can obtain one from the [Groq Console](https://console.groq.com/keys).

### Usage

1. Open `index.html` in your web browser.
2. Enter your Groq API key.
3. Enter a prompt to describe the contents of the image.
4. Select a model and set the maximum response tokens.
5. Upload an image or paste an image from the clipboard.
6. Click the "Process Image-To-Text" button to generate the text description.
7. View the generated text description and manage uploaded images.

### Local Storage

The application saves the API key, prompt, tokens, and model selection in the browser's local storage for convenience.

### Dependencies

- No need to download. These are simply referenced in the html itself.
- [marked.js](https://github.com/markedjs/marked) - A library for parsing Markdown.
- [Sortable.js](https://github.com/SortableJS/Sortable) - A library for sortable lists.
