# Ollama Coder

Ollama Coder is a lightweight, browser-based interface to generate fully functional web apps. By leveraging the simplicity of **AlpineJS** and **TailwindCSS**, this tool enables you to transform ideas into code instantly.

This project draws heavy inspiration from the incredible work behind [Cerebras Coder](https://cerebrascoder.com/). However, Ollama Coder takes a simpler and basic approach, focusing on providing a mostly self contained file for a drop-in browser-based experience using minimal dependencies like AlpineJS and TailwindCSS, for self hosted deployments. While it lacks advanced features and extensive capabilities, this project aims to offer an accessible and straightforward solution for turning ideas into code effortlessly, while keeping the clockwork complexity at a minimum.

## Features

- **Prompt-Based Code Generation:** Write a prompt, and let the app generate a complete website or web component.
- **Built-In Support for AlpineJS and TailwindCSS:** Uses CDNs for simplicity and minimal setup.
- **Live Preview and Code Editing:** Toggle between the generated content and source code directly in the browser.
- **Starter Prompts:** Test the tool with predefined suggestions.

## How It Works

1. **Write an Idea**: Type your app idea into the input box (e.g., "Build a to-do list").
2. **Generate Code**: Press the "Generate" button to get a fully functional app.
3. **View and Edit**: Switch between live content and raw HTML/CSS/JS for fine-tuning, or ask Ollama for further changes.


## Requirements

- A modern browser with JavaScript enabled.
- An API endpoint (default: `https://127.0.0.1:11434/api/chat`).

## Getting Started

1. Clone or download this repository.
2. Open the `index.html` file in your browser.
3. Start creating your apps instantly.

## Customization

You can tweak the following settings in the `x-data` block by passing them as query parameters:
- **ollama_host**: API host (default: `127.0.0.1`).
- **ollama_port**: API port (default: `11434`).
- **ollama_protocol**: API protocol (`http` or `https`, default: `http`).
- **ollama_api_path**: API path (default: `/api/chat`).
- **ollama_model**: Code generation model (default: `llama3.2:3b`).

## Contribution

Feel free to contribute by submitting issues, feature requests, or pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.