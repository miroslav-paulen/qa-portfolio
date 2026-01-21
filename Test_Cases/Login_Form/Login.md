# ✅ Positive & ❌ Negative Login Test Cases

---

## Zameranie

Pokritie pozitívnych a negatívnych test case prípadov, validačných chybových hlášok a neplatných prihlasovacích údajov

## Obsah

- TC-LOGIN-001 - Login s validným username a validným password
- TC-LOGIN-002 - Login s validným username a neplatným password
- TC-LOGIN-003 - Login s validným username a nevyplneným password
- TC-LOGIN-004 - Login s prázdnym username a validným password
- TC-LOGIN-005 - Login s nevyplneným username a password

---

## ✅ TC-LOGIN-001 – Login s validným username a validným password

**Title:** Login s validným username a validným password  
**Section:** Login_Form  
**Preconditions:** Používateľ je na login stránke SauceDemo  
**Test Data:** standard_user / secret_sauce  
**Expected Result:** Používateľ je úspešne prihlásený a zobrazí sa stránka Products  
**Actual Result:** Používateľ bol úspešne prihlásený a zobrazila sa stránka Products   
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action                           | 
|------|----------------------------------|
| 1    | Zadaj username: standard_user    | 
| 2    | Zadaj password: secret_sauce    | 
| 3    | Click “Login”                    | 

---

## 🚫 TC-LOGIN-002 – Login s validným username a neplatným password

**Title:** Login s validným username a validným password  
**Section:** Login_Form  
**Preconditions:** Používateľ je na login stránke SauceDemo  
**Test Data:** standard_user / abcx123  
**Expected Result:** Používateľ zostane neprihlásený a zobrazí sa validačná chybová hláška  
**Actual Result:** Používateľ zostal neprihlásený a zobrazila sa validačná chybová hláška  
**Defects:** —   
**Execution Status:** Passed     
**Steps:** 

| Step | Action                           | 
|------|----------------------------------|
| 1    | Zadaj username: standard_user    | 
| 2    | Zadaj password: abcx123          | 
| 3    | Click “Login”                    | 

---

## 🚫 TC-LOGIN-003 – Login s validným username a nevyplneným password

**Title:** Login s validným username a nevyplneným password  
**Section:** Login_Form  
**Preconditions:** Používateľ je na login stránke SauceDemo  
**Test Data:** standard_user / (prázdne)  
**Expected Result:** Používateľ zostane neprihlásený a zobrazí sa validačná chybová hláška   
**Actual Result:** Používateľ zostal neprihlásený a zobrazila sa validačná chybová hláška  
**Defects:** —   
**Execution Status:** Passed     
**Steps:** 

| Step | Action                           | 
|------|----------------------------------|
| 1    | Zadaj username: standard_user    | 
| 2    | Zadaj password: (prázdne)         | 
| 3    | Click “Login”                    |

## 🚫 TC-LOGIN-004 – Login s prázdnym username a validným password

**Title:** Login s prázdnym username a validným password  
**Section:** Login_Form  
**Preconditions:** Používateľ je na login stránke SauceDemo  
**Test Data:** (prázdne)/secret_sauce  
**Expected Result:** Používateľ zostane neprihlásený a zobrazí sa validačná chybová hláška pre chýbajúci username  
**Actual Result:** Používateľ zostal neprihlásený a zobrazila sa validačná chybová hláška Zobrazila sa chybová hláška: "Username is required"  
**Defects:** —   
**Execution Status:** Passed     
**Steps:** 

| Step | Action                           | 
|------|----------------------------------|
| 1    | Zadaj username: (prázdne)        | 
| 2    | Zadaj password: secret_sauce    | 
| 3    | Click “Login”                    |

---

## 🚫 TC-LOGIN-005 – Login s prázdnym username a prázdnym password 

**Title:** Login s prázdnym username a prázdnym password  
**Section:** Login_Form  
**Preconditions:** Používateľ je na login stránke SauceDemo  
**Test Data:** (prázdne)/(prázdne)  
**Expected Result:** Používateľ zostane neprihlásený a zobrazí sa validačná chybová hláška  
**Actual Result:** Používateľ zostane neprihlásený a zobrazí sa validačná chybová hláška "Username is required"  
**Defects:** —   
**Execution Status:** Passed     
**Steps:** 

| Step | Action                           | 
|------|----------------------------------|
| 1    | Zadaj username: (prázdne)        | 
| 2    | Zadaj password: (prázdne)        | 
| 3    | Click “Login”                    |




