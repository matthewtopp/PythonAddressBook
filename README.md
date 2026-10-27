# addressBook
a ground up build of a PWA to learn the process and structure.

# Personal Address Book PWA

A simple Progressive Web App built with Python/Flask for managing contacts.

## Features

- View, add, edit, and delete contacts (name, phone, email)
- PWA support (manifest and service worker)
- Runs on GitHub Codespace or locally
- GNU GLP v3 license

## Setup and Run (local)

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py

## Install sqlite3 viewer if needed
'''bash this to install sqlite viewer to view the database...
- Only needs running on first creation of the codespace, and then only if oyu want ot look at the database to get a feel for its structure
- sudo apt-get update
- sudo apt-get install sqlite3 -y
