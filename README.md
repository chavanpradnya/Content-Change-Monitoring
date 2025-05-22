# Website Change Monitor

This is a simple Python script that monitors a website for changes by comparing the hash of its content over time.

## 🧠 How It Works

- The script fetches the HTML content of a specified website.
- It generates a hash of the content using SHA-224.
- Every 30 seconds, it re-fetches the content and compares the new hash with the previous one.
- If the hash has changed, it prints a message indicating the website content has changed.

## 📦 Requirements

- Python 3.x

## 🛠️ Usage

1. Clone the repository or copy the script to your local machine.

2. Run the script:

```bash
python monitor.py
