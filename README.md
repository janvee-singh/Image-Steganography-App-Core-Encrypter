# Image-Steganography-App-Core-Encrypter
Image Steganography is a method to store a string into a Picture, it does so by breaking the message into bits and replacing LSB with the string bits!

Encoding Algorithm:
Firstly, the secret message that is extracted is compressed as the contents in the compressed string will significantly hard to detect and read, furthermore it reduces the size of string.
Secondly, the compressed string is encrypted with the secret key.
Finally, encoding the encrypted message in the image. It uses LSB steganographic embedding to encode data into an image. Once the message is encoded the process stops.
