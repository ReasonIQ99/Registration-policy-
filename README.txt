REASONIQ99 Founding 999 Registration

Files: index.html (registration form), privacy.html (policy template).

To connect Google Sheets, replace YOUR_GOOGLE_APPS_SCRIPT_URL_HERE in index.html with your deployed Google Apps Script Web App /exec URL. Your Apps Script must validate inputs, enforce the 999-registration limit on the server, generate unique registration numbers, save to the sheet, and return JSON such as {"success":true,"regNo":"R99-001"}. Confirmation emails only work if your Apps Script explicitly implements them.

Do not put private secrets in this public HTML. The privacy policy is a template, not legal advice or a compliance certification. Review it against your actual practices before collecting personal data.
