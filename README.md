# Junior Pilot Academy

A kid-friendly aviation learning site, for one student only.

Live site: https://aahmeddbs-pixel.github.io/junior-pilot-academy/

- **Locked (Nov 2026):** the whole academy is scrambled (AES-256) inside `index.html` and only opens after signing in with the student's username and password. Viewing the page code shows nothing readable.
- "Remember me on this computer" keeps it open on that computer; otherwise it locks again when the tab is closed. **🔒 Sign out** (bottom right) locks it straight away.
- Progress is saved in the browser as before.
- To change the content, ask Claude: it opens the locked page with the login, edits and locks it again.
