# YogiHub Landing Page

The public marketing site for YogiHub, introducing independent instructors to the product and linking them into the app to sign in or create an account.

## Structure

Single static `index.html` (inline CSS, no build step). Deployed via GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8080
```

## Deploy

Pushing to `main` publishes automatically via GitHub Pages (Settings → Pages → Deploy from branch → `main` / `/ (root)`).

## Links

Sign in / Sign up buttons point at the live app: https://d2i4mc65qmt90p.cloudfront.net/ (sign up uses `?mode=signup` to open directly in account-creation mode).
