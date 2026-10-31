# Future Situation Simulator — Static HTML/CSS/JavaScript

## Run in VS Code
1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.

No Python, Flask, npm, or database server is required for this static version.

## Publish on GitHub + Netlify
1. Create a GitHub repository.
2. Upload `index.html`, `css/`, `js/`, and `README.md` at the repository root.
3. Import the repository in Netlify.
4. Leave Build command blank and set Publish directory to `.` (root).

## Important limitations
This is a frontend-only demo. Login/register is not secure authentication; it only stores a demo profile in the current browser. Saved scenarios use browser localStorage and do not sync across people or devices. This static version does not connect to the original Flask/SQLite backend. The crowd calculations are simplified educational estimates, not validated predictions or safety guidance. Do not use it for real-world crowd management or emergency decisions.

For secure accounts and shared persistent records, connect the frontend to a properly secured backend API and server-side database. Never put passwords, API keys, or secrets in frontend JavaScript.
