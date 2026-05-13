---
vct: https://skatteverket.se/credentials/skv-address-credential
background_color: "#0b3a82"
text_color: "#ffffff"
---

# SkvAddressCredential

Credential som innehåller folkbokföringsadress för en person, inklusive namn och personnummer.

## Claims

- `personnummer` (string): Svenskt personnummer [mandatory] [sd=always]

- `fornamn` (string): Förnamn [mandatory] [sd=always]

- `efternamn` (string): Efternamn [mandatory] [sd=always]

- `adress` (string): Gatuadress [mandatory] [sd=always]

- `postnummer` (string): Postnummer [mandatory] [sd=always]

- `postort` (string): Postort [mandatory] [sd=always]
