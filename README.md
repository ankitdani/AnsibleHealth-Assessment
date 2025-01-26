# AnsibleHealth-Assessment

# AnsibleHealth-Assessment

## What does this repository do ?

This project automates the creation and management of Google Docs using Python. It allows users to:

- Authenticate using a Google service account.
- Create a new Google Document.
- Share the document with specified user.
- Upload and process Markdown file.
- Format and insert content into the document with styles and checkboxes.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required Python packages (see below)
- A Google Cloud service account JSON key
- Clone the repository:

  ```bash
  git clone https://github.com/ankitdani/AnsibleHealth-Assessment.git
  ```

## How to Run

1. **Install Required Dependencies:**

   ```bash
   pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
   ```

2. **Upload Service Account Key:**

   - Run the script and upload your Google service account JSON key when prompted.

3. **Authenticate and Create Document:**

   - The script will authenticate and generate a new Google Doc.
   - A link to the document will be displayed in the output.

4. **Share Document:**

   - The script will automatically share the document with the specified email.

5. **Upload Markdown File:**

   - When prompted, upload a Markdown (.md) file containing meeting notes.

6. **Process Content:**

   - The script will parse and insert content into the document with appropriate formatting.

7. **View Document:**
   - Open the provided document link to see the formatted content.

## Contact

For any questions or support, please reach out to `dani.s.ankit@gmail.com`.

---
