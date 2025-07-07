# Task 1 – Web Server Using Python in Termux

This project is part of my NullClass Cybersecurity Internship.

## 🔧 Description
A simple web server set up using Python in Termux. It serves an `index.html` file locally and can be accessed via `http://localhost:8080`. This demonstrates a basic understanding of HTTP servers and Linux command-line usage in Termux.

## 📂 Files Included
- `index.html`: The HTML file served by the Python web server.
- `README.md`: This file, explaining the project.

## 🛠️ How to Run
1. Open Termux.
2. Run the following commands:

```bash
pkg update && pkg upgrade -y
pkg install python -y
mkdir mywebserver
cd mywebserver
# Copy index.html into this directory or create it using nano
python -m http.server 8080
```

3. Open your browser and visit:
```
http://localhost:8080
```

## 📸 Task Requirements
- Screenshot of the webpage at `localhost:8080`
- Screenshot of Termux showing the server running
- Upload this project folder to GitHub

## 🏷️ Tags
Cybersecurity • Termux • Python • Web Server • Internship Project
