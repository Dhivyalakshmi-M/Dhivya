🛍️ Smart Mall Billing System
A Python-based multi-shop billing system designed for malls, with a modern GUI using Tkinter, speech and QR recognition, MySQL integration, PDF invoice generation, and automated WhatsApp sharing.

🚀 Features
🔐 Login Authentication (per shop)

🏪 Multiple Shop Billing Pages

Shop 1: List View Billing

Shop 2: Speech-to-Text Item Entry

Shop 3: QR Code Scanning for Items

Shop 4: Manual Item Code Entry

👥 Customer Management

Auto-generated Customer IDs

Reward Points (earn & redeem)

🧾 PDF Invoice Generation

Includes GST, colorful design, and coupon codes

Automatic WhatsApp sharing of invoice

📦 Inventory Management

Item stock tracking and alerts

📊 Invoice & Report Page

Export day-wise summaries as CSV

🖼️ Stylish GUI with background images and centered layouts

🛠️ Technologies Used
Python 3

Tkinter (GUI)

PyMySQL (MySQL integration)

ReportLab (PDF generation)

SpeechRecognition & PyAudio (Shop 2)

OpenCV & Pyzbar (QR Code scanning - Shop 3)

pywhatkit (WhatsApp integration)

📁 Folder Structure
pgsql
Copy
Edit
📦 mall_billing_system
├── billing_shop1.py
├── billing_shop2.py
├── billing_shop3.py
├── billing_shop4.py
├── customer_page.py
├── invoice_page.py
├── login.py
├── main_mall.py
├── shop_selection.py
├── PyWhatKit_DB.txt
└── assets/ (backgrounds, QR codes, logos)
💽 Database
Requires MySQL with the following tables:

customers

products

invoices

bill_items

Auto ID generation and reward points tracking are built-in.

▶️ How to Run
Set up your MySQL database and update DB credentials in .py files.

Install requirements:

bash
Copy
Edit
pip install pymysql reportlab pywhatkit SpeechRecognition pyaudio opencv-python pyzbar
Run the application:

bash
Copy
Edit
python main_mall.py
📸 Screenshots
Add screenshots here of each billing page, customer page, invoice preview, etc.

📌 Notes
Make sure your system microphone and camera are working for Shop 2 and Shop 3.

WhatsApp Web must be logged in on the default browser to send messages.

📜 License
MIT License. See LICENSE for more details.
