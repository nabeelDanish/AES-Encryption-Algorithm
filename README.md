# AES-Encryption-Algorithm
The AES Encryption Algorithm implemented in C++

## Installation

Use the given file and import it into your C++ project.

```C++
#include "functions.h"
```

## Usage

```C++
#include "functions.h"

unsigned char plaintext[16] = "Two One Nine Two";
unsigned char key[16] = "Thats my Kung Fu";

unsigned char ciphertext[16];
unsigned char newplaintext[16];

Encrypt(plaintext, key, ciphertext);
Decrypt(ciphertext, key, newplaintext);
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
