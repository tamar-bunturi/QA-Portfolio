# Garden Services Marketplace - Testing Checklist

> ⚠️ NDA Notice: This project is covered by a Non-Disclosure Agreement.
> Company name and URLs are intentionally omitted.
> All checklists documented for portfolio purposes only.

---

## 1. User Registration & Login

- [ ] User can register with valid credentials
- [ ] User cannot register with an already existing email
- [ ] User cannot register with empty required fields
- [ ] Password field masks the input
- [ ] User can log in with valid credentials
- [ ] User cannot log in with invalid credentials
- [ ] Error message is displayed for incorrect login attempt
- [ ] User display name is shown exactly as entered during registration
- [ ] User display name is consistent across all language versions
- [ ] User can log out successfully

---

## 2. Service Request Flow (Customer)

- [ ] Customer can create a new service request
- [ ] All required fields are validated before submission
- [ ] Customer can select service category
- [ ] Customer can select service type 
- [ ] Customer can add location to the request
- [ ] Customer can add description to the request
- [ ] Customer can mark request as Urgent
- [ ] Submitted request appears in MY REQUESTS section
- [ ] Request submitted from guest mode is visible after registration
- [ ] Confirmation message is displayed after successful submission

---

## 3. Gardener Profile & Pricing

- [ ] Gardener profile card displays correctly
- [ ] Gardener name is fully visible on the profile card
- [ ] Gardener name does not overflow outside card boundaries
- [ ] Gardener price is always visible on the profile card
- [ ] Long names are truncated with "..." to protect layout
- [ ] Service price matches the defined default price in requirements
- [ ] Price is consistent across all language versions

---

## 4. Chat Functionality

- [ ] Customer can open chat with gardener
- [ ] Gardener can open chat with customer
- [ ] Messages are sent and received correctly
- [ ] Timestamps are displayed on messages
- [ ] Timestamp format is consistent between user view and admin panel
- [ ] Payment/order banner does not permanently block the chat interface
- [ ] Payment banner is collapsible or dismissible
- [ ] Chat is functional on mobile devices

---

## 5. Multilingual Support

- [ ] Application displays correctly in Georgian language
- [ ] Application displays correctly in English language
- [ ] Language switch works without page errors
- [ ] All UI elements are translated correctly
- [ ] User data (name, input fields) displays correctly in all languages
- [ ] Prices and numbers display correctly in all languages

---

## 6. General UI & Usability

- [ ] All buttons are functional and responsive
- [ ] All forms have proper validation messages
- [ ] Input fields have appropriate character limits
- [ ] Application is responsive on mobile devices
- [ ] Application works correctly on Chrome browser
- [ ] No raw error messages are displayed to end users
- [ ] Navigation between pages works correctly

## Testing Notes
> Checklists were created based on hands-on testing experience 
> on this platform. Items marked are derived from real test 
> scenarios including edge cases discovered during active testing cycles.
