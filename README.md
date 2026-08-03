# Privacy Policy Site

This is a standalone folder, separate from the main automation project,
meant for its own **public** GitHub repo — so it can use free GitHub
Pages hosting without exposing your private automation repo (which
holds live API tokens and should stay private).

## Setup
1. Create a **new public** GitHub repo, e.g. `pinterest-app-privacy`.
2. Upload `privacy.html` from this folder to it.
3. Before uploading, open `privacy.html` and replace
   `[your email address]` with a real contact email — Pinterest's
   review sometimes checks this.
4. In that repo: **Settings → Pages** → Source: "Deploy from a branch"
   → Branch: `main`, folder `/ (root)` → Save.
5. After a minute or two you'll get a live URL like:
   `https://yourusername.github.io/pinterest-app-privacy/privacy.html`
6. Paste that URL into Pinterest's "Link to privacy policy" field
   when registering your app.
