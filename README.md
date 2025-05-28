# AI News Feed Generator

A web application that generates AI-powered news stories across various categories. The application uses multiple AI models (Gemini, Claude, ChatGPT) and can fetch real news from various sources (GNews, NewsAPI.org, The Guardian, NY Times).

## Features

- Generate news stories across 20 different categories
- Support for multiple AI models (Gemini, Claude, ChatGPT)
- Integration with multiple news APIs
- Text-to-speech capabilities using Google Cloud TTS
- Custom story input
- Local weather integration
- Copy to clipboard functionality
- Direct integration with NotebookLM

## Setup

1. Clone the repository
2. Open `index.html` in a web browser
3. Configure your API keys in the Settings panel:
   - AI Model API keys (Google Cloud, Anthropic, OpenAI)
   - News source API keys (GNews, NewsAPI.org, The Guardian, NY Times)
   - Optional: Configure weather location and TTS settings

## Usage

1. Select one or more news categories
2. Click "Generate Stories for Selected Categories"
3. View the generated stories in their respective tabs
4. Use the copy buttons to copy individual categories or all stories
5. Optionally generate audio versions of the stories

## Technologies Used

- HTML5
- CSS3 (with Tailwind CSS)
- JavaScript
- Various AI and News APIs

## License

MIT License 