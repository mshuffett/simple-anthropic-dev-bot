# Simple Anthropic Development Bot

A lightweight chatbot for Anthropic API development and testing, designed to preserve Claude usage quota.

## Overview

This project provides a simple, efficient chatbot implementation for development and testing purposes. It's designed to be easy to set up and modify while minimizing API usage costs during development.

## Features

- Minimal but functional chat interface
- Straightforward Anthropic API integration
- Basic message handling
- Usage tracking
- Simple deployment process

## Quick Start

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up your Anthropic API key
4. Start the development server: `npm run dev`

## Project Structure

```
├── src/
│   ├── server/       # Backend server code
│   │   └── index.js
│   ├── client/       # Frontend code
│   │   ├── index.html
│   │   └── app.js
│   └── config.js     # Configuration
├── tests/
└── package.json
```

## Configuration

Create a `.env` file in the root directory with your Anthropic API key:

```env
ANTHROPIC_API_KEY=your_api_key_here
```

## Development

Run the development server:
```bash
npm run dev
```

## Testing

Run tests:
```bash
npm test
```

## License

MIT