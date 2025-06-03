# Password Analysis Report

This document provides a detailed analysis of six different passwords tested using three online tools: PasswordMeter, Password Monster, and NordPass Secure Password Checker.

---

## 🔐 Password 1: `abc123`

- **Tool Used:** [PasswordMeter](https://passwordmeter.com)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/abc123_passwordmeter.png)
- **Score:** 32%
- **Feedback:**
  - Too short (less than 8 characters)
  - Only lowercase and numbers used
  - No uppercase or symbols
  - Very easy to guess
- **Verdict:** ❌ Very Weak

---

## 🔐 Password 2: `Qwerty2025`

- **Tool Used:** [Password Monster](https://www.passwordmonster.com)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/qwerty2025_pass_monster.png)
- **Feedback:**
  - Contains predictable keyboard pattern (`Qwerty`)
  - Ends with common year (`2025`)
  - No symbols used
  - Estimated crack time: **1.08 seconds**
 - **Verdict:** ❌ Weak

---

## 🔐 Password 3: `P@ssw0rd!`

- **Tool Used:** [NordPass](https://nordpass.com/secure-password/)
- **Screenshot:**

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/passw0rd_nordpass.png)
- **Feedback:**
  - Common word (`password`) with substitutions
  - Still very predictable
  - Used in many breaches
  - Estimated crack time: seconds
- **Verdict:**  ❌ Weak

---

## 🔐 Password 4: `Lemonade22`

- **Tool Used:** [NordPass](https://nordpass.com/secure-password/)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/lemonade22_nordpass.png)
- **Feedback:**
  - Dictionary word + digits
  - Easily found in password databases
  - Vulnerable to dictionary attacks
  - Estimated crack time: under a minute
- **Verdict:** Moderate

---

## 🔐 Password 5: `3rT!8vKz@1`

- **Tool Used:** [NordPass](https://nordpass.com/secure-password/)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/strong2_nordpass.png)
- **Feedback:**
  - Strong use of uppercase, lowercase, numbers, and symbols
  - No dictionary words or patterns
  - Estimated crack time: billions of years
- **Verdict:** ✅ Strong

---

## 🔐 Password 6: `veRR9v88gE@ww5G`

- **Tool Used:** [NordPass](https://nordpass.com/secure-password/)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/strong1_nordpass.png)
- **Feedback:**
  - Excellent length (15 characters)
  - Randomized use of multiple character types
  - Extremely high entropy
  - Estimated crack time: trillions of years
- **Verdict:** ✅ Very Strong

---

## ✅ Best Practices for Creating Strong Passwords

Based on this evaluation and tool recommendations:

- Use 12 characters or more
- Mix uppercase, lowercase, numbers, and symbols
- Avoid dictionary words and personal info
- Don’t reuse the same password across accounts
- Use a password manager to generate and store unique passwords
- Enable Two-Factor Authentication (2FA) for extra protection

---

##  💡 Lessons from Evaluation

- Replacing letters with symbols (P@ssw0rd!) isn’t enough
- Dictionary + number combos (Lemonade22) are easy to guess
- Random strings are far more secure
- Length and randomness are key for strength

---

## Common Password Attack Methods

#### 1. Brute Force Attack

- Involves trying every possible combination of characters until the correct password is found.
- Time-consuming but effective against short or simple passwords.
- Example: abc123, Lemonade22 (low complexity, short length)

#### 2. Dictionary Attack

- Uses precompiled lists of common passwords and words (from leaks, patterns, or language dictionaries).
- Efficient at breaking passwords that use real words or simple modifications.
- Example: Qwerty2025, P@ssw0rd! (contain common words or predictable substitutions)

#### 3. Credential Stuffing

- Attackers use usernames and passwords leaked from one website to try logging into others.
- Highly effective when users reuse passwords across services.
- Example: Any reused password from data breaches.

#### 4. Pattern Matching Attack

- Identifies keyboard patterns (like Qwerty, 1234), date formats, or known structures (like Word+Year).
- Exploits human tendencies to create memorable patterns.
- Example: Qwerty2025 

---

## 🔐 How Password Complexity Affects Security

| Factor             | Effect on Security                                      |
|--------------------|---------------------------------------------------------|
| Length             | Increases crack time exponentially                      |
| Randomness         | Avoids prediction by attackers                          |
| Character Variety  | Adds entropy, making brute-force harder                 |
| Avoiding Patterns  | Protects against dictionary/predictive attack methods   |

🧠 A long, random, mixed-character password is **exponentially harder** to crack than a short or common one. Modern tools reward **entropy**, not just length.

---




