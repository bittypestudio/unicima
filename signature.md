# Digital Signature Verification

This font is signed using **OpenPGP** for authenticity verification.

Public key file: `public-key.asc`  
Fingerprint: 

```bash
E4F7 C3C5 8A5B 5F3C 56FD 6627 EEC3 3971 A14E 4A51
```

---

## Verifying with Kleopatra (Windows GUI)

1. Install **Gpg4win** (includes Kleopatra).
2. Open the `.sig` file (e.g., `unicima-regular.ttf.sig`).
3. When prompted, select the original `.ttf` file (e.g., `unicima-regular.ttf`).
4. Import the public key: `public-key.asc`.
5. If prompted again, confirm the `.ttf` file.
6. If the signature is valid and the fingerprint matches, the font is authentic.

---

## Verifying via Command Line (GPG)

1. Import the public key
```bash
gpg --import public-key.asc
```
2. Verify the font file
```bash
gpg --verify unicima-regular.ttf.sig unicima-regular.ttf
```
3. Ensure the fingerprint shown matches:
4. If the fingerprint matches and the signature is valid, 
the file has not been tampered with and is verified to be original 
from the author.

---

## Getting Started with Unicima

For instructuions on the proper usage, formatting, and typographic guidelines 
for this font, please refer to the `usage_guide.pdf`.
