# Wake Energy NFC Contacts

This repository hosts lightweight contact-download pages for Wake Energy NFC business cards.

## Live URLs

- Jake Whinnery: `https://wake-energy.github.io/nfc-contacts/jake/`

## NFC setup

Write each live URL to its NFC tag as an **NDEF URL/URI record**. Do not write the vCard itself as a text or contact record.

## Adding a contact

Each person has a folder containing:

- `index.html` — redirects the phone to the contact file and provides a fallback button.
- `<name>.vcf` — the downloadable vCard.
