# BUG-001 - User display name shown in uppercase despite lowercase registration input

| Field | Details |
|---|---|
| **Module** | UI / Welcome Message |
| **Category** | UI |
| **Severity** | Low |
| **Priority** | Low |
| **Reproducibility** | 100% |

---

## Preconditions
User is registered in the system with lowercase letters

---

## Steps to Reproduce
1. Open the web application
2. Log in to the system
3. Ensure the account is registered with a lowercase name as a customer
4. Observe the welcome message

---

## Expected Result
The system should display the user's name exactly as it was entered during registration, preserving the original letter casing (lowercase/uppercase)

---

## Actual Result
The system displays the user's name in uppercase letters in the welcome message, even though the account is registered using lowercase letters

## Impact
This bug affects user trust and brand perception. When a user sees their name displayed incorrectly, it creates a feeling that the platform does not handle personal data carefully. For a service marketplace where trust between customer and provider is essential, this type of UI inconsistency can negatively affect user retention and first impressions.
