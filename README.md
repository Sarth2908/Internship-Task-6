# Internship-Task-6

| S.No | Password Example | Characteristics                          |
| ---- | ---------------- | ---------------------------------------- |
| 1    | `apple123`       | Lowercase + Numbers                      |
| 2    | `AppleTree!`     | Uppercase + Lowercase + Symbol           |
| 3    | `A1b2C3d4!`      | Mixed case + Numbers + Symbol            |
| 4    | `P@ssw0rd123!`   | Uppercase + Lowercase + Numbers + Symbol |
| 5    | `uH7$r@9T!eX2^`  | High Complexity (12+ chars, all types)   |


| Password        | Kaspersky Strength | Estimated Time to Crack (howsecureismypassword.net) | Feedback Summary                             |
| --------------- | ------------------ | --------------------------------------------------- | -------------------------------------------- |
| `apple123`      | Weak               | Few seconds                                         | Too short, no symbols, predictable           |
| `AppleTree!`    | Medium             | 15 minutes                                          | Better – added case variation and symbol     |
| `A1b2C3d4!`     | Strong             | Several months                                      | Good – strong mix of types                   |
| `P@ssw0rd123!`  | Strong             | 3 years                                             | Strong, but "password" pattern is risky      |
| `uH7$r@9T!eX2^` | Very Strong        | 100+ centuries                                      | Excellent – random, long, and highly complex |


Identified Best Practices for Creating Strong Passwords

    Use at least 12 characters
    Include all character types: uppercase, lowercase, numbers, symbols
    Avoid dictionary words or personal info
    Avoid repetition or sequences like 1234, aaaa, etc.
    Use unique passwords for each account
    Use a password manager to store complex passwords securely



Tips Learned From the Evaluation

    Even small improvements (like adding a symbol) significantly boost strength.
    Length is one of the most effective defenses.
    Randomness matters more than complexity patterns.
    Passwords like P@ssw0rd! may seem strong but are often in leaked datasets.
    Using passphrases like Rainy$Day@2025&Sky is both memorable and strong.


 Research on Common Password Attacks

    Brute Force Attack:
    Attempts every possible combination until the correct one is found. Slower but effective against short/simple passwords.

    Dictionary Attack:
    Uses precompiled lists of common passwords and variations. Very effective against passwords like password123, qwerty, or names.

    Credential Stuffing:
    Uses leaked passwords from one site to try on others (why reuse is dangerous).

    Phishing Attacks:
    Tricks users into revealing passwords via fake websites or emails.
