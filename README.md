# -Tutoring-Session-Summarization-System
This project implements a complete pipeline to process tutoring session transcripts, store session data in a SQLite database, and generate warm, parent-friendly summaries using OpenAI's GPT-4 model.

# Tutoring Session Summarization System

## Overview

This project implements a complete pipeline to process tutoring session transcripts, store session data in a SQLite database, and generate warm, parent-friendly summaries using OpenAI's GPT-4 model.

It includes:

- A relational database schema for Students, Tutors, Sessions, and Summaries.
- Python scripts to parse transcripts, manage database records, and call the OpenAI API for summary generation.
- Example generated summaries and usage instructions.

## Features

- Automatically adds new students and tutors.
- Stores session transcripts with timestamps.
- Retrieves historical summaries for contextual GPT prompt construction.
- Generates consistent and professional session summaries.
- Easily extensible for web dashboards or analytics.

## Getting Started

### Prerequisites

- Python 3.8+
- OpenAI Python SDK (`openai` or compatible library)
- SQLite (bundled with Python)
- Your OpenAI API key set as an environment variable: `OPENAI_API_KEY`

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/tutoring-summary.git
   cd tutoring-summary
