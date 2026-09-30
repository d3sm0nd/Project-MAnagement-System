# Zoho Projects Pro - Login Protected Website

## Run
Open `login.html` in a browser.

## Demo credentials
User ID: `admin`
Password: `Admin@123`

## Files
- `login.html` - login screen and credential check
- `portal.html` - your existing project portal, protected by session authentication
- `README.md` - instructions

## Important security note
This version is suitable for a local/demo HTML website. The credentials are present in client-side JavaScript, so this is NOT secure authentication for a production website.

For production, use a backend such as PHP + MySQL, Node.js + PostgreSQL/MySQL, etc. The backend should validate credentials and create a secure server-side session. Passwords should be stored using a strong password hash such as Argon2id or bcrypt.
