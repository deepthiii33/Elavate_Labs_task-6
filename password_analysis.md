# 📊 Password Analysis Report

This document contains a detailed analysis of six passwords tested using three different online tools: PasswordMeter, Password Monster, and NordPass Secure Password Checker.

---

## 🔐 Password 1: `abc123`

- **Tool Used:** [PasswordMeter](https://passwordmeter.com)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/abc123_passwordmeter.png)
- **Score:** 8%
- **Feedback:**
  - Extremely common and predictable
  - Too short
  - Contains only lowercase and digits
  - Easy to crack (within milliseconds)
- **Verdict:** ❌ Very Weak

---

## 🔐 Password 2: `Qwerty2025`

- **Tool Used:** [Password Monster](https://www.passwordmonster.com)
- **Screenshot:** `

![](https://github.com/deepthiii33/Elavate_Labs_task-6/blob/main/screenshots/qwerty2025_pass_monster.png)
- **Feedback:**
  - Includes keyboard pattern (`qwerty`)
  - Year (`2025`) is common
  - Easily guessable by dictionary and pattern attacks
  - Estimated crack time: less than 10 minutes
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
- **Verdict:** ⚠️ Moderate but Unsafe

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
- **Verdict:** ❌ Weak

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

- Use at least **12–16 characters**
- Combine **uppercase, lowercase, symbols, and digits**
- Avoid dictionary words, patterns, and common substitutions
- Never reuse passwords across sites
- Use a **password manager** to generate and store strong credentials
- Enable **2FA (Two-Factor Authentication)** wherever possible

---

## 💡 Tips Learned from Evaluation

- Even altered common words (`P@ssw0rd!`) are insecure
- Real-word + number formats (`Lemonade22`) are guessable
- Randomized passwords are significantly more secure
- Length + character variety = stronger password

---

## 🛡️ Common Password Attack Methods

| Type                 | Description                                               | Vulnerable Examples        |
|----------------------|-----------------------------------------------------------|-----------------------------|
| **Brute Force**       | Tries all possible combinations                          | `abc123`, `Lemonade22`      |
| **Dictionary Attack** | Uses known wordlists and patterns                        | `Qwerty2025`, `P@ssw0rd!`   |
| **Credential Stuffing** | Tests leaked credentials on other sites                | Any reused password         |
| **Pattern Matching**  | Guesses common formats or keyboard patterns              | `Qwerty2025`                |

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

## 📂 Files & References

- Screenshots available in: `/screenshots/`
- Summary report in: `README.md`
- Tools used:
  - [PasswordMeter](https://passwordmeter.com)
  - [Password Monster](https://www.passwordmonster.com)
  - [NordPass Secure Password Checker](https://nordpass.com/secure-password/)

---

## 👤 Author

*Your Name Here*  
[GitHub](https://github.com/your-username)
