# Exhaustive Brute Force

## Scenario

Investigation involving multiple authentication attempts followed by a successful login, indicating a possible brute force attack and risk of account compromise.

---

## Summary

Multiple failed login attempts within a short period of time were detected for the user `joao.silva` from an external IP (`103.45.78.22`), originating from an unusual location for the system (**Russia**), followed by a successful login attempt at an atypical time (`03:12 AM`).

---

## Evidence

| Field | Value |
|---|---|
| User | `joao.silva` |
| Source IP | `103.45.78.22` |
| Location | Russia |
| Failed attempts | 20 in 3 minutes |
| Interval between attempts | A few seconds |
| Successful login after failures | Yes |
| Login time | `03:12 AM` |

---

## Analysis

- The high volume of login attempts within a short period is consistent with **brute force** behavior.
- The unusual geographic origin and atypical login time reinforce the suspicion of malicious activity.
- The successful login after multiple failed attempts significantly increases the risk of account compromise.

---

## Conclusion

Suspicious activity consistent with a brute force attack with possible account compromise.

---

## Recommended Actions

- Reset the user’s password
- Verify activities performed after the login
- Temporarily block the source IP
- Recommend the use of multi-factor authentication (**MFA**)
