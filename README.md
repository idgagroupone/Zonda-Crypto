# Dokumentacja dataLayer dla eventów na serwisie ZONDA CRYPTO

Prośba o wstawienie poniższych DataLayer na strony w obrębie serwisu Zonda Crypto.
___

## EVENTY W DOMENIE https://zondacrypto.com/

### 1) Kliknięcie w przycisk "Zaloguj" lub "Dołącz do naszego programu partnerskiego".
Prośba o wywołanie kodu na kliknięcie we wszystkie przyciski kierujące na stronę logowania https://auth.zondacrypto.exchange/.

![image](https://github.com/user-attachments/assets/9e9833ba-03f3-4102-9a09-dec29bc7d959)
![image](https://github.com/user-attachments/assets/8a845f8e-ecae-40f1-88b9-a542a17110f2)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "click_button_LOGIN",
  "click_text": "[NAZWA TESKTU]" // zmienna przekazująca kliknięty tekst, tu: "Zaloguj" lub "Dołącz do naszego programu partnerskiego"
});
```


### 2) Kliknięcie w przycisk "Zarejestruj" lub "Załóż darmowe konto" lub "Załóż konto za darmo" lub "Załóż konto ZEN" lub "ZAŁÓŻ KONTO NA ZONDACRYPTO".
Prośba o wywołanie kodu na kliknięcie we wszystkie przyciski kierujące na stronę rejestracji https://onboarding.zondacrypto.exchange/.

![image](https://github.com/user-attachments/assets/426e0978-7fef-4743-a434-4a69a5cb73ea)
![image](https://github.com/user-attachments/assets/c7af8841-35d1-4d9e-a5aa-a3e73a6a5c85)
![image](https://github.com/user-attachments/assets/b87869fd-7cde-4417-9e61-d1980c9f01af)
![image](https://github.com/user-attachments/assets/a0a12e17-1c07-49a6-8210-e5f0b8b04440)
![image](https://github.com/user-attachments/assets/d6b14437-99ed-4e6a-9d7d-343448c308ee)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "click_button_REGISTER",
  "click_text": "[NAZWA TESKTU]" // zmienna przekazująca kliknięty tekst, tu: "Zarejestruj" lub "Załóż darmowe konto" lub "Załóż konto za darmo" lub "Załóż konto ZEN" lub "ZAŁÓŻ KONTO NA ZONDACRYPTO"
});
```

## EVENTY W DOMENIE https://onboarding.zondacrypto.exchange/

### 1) Odsłona pierwszego kroku ścieżki rejestracji.
Prośba o wywołanie kodu na wyświetlenie pierwszego kroku ścieżki rejestracji.

![image](https://github.com/user-attachments/assets/b5f88c45-7bf9-434c-9308-95b964a6f530)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "REGISTER",
  "step": "[KROK ŚCIEŻKI]" // zmienna przekazująca krok na ścieżce rejestracji, tu: "1"
});
```

### 2) Kliknięcie w przycisk "Zarejestruj się".
Prośba o wywołanie kodu na kliknięcie w przycisk "Zarejestruj się" przekierowujące na drugi krok ścieżki.

![image](https://github.com/user-attachments/assets/596871b6-121d-4f73-8bed-b6a2930847a7)

``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "click_button_REGISTER",
  "click_text": "[NAZWA TESKTU]" // zmienna przekazująca kliknięty tekst, tu: "Zarejestruj się"
});
```


### 3) Odsłona drugiego kroku ścieżki rejestracji.
Prośba o wywołanie kodu na wyświetlenie drugiego kroku ścieżki rejestracji.

![image](https://github.com/user-attachments/assets/1901fc72-d6ec-44e7-afab-28e6d87e395f)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "REGISTER",
  "step": "[KROK ŚCIEŻKI]" // zmienna przekazująca krok na ścieżce rejestracji, tu: "2"
});
```

### 4) Odsłona trzeciego kroku ścieżki rejestracji.
Prośba o wywołanie kodu na wyświetlenie trzeciego kroku ścieżki rejestracji.

![image](https://github.com/user-attachments/assets/85336d7b-0226-4b88-8ec7-22934a99d895)

``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "REGISTER",
  "step": "[KROK ŚCIEŻKI]" // zmienna przekazująca krok na ścieżce rejestracji, tu: "3"
});
```

### 5) Odsłona czwartego kroku ścieżki rejestracji.
Prośba o wywołanie kodu na wyświetlenie czwartego kroku ścieżki rejestracji.

![image](https://github.com/user-attachments/assets/8ad0cfd1-cbe1-4d50-b47a-f830b70cec06)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "REGISTER",
  "step": "[KROK ŚCIEŻKI]" // zmienna przekazująca krok na ścieżce rejestracji, tu: "4"
});
```

### 6) Odsłona piątego kroku ścieżki rejestracji.
Prośba o wywołanie kodu na wyświetlenie piątego kroku ścieżki rejestracji.

![image](https://github.com/user-attachments/assets/b64d418f-c81e-4ae9-b9de-f5e994bff324)


``` javascript
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "REGISTER",
  "step": "[KROK ŚCIEŻKI]" // zmienna przekazująca krok na ścieżce rejestracji, tu: "5"
});
```

