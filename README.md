# Password Strength Evaluation Report

# Tools Used:
- Dashline: https://www.dashlane.com/features/password-strength 
- PasswordMonster: https://www.passwordmonster.com/ 
- Browser: Google Chrome


# Passwords Tested & Results:

| Password              | Composition                               | Score (%) | Feedback                                                                 |
|-----------------------|-------------------------------------------|-----------|--------------------------------------------------------------------------|
| `password123`         | Lowercase + numbers                       | 25%       | Too common, no uppercase/symbols, easily guessable                       |
| `Pass123`             | Uppercase + lowercase + numbers           | 46%       | Better but too short, missing symbols                                    |
| `P@ssw0rd123`         | Upper + lower + numbers + symbol          | 73%       | Decent, length and complexity help                                       |
| `Xy@8gZ#9mT!2`        | Upper + lower + numbers + multiple symbols| 100%      | Very strong, meets all complexity metrics, excellent entropy             |
| `123456`              | Numbers only                              | 5%        | Extremely weak, highly predictable                                       |
| `Xxxx$Yyyyy2025!`   | Name variant + special characters + year  | 85%       | Strong, but may be predictable if X,Y info is known                 |


# Analysis:

*Best Performing Password:*
`Xy@8gZ#9mT!2`  
- Length: 12 characters  
- Uses uppercase, lowercase, numbers, and multiple symbols  
- Random and non-dictionary based  

*Weakest Password:*  
`123456`  
- Too short, numeric only, and commonly used in brute force attacks  


# Common Password Attacks:

1. **Brute Force Attack**  
   - Tries all possible combinations until the correct one is found  
   - Longer and more complex passwords take exponentially more time  

2. **Dictionary Attack**  
   - Uses precompiled lists of common passwords or words  
   - Passwords like `password123`, `qwerty`, or `welcome2024` are easily cracked  

3. **Credential Stuffing**  
   - Uses known username/password combinations from data breaches  
   - Reusing passwords makes users vulnerable  

---

# Best Practices for Creating Strong Passwords:

- Use *at least 12 characters*
- Combine *uppercase*, *lowercase*, *numbers*, and *symbols*
- Avoid *personal information* (e.g., name, birthdate)
- Use *random phrases* or passphrases (e.g., `Giraffe#Bakes9Muffins!`)
- Consider using a *password manager* to generate and store passwords
- *Don’t reuse* passwords across different sites
- Change passwords regularly, especially after a breach



# Tips Learned:

- Complexity (mix of character types) significantly increases password strength.
- Length is a critical factor — longer passwords are harder to crack.
- Using personal info makes passwords predictable.
- Randomness = stronger protection.
- Password managers can help avoid using weak or reused passwords.

# Conclusion:

This exercise demonstrates the importance of combining character variety and sufficient length to create a strong password. With the growing number of threats, password hygiene is essential for cybersecurity.
