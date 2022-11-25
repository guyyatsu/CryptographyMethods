# Lab-93 CryptographyMethods
This class abstracts the handling of Python3's cryptography cryptography module.  The class provides one-way and two-way encryption methods for use with handling sensitive user credentials.

---

## Documentation
### ```[CryptographyMethods.SHA256(secret)](https://github.com/guyyatsu/CryptographyMethods/blob/6f8b67e360d991b6e432fb719ae8dad8b90b897e/src/CryptographyMethods/CryptographyMethods/CryptographyMethods.py#L21-L23)```  
Simple one-way encryption for hashing secrets.

### ```CryptographyMethods.BuildKey(username, password)```  
Create a base-64 encoded, url-safe, 32-bit key based on the SHA-256 hash
of a given username and password.

### ```CryptographyMethods.Encryption(phrase, target)```  
Encrypt a target object using a custom key.

### ```CryptographyMethods.Decryption(phrase, target)```  
Decrypt a target object with it's generated key.