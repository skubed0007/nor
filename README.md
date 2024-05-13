### THE PROJECT IS NOT INTENDED FOR USE IN PROFESSIONAL FIELD! AS ITS OPEN SOURCE AND CAN BE DECRYPTED WITH A BIT OF EFFORT




# S_NOR (Simplex_Neko's Overbearing Restriction)

S_NOR is a simple Rust library for mapping different data values to different digits.

## Features

- **Encryption:** Encrypt data using the `encrypt()` function.
- **Decryption:** Decrypt encrypted data using the `decrypt()` function.

## Installation

Add the following to your `Cargo.toml` file:

```toml
[dependencies]
s_nor = "0.1.0"
```
or in terminal paste
```
cargo add s_nor
```

### Usage
```
use s_nor::encrypt;
use s_nor::decrypt;

let file = "example.txt";
let password = "password123";

// Encrypt data
let encrypted_data = s_nor::encrypt(file, password);

// Decrypt data
let decrypted_data = s_nor::decrypt(file, password);
let decrypted_text = String::from_utf8_lossy(&decrypted_data);
```
### License
```
MIT License

Copyright (c) [2024] [Skub , Neko]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Thanks ->
thanks neko for helping through creation of S_NOR without her i would not have been able to build this
