# AI News Aggregator

A simple, personal-use AI news aggregator that fetches the latest AI news from the Perplexity Sonar Pro API. 

## Model Usage
It uses the Sonar API by Perplexity to fetch the latest news on AI innovations. Specifically, it leverages the sonar-pro model, which is designed for comprehensive web searches and information retrieval.

## Hackathon submission
Category: Most Fun (for me!) - because this is my first hackaton submission ever, enabled by Perplexity.

## Features

- Fetches AI news from the past 48 hours
- Secure backend implementation to protect API keys
- Debug logging to track request/response flow
- Dense, scannable news display
- Single-user, personal tool

## Setup

1. Clone this repository
2. Install dependencies with `npm install`
3. Create a `.env` file in the root directory with your Perplexity API key:
   ```
   PERPLEXITY_API_KEY=your_perplexity_api_key_here
   ```
4. Start the development server with `npm run start`

## Usage

1. Click the "Refresh News" button to fetch the latest AI news
2. View the debug log to see the request/response flow
3. Click on news headlines to read the full articles

## Technology Stack

- Development tools: Bolt.new & VS Code
- Frontend: React, TypeScript, Tailwind CSS
- Backend: Express.js
- API: Perplexity Sonar Pro

## Future Improvements

- Search domain filter for trusted AI news outlets
- Keyword search functionality
- Topic categorization
- Time window filtering
