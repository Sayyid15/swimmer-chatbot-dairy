# Welcome to the Swimming Performance App

## Overview
This app is built for swimmers. In the app, swimmers can log their swimming performances. It helps them see what they did before, so they can keep improving their swimming performance.

## Installation
1. Open your terminal in the code editor of your choice and clone the repo:
   ```bash
   git clone https://github.com/Sayyid15/prg08-opdracht1.git
   ```
2. Navigate to the server directory:
   ```bash
   cd server
   ```
3. Install all dependencies:
   ```bash
   npm install
   ```

## Environment
To make the app work, you need environment variables for the OpenAI API and the OpenWeather API.
Add them to your `.env` file using this structure:

```env
OPENAI_API_TYPE=...
OPENAI_API_VERSION=...
OPENAI_API_BASE=...
AZURE_OPENAI_API_KEY=...
DEPLOYMENT_NAME=...
ENGINE_NAME=...
INSTANCE_NAME=...
OPENWEATHER_API_KEY=...
```

## Usage
1. Start the server from the `server` directory:
   ```bash
   npm start
   ```
2. Open your browser and go to http://localhost:3000/ to check that the server is running.
3. To open the app, go to `index.html` in your files and double-click it.

Have fun logging your swimming performances!
