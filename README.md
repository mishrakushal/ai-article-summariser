# AI Article Summariser

This repository contains the code for a web application that utilizes AI to summarize articles. It makes use of the RapidAI Summarizer API to generate concise summaries of web articles.

The website is hosted at [summarise-my-article.netlify.app](https://summarise-my-article.netlify.app/)


## Features

- Modern user interface with a **responsive design** and beautiful UI/UX, incorporating a touch of **glass morphism**.
- Connection to **OpenAI's GPT** model for **enhanced summarization** capabilities.
- Integration of **Redux Toolkit (RTK)** for efficient state management.
- Allows users to easily **copy the search URL** to the clipboard for sharing purposes.
- Implements browser local storage to **save search history**, providing **quick access to previous searches**.

## Tech Stack

- JavaScript
- ReactJS
- Tailwind CSS
- Vite

## Installation

1. Clone the repository:

```bash
git clone https://github.com/mishrakushal/ai-article-summariser.git
```

2. Navigate to the project directory:

```bash
cd ai-article-summariser
```

3. Install dependencies:

```bash
npm install
```

4. Run the development server:

```bash
npm run dev
```

5. Open your browser and visit `http://localhost:3000` to access the web application.

## Configuration

To use the RapidAI Summarizer API, you will need to obtain an API key from RapidAI. Once you have your API key, create a `.env` file in the root directory of the project and add the following line:

```
VITE_RAPID_API_ARTICLE_KEY=your_api_key_here
```

Make sure to replace `your_api_key_here` with your actual API key.

## Contributing

Contributions to this project are welcome. Feel free to open issues and submit pull requests to help improve the application.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).
