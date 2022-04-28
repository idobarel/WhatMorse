# WhatMorse

_A python package that allows you to encrypt and decrypt morse code._

# How To Use

A simple code that allows you to encrypte and decrypte a _message_:

```python
from WhatMorse.whatmorse import All # Import

handler = All() # set an object
msg = input("[+] Message >> ")
opt = int(input("[1] Encrypt\n[2] Decrypt\n[+] Enter Index >> "))
if opt == 1:
    x = handler.encrypt(msg) # encryption
    print(f"output:\n{x}")
else:
    x = handler.decrypt(msg) # decryption
    print(f"output:\n{x}")
```

# Pay Attention ❤️

_This program is on early release, so it's really small._

_Have A Good Day!_
