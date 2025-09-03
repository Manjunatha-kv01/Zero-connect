# Zero-connect
Connect the cutting edge technology from **A device** to **Cloud** to **B device**
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/0da701ba-ae82-48e1-92ac-9036fb479d06" />

Tranfer the Data  using the unique (UUID, timestamp-based ID, or random alphanumeric string) **QR Code** from the **Mobile A** to **Cloud** and Recive the **B mobile**
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/36cde4b3-c966-482c-98ea-08e7b2a643b9" />

**simple Data tranfer project with two main parts: Sender and Receiver.**

**Sender Side**

Allow the user to upload an image, text, video, or any file.

Generate a unique ID for the uploaded file.

Store the file temporarily on the server (e.g., using Python backend with Flask or FastAPI).

Create a QR code that contains the unique ID or download link to the file.

Display the generated QR code on the sender’s page.

**Receiver Side**

Provide a scanner page where the user can scan the QR code (using JavaScript QR code scanner in browser or upload QR code image).

Once scanned, decode the unique ID or link from the QR code.

Fetch the file from the server and allow the receiver to download/view it.

**Requirements**

Backend: Python (Flask or FastAPI) to handle file upload, storage, and retrieval.

QR Code Generation: Use qrcode or segno library in Python.

QR Code Scanning: Use JavaScript library like html5-qrcode on the receiver’s page.

Support for text, images, videos, and general file formats.

Simple UI with two buttons/pages → Send (upload & generate QR) and Receive (scan & download)
<img width="1024" height="1536" alt="Image" src="https://github.com/user-attachments/assets/59490269-1872-44bd-8876-87f673ab09ff" />

