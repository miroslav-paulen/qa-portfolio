# QA Manual Testing Portfolio 

Toto je **tréningové (junior) QA portfólio** zamerané na manuálne testovanie webovej aplikácie (demo e‑shop **SauceDemo**).
     Cieľom je ukázať **systematický prístup**, základné QA myslenie a čistú dokumentáciu.

## Čo tu nájdete
- **Test Cases**
  - SMOKE + REGRESSION TESTY PRE :
    - LOGIN
    - PRODUCTS
    - CART
    - CHECKOUT
    - V každom TC sú: Preconditions, Steps, Test Data, Expected/Actual result, Status.
 
## Testovacia stratégia
### 🔥 Smoke tests
Rýchla sada testov, ktorá overí, či build vôbec „drží pokope“ (login, products, cart, checkout).
Ak smoke test failne, ďalšie testovanie sa pozastaví.

### 🔁 Regression tests
Rozšírené scenáre (navigácia, dodatočné overenia, negatívne scenáre).

## Prostredie
- Browser: Chrome
- Test type: Manual UI testing

## Súbory
- `QA_Portfolio_SauceDemo_TestCases.xlsx` – kompletná sada test cases v jednom súbore.

## Poznámky
- Počas testovania neboli nájdené reprodukovateľné funkčné chyby (všetky vykonané TC sú PASS).


[Test_Cases/Login_Form/README.md](Test_Cases/Login_Form/README.md)
