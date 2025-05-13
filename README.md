📝 PDF to Word Converter (OCR with EasyOCR + Flask)
This is a simple web application that converts scanned PDF documents into editable Word (.docx) files using Optical Character Recognition (OCR). It uses EasyOCR for text extraction and Flask for the web interface.

⚡️ Features

🖼 Convert scanned PDFs to Word documents

🧠 Uses EasyOCR (no need for Tesseract)

💡 Clean Bootstrap UI

🔁 Handles multiple pages

📥 One-click Word file download

📸 Demo
🚀 Tech Stack

Python 3.8+

Flask (backend)

EasyOCR (OCR engine)

pdf2image (PDF to image conversion)

python-docx (Word file generation)

Bootstrap (frontend styling)

📦 Installation

Clone the repository:


Create and activate a virtual environment:

Windows
python -m venv venv
venv\Scripts\activate

macOS/Linux
python3 -m venv venv
source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run the app:

python main.py

🖥 Access the app in your browser:

http://127.0.0.1:5000/

🗂 Project Structure

pdf2word-ocr-flask/
├── static/
│ └── style.css
├── templates/
│ └── index.html
├── uploads/
├── outputs/
├── main.py
├── requirements.txt
└── README.md

🧪 Sample Usage

Upload a scanned PDF

Click "Convert to Word"

Download your editable .docx file

🛠 Dependencies

easyocr

flask

pdf2image

python-docx

uuid

📌 Notes

No need to install Tesseract or Poppler on your system

EasyOCR will automatically install PyTorch as a backend

Tested on Windows 10, Python 3.10

📃 License

MIT License © 2025 Saif
