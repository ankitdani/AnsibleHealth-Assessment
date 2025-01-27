# AnsibleHealth-Assessment

## Project Description

This project automates the creation and management of Google Docs using Python. It allows users to:

- Authenticate using a Google service account.
- Create a new Google Document.
- Share the document with specified users.
- Upload and process a Markdown file.
- Format and insert content into the document with styles and checkboxes.

## Setup Instructions

### Prerequisites

Ensure you have the following:

1. **Python 3.x Installed**
2. **Google Cloud Service Account**
   - Create a service account on Google Cloud and download the JSON key file.
3. **Clone this repository**:

   ```bash
   git clone https://github.com/ankitdani/AnsibleHealth-Assessment.git
   ```

4. **Required Python Packages**:

   - Install the required packages using the command below:

   ```bash
   pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
   ```

## Steps to Run in Google Colab

1. **Open Google Colab**

   - Navigate to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**

   - Upload the Python notebook (`.ipynb`) file from this repository.

3. **Install Dependencies**

   - Run the following command in the first cell of the notebook:

     ```bash
     pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
     ```

4. **Upload the Service Account JSON Key**

   - When prompted, upload the Google Cloud service account JSON key file.

5. **Run the Notebook**

   - Execute each cell sequentially to:
     - Authenticate with Google Docs API.
     - Create a new Google Document.
     - Share the document with specified email(s).
     - Upload and process a Markdown file.
     - Format and insert content into the document.

6. **View the Generated Document**
   - After processing, the notebook will display a link to the Google Doc. Open it to view the formatted content.

## Contact

For any questions or support, please reach out to **dani.s.ankit@gmail.com**.
