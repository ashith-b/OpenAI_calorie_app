# AI Calorie Counter App

## Overview

The AI Calorie Counter App is a GPT-4 powered Flask web application that estimates the number of calories in an image of a meal you upload. This app uses cutting-edge computer vision models to analyze meal images and predict their nutritional content, making it easier for users to track their calorie intake. The project leverages OpenAI's GPT-4 and integrates with a backend server to deliver predictions in real-time.

## Setup

1. Install dependencies:

```sh
$ pip install -r requirements.txt
```

2. Configure the environment

```sh
$ OPENAI_API_KEY="your_openai_api_key"
```

Add your OpenAI API key in the .env file like 

## How to Run

0. Rename the `.env.sample` file into `.env` and add your OpenAI API key

1. Start the server:

```sh
$ python3 server.py
```

2. Go to http://localhost:5000


## Terminal usage

You can also use it from the terminal:

```sh
$ python3 calorie_counter.py IMAGE_FILE
```
# OpenAI_calorie_app
