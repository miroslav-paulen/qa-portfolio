# ✅ Positive Checkout Test Cases

---

## Zameranie

Pokritie pozitívnych a negatívnych test case prípadov Checkout, jeho zobrazovanie, funkcie a valídne polia  

## Obsah

- TC-CHECKOUT-001 - Prechod na Checkout
- TC-CHECKOUT-002 - Validácia povinných polí v Checkout  
- TC-CHECKOUT-003 - Vyplnenie Checkout formulára valídnymi údajmi  

---

## ✅ TC-CART-001 – Prechod na Checkout

**Title:** Prechod na Checkout  
**Section:** Checkout  
**Preconditions:** V košíku je aspoň 1 produkt  
**Test Data:** —  
**Expected Result:** Zobrazí sa Checkout: Your Information  
**Actual Result:** Zobrazil sa Checkout: Your Information formulár  
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action           |
| ---- | ---------------- |
| 1    | Otvor košík      |
| 2    | Click “Checkout” |

---

## ✅ TC-CHECKOUT-002 – Validácia povinných polí v Checkout

**Title:** Validácia povinných polí v Checkout  
**Section:** Checkout  
**Preconditions:** Používateľ je na Checkout: Your Information  
**Test Data:** —  
**Expected Result:** Zobrazí sa validačná chybová hláška  
**Actual Result:** Zobrazila sa chybová hláška o povinnom vyplnení krstného mena    
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action              |
| ---- | ------------------- |
| 1    | Nevyplň žiadne pole |
| 2    | Click “Continue”    |

---

## ✅ TC-CHECKOUT-003 – Vyplnenie Checkout formulára valídnymi údajmi

**Title:** Vyplnenie Checkout formulára valídnymi údajmi  
**Section:** Checkout  
**Preconditions:** Používateľ je na Checkout: Your Information  
**Test Data:** Ján. Janovič, 83208  
**Expected Result:** Zobrazí sa Checkout: Overview s informáciami o produktoch, platbe, doručení a cene 
**Actual Result:** Zobrazila sa Checkout: Overview s informáciami o produktoch, platbe, doručení a cene   
**Defects:** —  
**Execution Status:** Passed     
**Steps:** 

| Step | Action              |
| ---- | ------------------- |
| 1    | Vyplň valídne každné pole |
| 2    | Click “Continue”    |



