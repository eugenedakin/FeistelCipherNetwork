# FeistelCipherNetwork
Feistel Cipher Network Cryptography

Horst Feistel was a German-Born physicist and Dan Coppersmith worked on cryptography while working at IBM around 1974. The Feistel network is also called a Feistel cipher that is used to encrypt and decrypt data. A quick explanation is that data is split into two pieces, and encryption occurs multiple times, which creates the encoded data. The number of iterations, and keys are different for each cipher that uses the Feistel network. Feistel Ciphers are used in two fish, padding schemes for certificates, key schedules, DES (Data Encryption Standard), and more. 

- Compatible OS's: All
- Xojo IDE: 2021 r1
- Xojo API: API 2
- Level: Advanced

Code for this example is in the following method: 1) FeistelCipher

Screen Grab:

![](https://github.com/eugenedakin/FeistelCipherNetwork/blob/main/FeistelScreenGrab.png)

Instructions:

Run the program in Xojo 2021 r1
 - Add Key#1 and Key#2 String in the top TextArea
- Enter your text in the Upper-Left TextArea Control
- Press Encrypt to use the Feistel Cipher Algorithm and the encoded text will appear in the control in the Upper-Right TextArea Control
- To decrypt the message, place the encoded message in the Lower-Left Control
- Press the Decrypt button
- The decrypted message will then appear in the Lower-Right Control
- The Method can be copied and pasted to use in your program. This is written in native Xojo code.

An article was written in xDev (xdevmag.com) Issue 20.1 (January/February 2022) that describes the Xojo code. This is a great journey using ciphers, or also known as encoding/decoding data.
