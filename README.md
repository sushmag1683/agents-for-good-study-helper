# Agents for Good – Study Helper Agent

An AI-powered study assistant developed as part of the Google AI Agents Intensive course on Kaggle. The project uses generative AI to help students revise study material through summaries, flashcards, and practice quizzes.

## Features

- **Text Summarization:** Generates concise study summaries from input notes.
- **Flashcard Generation:** Creates question-and-answer flashcards to support active recall.
- **Quiz Generation:** Produces practice questions based on study material.
- **Sequential Pipeline:** Runs summarization, flashcard generation, and quiz creation in sequence.
- **In-Memory History:** Stores input snippets and summaries during the current notebook session.
- **Interactive Input:** Provides an `ipywidgets` interface for entering study notes.
- **Export Results:** Saves pipeline output as JSON and flashcards as CSV.

## Technologies

- Python
- Google Generative AI Python SDK
- Gemini models
- Requests
- IPython Widgets
- JSON and CSV

## How It Works

1. Accepts study notes as text.
2. Uses a Gemini model to summarize the notes.
3. Generates flashcards from the summary.
4. Creates practice quiz questions from the summary.
5. Displays the results and optionally exports them to files.

## How to Run

1. Open the notebook in Kaggle.
2. Configure your Google API key using Kaggle Secrets.
3. Install the required dependencies.
4. Run the notebook cells in order.
5. Enter study notes and review the generated outputs.

**Security:** Never commit API keys or other credentials to GitHub.

## Project Status

Developed as a learning project using a notebook-based Python pipeline. Model availability, API access, and generated output quality depend on the configured Gemini model and credentials.

## Future Improvements

- Improve structured output validation for flashcards and quizzes.
- Add persistent storage for study history.
- Improve error handling and model selection.
- Package the workflow for easier use outside Kaggle.
