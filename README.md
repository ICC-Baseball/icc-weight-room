# ICC Weight Room

Itawamba CC baseball strength & conditioning app. Static site (one `index.html`) on Vercel, data and logins in Supabase (`app_docs` table, `app = 'weightroom'`).

## Files
- `index.html` – the whole app
- `manifest.json`, `icon-*.png`, `apple-touch-icon.png` – "Add to Home Screen" icon and name

## How sign-in works
- A coach puts a player's email on his name (in the app: Settings › Player logins).
- The player opens the site, taps **Create your account**, uses that email and picks a password.
- The database links the account to his roster spot automatically. Anyone whose email isn't on the roster or coach list can sign in but sees nothing.

## Updating the app
Edit `index.html` in GitHub (or have Claude do it) and commit. Vercel redeploys in about a minute.
