# **RSA Keys**

**`Credit`**: [What is RSA encryption and how does it work?](https://www.comparitech.com/blog/information-security/rsa-encryption/)

&nbsp;

Under RSA encryption, messages are encrypted with a code called a **public key**, which can be shared openly. Due to some distinct mathematical properies of the RSA algorithm, **once a message has been encrypted with the public key, it can only be decrypted by another key, known as the private key**. Each RSA user has a key pair consisting of their public and private keys. As the name suggests, the private key must be kept secret.

Public key encryption schemes differ from **symmetric-y encryption, where both the encryption and decryption process use the same key**. These differences make public key encryption like RSA useful for communicating in situations where there has been no opportunity to safely distribute keys beforehand.

RSA encryption is often used in **combination with other encryption schemes**, or for **digital signatures** which can prove the authenticity and integrity of a message. It is not generally used to encrypt entire messages or files, bc it is less efficient and more resource-heavy than symmetric-key encryption.

To make things more efficient, **a file will generally be encrypted with a symettric-key algorithm, and then the symmetric key will be encrypted with RSA encryption**. Under this process, only an entity that has access to the RSA private key will be able to decrypt the symmetric key.

Without being able to access the symmetric key, the **original file can not be decrypted**. This method can be used to keep messages and files secure, without taking too long or consuming too many computational resources.

&nbsp;

## **How does it work?**

A variety of different concepts are combined in order to make RSA all fit together. These include **trapdoor functions, generating primes, [Carmichael's totient function](https://en.wikipedia.org/wiki/Carmichael_function)** and the separate processes involved in **computing the public and private keys** used in the encyption and decryption processes. 

Another way RSA is secured is by the use of **padding to help revent a number of attacks**. Normally hackers could look at the format or structure of a message in order decrypt it. When a message is padded, **randomized data is added to hid the original formatting clues that could lead to an encrypted message being broken**.

&nbsp;

## **Some Pitfalls**

RSA keys **need to be implemented correctly and use a key that falls within the correct parameters. Keys need to be at least 1024 bits up to 4096 bits for higher threat models**. Also, it is important that padding schemes like OAEP are implemented. It is also important to use adequately sized primes otherwise hackers can pottentially crack RSA keys.
