# Lab-93 CryptographyMethods
This class abstracts the handling of Python3's cryptography cryptography module.  The class provides one-way and two-way encryption methods for use with handling sensitive user credentials.

---

## Documentation
### [```CryptographyMethods.SHA256(secret)```](https://github.com/guyyatsu/CryptographyMethods/blob/6f8b67e360d991b6e432fb719ae8dad8b90b897e/src/CryptographyMethods/CryptographyMethods/CryptographyMethods.py#L21-L23)  
Simple one-way encryption for hashing secrets.

### [```CryptographyMethods.BuildKey(username, password)```](https://github.com/guyyatsu/CryptographyMethods/blob/b7cf4e510b25a6f4089fd979cc7b197406467241/src/CryptographyMethods/CryptographyMethods/CryptographyMethods.py#L26-L34)  
Create a base-64 encoded, url-safe, 32-bit key based on the SHA-256 hash
of a given username and password.

### [```CryptographyMethods.Encryption(phrase, target)```](https://github.com/guyyatsu/CryptographyMethods/blob/b7cf4e510b25a6f4089fd979cc7b197406467241/src/CryptographyMethods/CryptographyMethods/CryptographyMethods.py#L37-L39)  
Encrypt a target object using a custom key.

### [```CryptographyMethods.Decryption(phrase, target)```](https://github.com/guyyatsu/CryptographyMethods/blob/b7cf4e510b25a6f4089fd979cc7b197406467241/src/CryptographyMethods/CryptographyMethods/CryptographyMethods.py#L42-L44)  
Decrypt a target object with it's generated key.