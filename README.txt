PROP INTERNATIONAL WEBSITE — GITHUB PAGES

Included:
- index.html: responsive single-page corporate website

BEFORE PUBLISHING:
1. Replace every occurrence of 919000000000 with your business WhatsApp number in international format (India: 91 + number).
2. Review company text, offerings, and any claims. Add confirmed contact details.
3. Project names, prices, logos, RERA identifiers and developer relationships should be added only after verification.

GITHUB PAGES SETUP:
1. GitHub -> create a new repository. Name it propinternational-website.
2. Choose Public (GitHub Pages free tier commonly supports public repositories); create repository.
3. Upload index.html at repository root (Add file -> Upload files -> Commit changes).
4. Repository Settings -> Pages -> Build and deployment -> Deploy from a branch.
5. Branch: main; folder: /(root); Save.
6. After published, GitHub shows a temporary pages URL under Settings -> Pages.

CUSTOM DOMAIN:
1. In Settings -> Pages -> Custom domain, enter propinternational.com (or www.propinternational.com, choose one canonical host).
2. At Hostinger DNS, set the records GitHub Pages currently instructs you to set. Common setup:
   - www CNAME -> <your-github-username>.github.io
   - apex/root A records -> GitHub Pages IPs as displayed in current GitHub docs.
3. Enable Enforce HTTPS after DNS check passes.
4. If using email at this domain, do not remove MX/SPF/DKIM/DMARC records.
DNS record instructions can change; follow the exact current guidance shown by GitHub Pages.

This is a static website; no backend, database or CMS is included.
