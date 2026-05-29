# AI Document Editor - Testing Checklist

> ⚠️ NDA Notice: This project is covered by a Non-Disclosure Agreement.
> Company name and URLs are intentionally omitted.
> All checklists documented for portfolio purposes only.

---

## 1. User Authentication

- [ ] User can register and log in successfully
- [ ] User cannot access the editor without authentication
- [ ] Session is maintained correctly during editing
- [ ] User can log out successfully

---

## 2. Document Management

- [ ] User can create a new Manuscript file
- [ ] User can create a new folder
- [ ] User can rename a file
- [ ] User can rename a folder
- [ ] User can delete a single file
- [ ] User can delete multiple files simultaneously
- [ ] User can delete more than 10 files simultaneously
- [ ] Deleted files are removed from the file list
- [ ] Success message is displayed only when action is completed
- [ ] User can move a Manuscript file to a folder using Drag and Drop
- [ ] User can move a PDF file to a folder using Drag and Drop
- [ ] User can move a PDF file to a folder using Copy & Paste
- [ ] User can move a PDF file to a folder using Cut & Paste
- [ ] Moved file appears inside the destination folder
- [ ] Moved file is removed from its original location

---

## 3. Editor Functionality

- [ ] Editor loads correctly when opening a document
- [ ] User can type and edit text in the editor
- [ ] User can select text in the editor
- [ ] Formatting toolbar is visible and accessible
- [ ] Bold, Italic, Underline formatting works correctly
- [ ] Font size can be changed
- [ ] Font type can be changed
- [ ] Formatting toolbar does not overlap other UI elements
- [ ] Dropdown panels appear in correct z-index layer
- [ ] All toolbar buttons are functional and accessible

---

## 4. AI Assistant Functionality

- [ ] AI assistant is accessible from within the editor
- [ ] User can send a prompt to the AI assistant
- [ ] AI generates relevant content based on the prompt
- [ ] AI generated content is inserted correctly into the document
- [ ] AI does not display raw error messages to the user
- [ ] HTTP or CSRF errors are never visible in the user interface
- [ ] AI assistant works correctly for content generation prompts
- [ ] AI assistant works correctly for grammar correction prompts
- [ ] AI assistant works correctly for formatting prompts
- [ ] AI assistant works correctly for character name change prompts

---

## 5. File Upload & Attachments

- [ ] User can upload a PDF file
- [ ] User can upload images as attachments
- [ ] Uploaded files appear correctly in the file list
- [ ] Attachment panel opens correctly without overlapping other elements
- [ ] Attachment icon is accessible from the formatting toolbar

---

## 6. General UI & Usability

- [ ] All buttons are functional and responsive
- [ ] No raw technical error messages are displayed to end users
- [ ] Platform works correctly on Chrome browser
- [ ] Platform is tested on STG environment
- [ ] Navigation between documents works correctly
- [ ] Auto-save works correctly during editing

---

## Testing Notes
> Checklist was created based on hands-on testing experience
> on this platform. Items are derived from real test scenarios
> including edge cases discovered during active testing cycles.
> Special attention was given to AI assistant behavior, file
> management reliability, and UI layering issues between
> the formatting toolbar and AI interaction panels.
