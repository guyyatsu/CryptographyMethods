# Lab-93 CryptographyMethods
This class abstracts the handling of Python3's cryptography cryptography module.  The class provides one-way and two-way encryption methods for use with handling sensitive user credentials.

---

## Documentation
### ```CryptographyMethods.SHA256(secret)```  
Simple one-way encryption for hashing secrets.

### ```CryptographyMethods.BuildKey(username, password)```  
Create a base-64 encoded, url-safe, 32-bit key based on the SHA-256 hash
of a given username and password.

### ```CryptographyMethods.Encryption(phrase, target)```  
Encrypt a target object using a custom key.

### ```CryptographyMethods.Decryption(phrase, target)```  
Decrypt a target object with it's generated key.