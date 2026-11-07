# Agency Remediation

Agency Remediation is the portfolio hub for specialist agents used across the Andrew Jourdan repositories. The site lists the properties it serves, describes the specialist roles, and provides a form that drafts an email to the agency steward.

**Live site:** [agencyremediation.com](https://agencyremediation.com/)

## Preview locally

From the repository root, run `python3 -m http.server 8000` and open [localhost:8000](http://localhost:8000/). The site is static and has no build step. The request form opens your mail app with a draft.

## Deployment

GitHub Pages publishes the root of `main`. `index.html` is the homepage, and `CNAME` associates the site with its custom domain. Cloudflare manages public DNS and sets the `X-Content-Type-Options: nosniff` response header for the apex and `www` hostnames.

See [CONTRIBUTING.md](CONTRIBUTING.md) for review steps and [SECURITY.md](SECURITY.md) for private vulnerability reporting.
