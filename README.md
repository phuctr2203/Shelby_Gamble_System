# Shelby Gamble System

This is the repository for LostD team for the Shelby Gamble System project. The project aims to create an AI-powered system that able to make prediction and inference about the market price and recommend user to buy or sell on a specific of time frame.

## Setup
To run locally, follow these steps:
```
conda create --name shelby-project python=3.11
conda activate shelby-project

pip install -r app/requirements-dev.txt

pre-commit install
pre-commit run --all-files
```

Some file you need to change and replace the info before running the code:
- Create a folder at the parent path, `.streamlit/secrets.toml` and `app/local.env`
- Check shared folder on GDrive for API KEY for specific key information like FinnHub or AWS.

## Running UI
To run the UI locally, run the following line: ```streamlit run app/main.py```
