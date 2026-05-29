# B2B AI Platform - Testing Checklist

> ⚠️ NDA Notice: This project is covered by a Non-Disclosure Agreement.
> Company name and URLs are intentionally omitted.
> All checklists documented for portfolio purposes only.

---
### App Overview
A B2B web platform that integrates AI-powered systems including
an AI search engine and an AI chat assistant. The platform is
designed for business users and focuses on intelligent content
discovery and conversational AI interactions.

## 1. AI Search Functionality

- [ ] Search bar is visible and accessible on the main page
- [ ] User can type a query in the search bar
- [ ] Search returns results for valid queries
- [ ] Search results are relevant to the entered query
- [ ] Search returns only results matching the specific model/version queried
- [ ] Irrelevant product models are not included in search results
- [ ] Search handles special characters without errors
- [ ] Search handles empty input appropriately
- [ ] Search results load within acceptable time
- [ ] No system errors are displayed during search

---

## 2. AI Chat Functionality

- [ ] AI Chat is accessible from the main interface
- [ ] User can start a new chat session
- [ ] AI responds to user messages correctly
- [ ] AI chat works correctly in Georgian language
- [ ] AI chat works correctly in English language
- [ ] AI only recommends products that are in stock
- [ ] AI does not contradict its own previous recommendations
- [ ] AI correctly handles product capacity queries (e.g. 5kg, 6kg)
- [ ] Out of stock message is displayed before user selects unavailable item
- [ ] AI chat redirects user appropriately when item is unavailable

---

## 3. Timestamp & Message Display

- [ ] Message timestamps are displayed in the user-facing chat
- [ ] Message timestamps are displayed in the admin panel
- [ ] Timestamp format is consistent between user view and admin panel
- [ ] Timestamps display correctly on mobile devices
- [ ] Timestamps display correctly on desktop

---

## 4. Admin Panel

- [ ] Admin panel is accessible to authorized users only
- [ ] Admin panel displays all active chat sessions
- [ ] Admin can view message history
- [ ] Timestamp format in admin panel matches user-facing chat
- [ ] Admin panel is functional on desktop browser

---

## 5. General UI & Usability

- [ ] All buttons are functional and responsive
- [ ] No raw error messages are displayed to end users
- [ ] Platform is responsive on mobile devices
- [ ] Platform works correctly on Chrome browser
- [ ] Language switch works without errors
- [ ] All UI elements display correctly in all supported languages

---

## Testing Notes
> Checklists were created based on hands-on testing experience
> on this platform. Items are derived from real test scenarios
> including edge cases and AI behavior inconsistencies discovered
> during active testing cycles. Special attention was given to
> AI recommendation accuracy and real-time stock validation behavior.
