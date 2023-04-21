# Caesar Cipher Decryption
This is a Jupyter Notebook for decrypting messages encrypted using the Caesar cipher. The Caesar cipher is a simple substitution cipher where each letter in the plaintext is shifted by a fixed number of positions in the alphabet.

## Usage
1. Clone the repository to your local machine using git clone.
```
git clone https://github.com/CalyGit/caesar-cipher-decryption.git
```
1. Navigate to the repository directory.
cd caesar-cipher-decryption
1. Open the caesar cipher decrypt.ipynb Jupyter Notebook in a Jupyter Notebook environment such as Jupyter Notebook or JupyterLab.

1. Follow the instructions in the notebook to enter the message to be decrypted, the password, and the number of shifts.

1. Run the notebook by clicking on the "Run" button or pressing "Shift + Enter". The decrypted message will be displayed in the notebook.

## Algorithm
The Caesar cipher decryption notebook uses a simple algorithm to decrypt messages:

1. It takes an input string, which represents the encrypted message, a password, and a number of shifts.
1. It checks if the password is valid.
1. If the password is valid, it iterates over each character in the input string.
1. For each character, it checks if it is an uppercase or lowercase letter.
1. If it is a letter, it shifts it back by the specified number of shifts, wrapping around the alphabet if necessary.
1. If it is not a letter, it leaves it unchanged.
1. It concatenates the decrypted characters to obtain the decrypted message.
1. It displays the decrypted message in the notebook.
##  Contributions
Contributions to this repository are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Acknowledgements
This project was inspired by the concept of the Caesar cipher and is based on the Python programming language.

## Disclaimer
This tool is for educational purposes only. Please ensure that you have the necessary permissions and legal rights before using it for any other purposes. The author of this repository is not responsible for any misuse or illegal activities. Use at your own risk.

