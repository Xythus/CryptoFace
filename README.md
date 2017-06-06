# CryptoFace
Avans SEC3 Week 3 Opdracht

### Libraries
- jQuery voor interactie met UI
- SJLC voor encryption/decryption (http://bitwiseshiftleft.github.io/sjcl/)
- Specifiek: http://bitwiseshiftleft.github.io/sjcl/doc/symbols/sjcl.json.html

### Encryptie
Encryptie met salt op basis van het ingevulde wachtwoord. Resultaat wordt BASE64-encoded en wordt in een JSON object opgeslagen in LocalStorage.
De LocalStorage slaat alles in een object op. De keys zijn de ingevulde namen bij elke encryptie. De values zijn de JSON objecten die SJLC teruggeeft.
