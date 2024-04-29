# Streamlit Groq Chatbot

## Introduction

This repository contains a Streamlit app that allows you to use a Groq chatbot.

## Usage

To use the Streamlit Groq Chatbot, follow these steps:

1. Set up the development environment by launching DevContainers.
2. Create a new file named `.env` based on the provided `.env.sample` file.
3. Generate a Groq API key and paste it into the `.env` file.<br>
    <https://console.groq.com/keys>
4. Run the following command to start the Streamlit app:
    ```bash
    streamlit run app.py --server.address localhost
    ```

Please note that starting from a certain point, you need to include the `--server.address localhost` flag when running the Streamlit app using the `streamlit run app.py` command.
