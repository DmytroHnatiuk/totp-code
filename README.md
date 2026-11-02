# TOTP code

A single static page that shows the current TOTP code of a secret (RFC 6238: HMAC-SHA1, 6 digits, 30 s step).

- Accepts a base32 secret, an `otpauth://totp/…` link, or a base64url secret.
- Shows the current code (click to copy), the seconds left and the next code.
- Runs fully in the browser with Web Crypto. Nothing is stored, and the page's Content-Security-Policy blocks every network request.

Open `index.html` locally, or use the GitHub Pages copy.
