# ✅ Positive Products Test Cases

---

## Zameranie

Pokritie pozitívnych test case prípadov produktov, ich zobrazovanie, umiestnenie a pohybovanie sa  v aplikácii

## Obsah

- TC-PRODUCTS-001 - Zobrazenie zoznamu produktov po úspešnom loginu
- TC-PRODUCTS-002 - Detail produktu
- TC-PRODUCTS-003 - Návrat z detailu produktu na Products stránku
- TC-PRODUCTS-004 - Filtrovanie produktov
- TC-PRODUCTS-005 - Responzívne rozloženie mriežky

---

## ✅ TC-PRODUCTS-001 – Zobrazenie zoznamu produktov po úspešnom loginu

**Title:** Zobrazenie zoznamu produktov po úspešnom loginu  
**Section:** Products  
**Preconditions:** Používateľ je úspešne prihlásený  
**Test Data:** —  
**Expected Result:** Zobrazí sa stránka Products so zoznamom produktov  
**Actual Result:** Zobrazila sa stránka Products so zoznamom produktov  
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                                 |
| ---- | -------------------------------------- |
| 1    | Prihlás sa s validnými údajmi          |
| 2    | Skontroluj zobrazenie Products stránky |

---

## ✅ TC-PRODUCTS-002 – Detail produktu

**Title:** Detail produktu  
**Section:** Products  
**Preconditions:** Používateľ je na stránke Products  
**Test Data:** Sauce Labs Backpack  
**Expected Result:** Zobrazí sa detail produktu s popisom a cenou  
**Actual Result:** Zobrazil sa detail produktu s popisom a cenou  
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                     |
| ---- | -------------------------- |
| 1    | Klikni na názov produktu   |
| 2    | Skontroluj detail produktu |

---

## ✅ TC-PRODUCTS-003 – Návrat z detailu produktu na Products stránku

**Title:** Návrat z detailu produktu na Products stránku  
**Section:** Products  
**Preconditions:** Používateľ je v detaile produktu  
**Test Data:** —  
**Expected Result:** Používateľ sa vráti na Products stránku  
**Actual Result:** Používateľ sa úspešne vrátil na Products stránku   
**Defects:** —   
**Execution Status:** Passed     
**Steps:**  

| Step | Action                   |
| ---- | ------------------------ |
| 1    | Click “Back to Products” |

---

## ✅ TC-PRODUCTS-004 – Filtrovanie produktov

**Title:** Overiť, či je správne funguje filtrovanie produktov  
**Section:** Products  
**Preconditions:** Používateľ je na stránke Products  
**Test Data:** zmena filtra - Price(low to high)   
**Expected Result:** Po zmene filtra sa zmení poradie produktov podľa požadovaného poradia   
**Actual Result:** Po zmene filtra sa zmenilo poradie produktov podľa požadovaného poradia    
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                   |
| ---- | ------------------------ |
| 1    | Klikni na filter a vyber Price (low to high) |
| 2    | Skontroluj zoradenie produktov |

---

## ✅ TC-PRODUCTS-005 – Responzívna zmena veľkosti prehliadača

**Title:** Responzívna zmena veľkosti prehliadača  
**Section:** Products  
**Preconditions:** Používateľ je na stránke Products  
**Test Data:** —   
**Expected Result:** Po zmene veľkosti prehliadača, responzívne rozloženie sa prispôsobí veľkosti obrazovky  
**Actual Result:** Po zmene veľkosti prehliadača, mriežka sa responzívne prispôsobí formátu a produkty zostan  vycentrované na stred   
**Defects:** —  
**Execution Status:** Passed     
**Steps:**  

| Step | Action                   |
| ---- | ------------------------ |
| 1    | Zmena veľkosti prehliadača |
| 2    | Skontroluj umiestnenie produktov |
