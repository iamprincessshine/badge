# Certified Silly Developer — Open Badge

This folder contains a hosted Open Badges 2.0 assertion for Parchment Backpack.

## Publish it with GitHub Pages

1. Create a public GitHub repository named `certified-silly-developer`.
2. Upload every file from this folder to the repository root.
3. Replace every occurrence of `YOUR_GITHUB_USERNAME` in `issuer.json`, `badgeclass.json`, and `assertion.json` with your GitHub username.
4. Enable **Settings → Pages → Deploy from branch → main → / (root)**.
5. Wait until GitHub Pages is published.
6. In Parchment Backpack, choose **Badges → Add Badge**.
7. Put this URL into **Badge URL**:

   `https://YOUR_GITHUB_USERNAME.github.io/certified-silly-developer/assertion.json`

8. Press **Import**.

The recipient is stored as a SHA-256 hash of the normalized email address, not as plain text.

## Important

This is technically a valid self-issued Open Badge. It is not an independent educational or professional certification: the issuer is `princess Badges`, created by the badge owner.
