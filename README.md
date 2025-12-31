# Markdown to Google Docs Converter

This project converts markdown meeting notes into a well-formatted Google Doc using the Google Docs API.  
It is designed to run in a Google Colab environment and demonstrates document creation, formatting, and API integration.

---

## Features

- Programmatic creation of Google Docs
- Markdown to Google Docs conversion
- Heading styles (H1, H2, H3)
- Bullet points with proper indentation
- Conversion of markdown checkboxes into Google Docs checklists
- Styled assignee mentions (e.g., `@name`)
- Robust handling of Google Docs API index constraints

## Prerequisites

- Google account
- Google Colab access
- Internet connection

---

## Required Dependencies

The following Python libraries are used:

- google-api-python-client
- google-auth
- google-auth-oauthlib
- google-auth-httplib2

These dependencies are installed automatically in the Colab notebook.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/markdown-to-google-docs.git

2. Run the ipynb script after authenticating your gmail account
