# RSA_sign_verify
Signs and verifies files using RSA public and private key cryptography.

## Basic usage
```python signer.py <KEY FILE NAME> <SIGNATURE FILE NAME> <INPUT FILE NAME> <MODE>```

example sign: ```python privKey.pem signer.py signature.sig input.txt sign```

example verify: ```python pubKey.pem signer.py signature.sig input.txt verify```
