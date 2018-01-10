# PythonCipher
A Vernam Cipher created with python 3.5.2. Uses a XOR function to encrypt a message with an encryption key. It contains a custom dictionary to accomodate the alphabet and custom punctuation. Encryption is unbreakable if key is used once.

# Setup
The GUI is what should be run through a python interpreter (ie. Pycharm) in order to get the actual program running. 
The GUI should be paired with the Functions file such that it can import the file and call upon the functions within. 

# Encrypt Operation
Upon running the GUI, a window pops up with several buttons and textboxes. To start off, the user must supply the message being encrypted.
This can be done either by filling in the message slot or choosing a text file with the Upload File button.

Next, a key must be provided, with the user either filling in a key of their own, or generating a key with the Generate Key button.
The key must be shorter than or equal in length to the message. 

Finally, clicking Finish will portray the encrypted text in a label, which will pop up in the window, or if a file is uploaded, it will generate a file with the encrypted message.

# Decrypt Operation
First, either insert encrypted text under Ciphertext or upload an encrypted file. 

Next, insert the key used to encrypt the message.

Click Finish to decrypt, which will either generate decrypted text in a label (if the text is inserted), or a file with decrypted text (if the file is uploaded). 

