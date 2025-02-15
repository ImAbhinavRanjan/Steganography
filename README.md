# Steganography using Google Colab

This project demonstrates a simple steganography tool implemented in Python using Google Colab. Steganography is the art of hiding messages or information within another medium, such as images.

## Features
- **Message Embedding**: Hides a secret message inside an image by modifying pixel values.
- **Message Extraction**: Retrieves the hidden message from an image.
- **Passcode Security**: Requires a passcode for encrypting and decrypting messages.

### How the Project Uses Caesar Cipher for Enhanced Security

This project incorporates the Caesar cipher to add an additional layer of security to traditional steganography. Instead of directly embedding the plain text message into the image, the message undergoes a Caesar cipher encryption process. The cipher shifts the alphabets in the message by a key derived from the ASCII value of the provided passcode. Non-alphabetic characters remain unchanged, ensuring minimal distortion while enhancing security. This approach ensures that even if the steganography is compromised, the embedded message remains encrypted and protected.

- Ensure the image has sufficient size to store the entire message.
- The embedded message is secured using a passcode.

## Usage

### 1. Run the Notebook in Google Colab

1. Open the repository:
    ```
    https://github.com/ImAbhinavRanjan/Steganography
    ```
2. Open the `steg.ipynb` file in Google Colab:
    - Click on the notebook file and select `Open in Colab`.
3. Follow the instructions in the notebook to embed or extract a message.

### 2. Embedding a Message

- Provide the path to the image.
- Enter the message you want to hide.
- Enter a passcode to encrypt the message.
- The notebook will save the image with the hidden message.

### 3. Extracting a Message

- Provide the path to the image containing the hidden message.
- Enter the correct passcode used during embedding.
- The notebook will display the decrypted message.





