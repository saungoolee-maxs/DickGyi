# DickGyi Burmese JSON Decryptor

**DickGyi** is a standalone command-line tool that converts Burmese-character encrypted data into Base64, decodes and decrypts the AES ciphertext, and saves the result as valid JSON.

The tool also scans the decrypted configuration and prints all detected `vmess://` links are show in terminal and other supported V2Ray configurations are saved in json output.

## Usage

Decrypt directly from a URL and print the extracted configurations:

```bash
./DickGyi "https://raw.githubusercontent.com/foo/foo/encrypted.json"
```

Decrypt from a URL and save the output:

```bash
./DickGyi "https://raw.githubusercontent.com/foo/foo/encrypted.json" -o decrypted.json
```

Decrypt a locally saved encrypted file:

```bash
./DickGyi encrypted.json -o decrypted.json
```

## Author

**Call me PaPa --- D*ck Gyi.**
