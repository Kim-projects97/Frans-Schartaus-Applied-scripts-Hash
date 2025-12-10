# MD5 Password Hash Generator

Detta projekt innehåller ett enkelt Python-script som:
- Genererar slumpmässiga numeriska lösenord med en fast längd.
- Beräknar MD5-hashvärdet för varje lösenord.
- Skriver ut endast hashvärdena i terminalen.

## Hur man kör scriptet
1. Se till att du har Python 3 installerat på din Linux-maskin.
2. Kör scriptet med:
   python3 md5-hasher.py

## Konfiguration
- Ändra konstanten PWD_LGT i koden för att styra längden på lösenorden.
- Ändra konstanten NO_PASS för att styra hur många lösenord som genereras.

## Viktig notering
MD5 är inte säkert för verklig användning i moderna system.
Detta script är endast avsett för utbildningssyfte.
För riktiga applikationer bör algoritmer som SHA-256, bcrypt eller Argon2 användas.
