# Resume Screening Application

This is an easy-to-use application that predicts the **job category** of a resume. Just follow the steps below to set it up and start using it—no coding knowledge required!

---

## What You Need to Get Started

1. A computer (Windows, macOS, or Linux).
2. **Python** installed on your computer (we’ll explain how to install it below).
3. An internet connection.

---

## Step 1: Install Python

1. Go to [python.org](https://www.python.org/downloads/).
2. Download the latest version of Python for your system.
3. During installation:
   - Check the box that says **"Add Python to PATH"** before clicking Install.
   - Complete the installation.

To verify Python is installed:
- Open **Command Prompt** (Windows) or **Terminal** (macOS/Linux).
- Type:
  ```bash
  python --version
  ```
  You should see a version number (e.g., `Python 3.10.5`).

---

## Step 2: Download the Application

1. Go to the project’s GitHub page.
2. Click the green **Code** button, then select **Download ZIP**.
3. Extract the ZIP file to a folder on your computer.

---

## Step 3: Open the Folder in Command Prompt or Terminal

1. Open **Command Prompt** (Windows) or **Terminal** (macOS/Linux).
2. Navigate to the folder where you extracted the files.
   - Example (Windows):
     ```bash
     cd C:\Users\YourName\Downloads\ResumeProject
     ```
   - Example (macOS/Linux):
     ```bash
     cd /Users/YourName/Downloads/ResumeProject
     ```

---

## Step 4: Set Up the Application

### Step 4.1: Create a Virtual Environment
This keeps all the files needed for the app in one place.
- **Windows**:
  ```bash
  python -m venv resume_env
  resume_env\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  python3 -m venv resume_env
  source resume_env/bin/activate
  ```

### Step 4.2: Install Required Tools
Install everything the app needs by running:
```bash
pip install -r requirements.txt
```

---

## Step 5: Start the Application

Run this command:
```bash
streamlit run app.py
```

After running, you’ll see a message like:
```
You can now view your Streamlit app in your browser.
Local URL: http://localhost:8501
```

---

## Step 6: Open the Application

1. Copy the link (`http://localhost:8501`) from the message in Step 5.
2. Paste it into your browser.
3. The app will open, and you can now use it.

---

## How to Use the Application

1. Click the **Browse files** button in the app.
2. Upload a resume in PDF, DOCX, or TXT format.
3. The app will display the predicted **job category**.

---

## Troubleshooting

- **I can’t find Command Prompt or Terminal:**
  - On Windows: Search for "Command Prompt" in the Start menu.
  - On macOS/Linux: Look for "Terminal" in your applications.
  
- **The app doesn’t open in my browser:** Copy the link (e.g., `http://localhost:8501`) and paste it into your browser manually.

- **I see an error while installing tools:** Make sure you ran:
  ```bash
  pip install -r requirements.txt
  ```

---

## What’s in the Folder?

- **app.py**: This runs the application.
- **requirements.txt**: Contains all the tools the app needs.
- **tfidf.pkl, clf.pkl, encoder.pkl**: These are the files the app uses to process resumes.

---

## No Coding Knowledge? No Problem!

Just follow these instructions step by step. Once everything is set up, you only need to upload resumes, and the app will do the rest for you!
