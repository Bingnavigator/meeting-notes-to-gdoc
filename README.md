# meeting-notes-to-gdoc


# Markdown to Google Doc Converter (Colab)

## Description
This repository contains a Colab notebook and Python script that converts provided markdown meeting notes
into a formatted Google Doc using the Google Docs API.

## Dependencies
- google-api-python-client
- google-auth
- google-auth-httplib2
- google-auth-oauthlib

## Setup / Run
1. Open the Colab notebook under `notebook/meeting_notes_to_gdoc.ipynb`
2. Authenticate with Google when prompted
3. Run all cells
4. The script will create a Google Doc and print the link

## Code Structure
- `notebook/` — Jupyter Colab notebook
- `src/convert.py` — core conversion Python code
- `requirements.txt` — required package list
