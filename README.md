# Split It

A simple Splitwise-style expense splitter. Add people (with mobile numbers) and expenses, then tap **Settle up** to see who owes who and text everyone their share.

- Single `index.html`, no build step — deploys straight to GitHub Pages.
- Data is saved in the browser (localStorage) on the device you use, and also in the page URL (`#s=...`), so the link itself is the session. Tap **Share** to send it to someone, and the texts include it too.
- Texts open your phone's Messages app pre-filled with the number and message; tap send for each person.
