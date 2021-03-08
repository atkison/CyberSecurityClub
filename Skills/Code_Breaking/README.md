# Code-Breaking and Decoding 

Having the ability to interpret and understand data even if it is presented in a different or unknown format is extremely important to conducting cyber security examinations and to the general understanding of cyber security. A coded message is simply a message that has been changed in some way so as to hide its meaning from prying eyes. <br>

There are many different ways to write the same information. Below is a Lookup Table that shows decimal, hex, octal, and html encodings for characters. There are other ways to encode messages, such as binary or Base 64, but these will give a good idea of how encoding works. <br>

The message “Let the games begin!” could be encoded as follows: <br>
Dec: 76 101 116 32 116 104 101 32 103 97 109 101 115 32 98 101 103 105 110 33 <br>
Hx: 4C 65 74 20 74 68 65 20 67 61 6D 65 73 20 62 65 67 69 6E 21 <br>
Oct: 114 145 164 040 164 150 145 040 147 141 155 145 163 040 142 145 147 151 156 041 <br>
Html: &#76 &#101 &#116 &#32 &#116 &#104 &#101 &#32 &#103 &#97 &#109 &#101 &#115 &#32 &#98 &#101 &#103 &#105 &#110 &#33 <br>

<p align="center">
<img width="650px" height="400px" src="/00_Archive/images/asciiTable.png" alt="AsciiTable"/>
</p>

Being able to recognize different encoding schemes can be an asset when trying to find hidden information. However, encoding isn’t the most secure way to code a message. If a person recognizes the encoding scheme, all they have to do is go to the lookup table to decode it. <br>

Encryption is different from encoding as encoded messages do not require secret information to understand or interpret. Whereas, encryption involves altering the content of the message and must be decrypted using a secret key to reverse the process. Encryption is a more secure way to code a message. Encryption takes a key known by the encoder and uses that key to change the message. Then, only the people that know the key will be able to decrypt the message. The simplest form of encryption is a Caesar Cypher. For the example above, a Caesar Cypher shift +1 would shift each letter in the message up by one character. So, Let the games begin! would become Mfu uif hbnft cfhjo! More information on encryption: <br>

[How to Make Your Data Safe Using Cryptography](https://www.guru99.com/how-to-make-your-data-safe-using-cryptography.html) <br>
[Cryptography - KhanAcademy](https://www.khanacademy.org/computing/computer-science/cryptography) <br>
