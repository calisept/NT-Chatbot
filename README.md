# NT-Chatbot

A demo chat bot to engage young children
## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Chat with configured vertex ai targeted young children
- Avatar selection 

## Prerequisite
Python ver 3.10 

Install gcloud CLI via the site https://cloud.google.com/sdk/docs/install 
- Window users are recommended to run the PowerShell command to install
- Login to team account, and use lean-ehm-test project

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/calisept/NT-Chatbot.git
    ```

2. **Navigate to the project directory** (skip if in root):
    ```bash
    cd NT Chatbot
    ```

3. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment**:
   - On Git Bash:
    ```bash
     cd venv/
     source ./Scripts/activate
    ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Authenticate with gcloud using the following command and login to an authenticated account:

```bash
gcloud auth application-default login
```
Run the Streamlit application locally using the following command:

```bash
streamlit run app.py