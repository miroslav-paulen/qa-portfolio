# ✅ Positive Cart Test Cases

---

## Zameranie

Pokritie pozitívnych test case prípadov Košíka, jeho zobrazovanie, funkcie a umiestnenie

## Obsah

- TC-CART-001 - Prvok viditeľný pri načítaní stránky
- TC-CART-002 - Pridanie produktu do košíka  
- TC-CART-003 - Odobratie produktu z košíka  
- TC-CART-004 - Pridanie a odstránenie z detailu produktu  
- TC-CART-005 - Responzívne zobrazenie košíka  

---

## ✅ TC-CART-001 – Prvok viditeľný pri načítaní stránky

**Title:** Prvok košík viditeľný v pravo hore pri načítaní stránky  
**Section:** Cart  
**Preconditions:** Používateľ je na stránke Login  
**Test Data:** standard_user / secret_sauce    
**Expected Result:** Po prihlásení stránky Products je v pravom hornom rohu ikona košík  
**Actual Result:** Tlačidlo sa správne prepínalo  
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action                                                            |
| ---- | ------------------------------------------------------------------|
| 1    | Prihlásenie sa pomocou validných údajov                           |
| 2    | skontrolovať či sa v pravom hornom rohu nachádza ikona košík      |

---

## ✅ TC-Cart-002 – Pridanie produktu do košíka

**Title:** Zobrazenie zoznamu produktov po úspešnom loginu  
**Section:** Cart  
**Preconditions:** Používateľ je na stránke Products  
**Test Data:** Sauce Labs Backpack  
**Expected Result:** Produkt je pridaný do košíka  
**Actual Result:** Produkt bol pridaný do košíka  
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                           |
| ---- | -------------------------------- |
| 1    | Click “Add to cart” pri produkte |
| 2    | Skontroluj ikonu košíka          |

---

## ✅ TC-CART-003 – Odobratie produktu z košíka  

**Title:** Odobratie produktu z košíka  
**Section:** Cart  
**Preconditions:** Produkt je v košíku  
**Test Data:** Sauce Labs Backpack 
**Expected Result:** Produkt je odstránený z košíka  
**Actual Result:** Produkt bol odstránený z košíka  
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                  |
| ---- | ----------------------- |
| 1    | Click “Remove” v košíku |
| 2    | Skontroluj obsah košíka |

---

## ✅ TC-CART-004 – Pridanie a odstránenie produktu z detailu

**Title:** Pridanie a odstránenie produktu z detailu  
**Section:** Cart  
**Preconditions:** Používateľ je v detaile produktu  
**Test Data:** Sauce Labs Backpack  
**Expected Result:** Tlačidlo sa prepína Add / Remove  
**Actual Result:** Tlačidlo sa správne prepínalo  
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action              |
| ---- | ------------------- |
| 1    | Click “Add to cart” |
| 2    | Click “Remove”      |

---

## ✅ TC-CART-005 – Responzívne zobrazenie košíka

**Title:** Prvok košík responzívne reaguje na počet položiek  
**Section:** Cart   
**Preconditions:** Používateľ je na stránke Products  
**Test Data:** Sauce Labs Backpack, Sauce Labs Bike Light, Sauce Labs Onesie    
**Expected Result:** Po pridaní košík responzívne reaguje na počet pridaních produktov ktoré vyjadruje číslom  
**Actual Result:** Po pridaní košík responzívne reagoval na počet pridaních produktov ktoré vyjadril adekvátnim číslom   
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                                                            |
| ---- | ------------------------------------------------------------------|
| 1    | Pridáme do košíka Sauce Labs Backpack                             |
| 2    | Pridáme do košíka Sauce Labs Bike Light                           |
| 3    | Pridáme do košíka Sauce Labs Onesie                               |
| 4    | skontrolovať či sa pri ikone košíka zobrazuje správne číslo       |





