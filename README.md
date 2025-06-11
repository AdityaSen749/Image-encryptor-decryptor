# Image-encryptor-decryptor
# imcrypt-main Web App

A web-based tool to encrypt and decrypt images using a custom XOR-based algorithm.  
**Developed by Aditya Sen**

---

## Features

- Encrypt any PNG/JPG image in your browser.
- Download the encrypted image and a short key.
- Decrypt your encrypted image using the key.
- No image or key is stored on the server after processing.

---![images_encrypted (1)](https://github.com/user-attachments/assets/c6eab899-b56e-4e42-bee0-5be94dffc903)
![ency img 2](https://github.com/user-attachments/assets/f2c57887-340f-45a8-a5a3-310769ecda76)
![ency img 1](https://github.com/user-attachments/assets/178c625b-0b79-452c-a262-5d19540e35bb)




## Getting Started

### 1. Open the folder image encryptor main in VS CODE :

Make sure all the files are present there that has been provided

### 2. Install dependencies

```sh
npm install
```

### 3. Start the web app

You can use the provided batch file (on Windows):

```sh
start-webapp.bat
```

Or manually:

```sh
node server.js
```

### 4. Open the app

Go to [http://localhost:3000/index.html](http://localhost:3000/index.html) in your browser.

---

## Usage

### Encrypt an Image

1. Click "Select an image to encrypt" and choose your image.
2. Click "Encrypt Image".
3. The encrypted image will be downloaded automatically.
4. Copy and save the generated key (you'll need it to decrypt).

### Decrypt an Image

1. Click "Select an image to decrypt" and choose your encrypted image.
2. Paste the key you saved earlier.
3. Click "Decrypt Image".
4. The decrypted image will be shown in the browser (right-click to save).

---

## Notes

- The encryption key is now short (256 bytes) for speed and usability.
- The server does **not** store your images or keys after processing.
- For best results, use PNG images.

---
