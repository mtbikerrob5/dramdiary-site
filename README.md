# Dram Diary™ Website

Marketing site, privacy policy, and support page for dramdiary.com.

## Files

- `index.html` — Landing page
- `privacy.html` — Privacy policy (required for App Store)
- `support.html` — Support & FAQ (required for App Store)
- `logo.png` — Dram Diary logo (transparent background)
- `app-icon.png` — App icon

## Deploying to Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click **Add New Project** → select your repo
4. Leave all settings as default → click **Deploy**
5. In your project settings → **Domains** → add `dramdiary.com`
6. Update your DNS at your domain registrar:
   - Add an `A` record pointing to `76.76.21.21`
   - Add a `CNAME` for `www` pointing to `cname.vercel-dns.com`

## Updating the App Store button

Once the app is live, replace the `<span class="app-badge">` in `index.html` with:

```html
<a href="YOUR_APP_STORE_URL" class="btn-primary">
  DOWNLOAD ON THE APP STORE
</a>
```

## Email addresses to set up

- support@dramdiary.com
- privacy@dramdiary.com
