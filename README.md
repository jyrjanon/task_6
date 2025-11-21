# Task 6  **Create a Strong Password and Evaluate Its Strength**
---

## 🛠 Tools Used
- Online password strength checkers:
  - https://passwordmeter.com
---

## 🔑 Passwords Tested

### **1️⃣ Password: `jay123`**
- **Strength:** Very Weak  
- **Length:** 6  
- **Issues Found:**  
  - Only lowercase + numbers  
  - Too short  
  - Contains a common name  
- **Crack Time:** Instantly (brute force)

---

### **2️⃣ Password: `Jay@2005`**
- **Strength:** Medium  
- **Length:** 8  
- **Positive Points:**  
  - Uppercase + lowercase + numbers + symbol  
- **Issues Found:**  
  - Contains birth year (guessable)  
  - Too short for modern standards  
- **Crack Time:** Few hours (dictionary + brute force hybrid)

---

### **3️⃣ Password: `V!perX_90$shield`**
- **Strength:** Strong  
- **Length:** 16  
- **Positive Points:**  
  - Random words  
  - Symbols + numbers + uppercase  
  - High entropy  
- **Crack Time:** Millions of years (estimated)

---

### **4️⃣ Password: `Blue-Tiger-Eats-7-Mangoes`** (Passphrase)  
- **Strength:** Very Strong  
- **Length:** 27  
- **Positive Points:**  
  - Long passphrase  
  - Unpredictable  
  - Easy to remember  
  - Hard to brute force  
- **Crack Time:** Trillions of years

---

## 📊 Password Checker Results Summary

| Password | Score | Verdict | Crack Time |
|---------|-------|---------|------------|
| jay123 | 10% | Weak | Instantly |
| Jay@2005 | 45% | Medium | Hours |
| V!perX_90$shield | 85% | Strong | Millions of years |
| Blue-Tiger-Eats-7-Mangoes | 98% | Very Strong | Trillions of years |

---

## 🧠 What I Learned (According to PDF Tasks)  
(From page 1: create passwords, test them, note best practices) :contentReference[oaicite:1]{index=1}

### ✔ Strong Password Best Practices  
- Use **12 to 20+ characters**  
- Mix of **uppercase, lowercase, digits, symbols**  
- Avoid names, birthdays, and common words  
- Prefer **passphrases**  
- Use **unique passwords** for every website  
- Store in a **password manager**

### ✔ Why Password Complexity Matters  
- Longer passwords increase entropy  
- Each additional character massively increases brute-force time  
- Symbols/numbers raise unpredictability  
- Passphrases are easy for humans but hard for machines

---

## 🛡 Common Password Attacks (As required by PDF)  
(From interview question section on page 1) :contentReference[oaicite:2]{index=2}

### **1. Brute Force Attack**  
The attacker tries all possible combinations until the password is found.

### **2. Dictionary Attack**  
Attacker uses a pre-made list of common words + password patterns.

### **3. Social Engineering**  
Tricking the user into revealing passwords.

### **4. Password Spraying**  
Trying common passwords on multiple accounts.

---

## 📁 Repository Structure
```
task-6-password-strength/
│── README.md
├── password1.png
├── password2.png
├── password3.png
└── password4.png
```

---
