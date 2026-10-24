# Timo Auto Shorts website

Public, static documentation for the local Timo Auto Shorts desktop application.

- Home: https://timo456.github.io/timo-auto-shorts-site/
- Privacy: https://timo456.github.io/timo-auto-shorts-site/privacy.html
- Terms: https://timo456.github.io/timo-auto-shorts-site/terms.html

## Publishing

GitHub Pages publishes the root of the `main` branch. `.nojekyll` serves these
files without a site generator. There are no dependencies, JavaScript, analytics,
external fonts, sign-in handlers, upload endpoints, or paid services.

Edit the HTML or local CSS/SVG assets, review `git diff`, and push to `main`.
Check the Pages deployment and public URLs after each change. Use relative links
so navigation works under the project path. The `.gitignore` is an explicit
allowlist: add any future static asset deliberately.

**Never copy the desktop application directory here.** Do not commit credentials,
tokens, client configuration, SQLite files, logs, local settings, private media,
upload-session URLs, backups, or diagnostic exports. Review staged files before
every push; ignored files can still be added with force or if already tracked.

## Policy maintenance

The English policy was checked against the local application implementation on
2026-10-25: its OAuth scopes, private-first uploads, local JSON/SQLite records,
NTFS credential-directory permissions, persisted resumable sessions, retained
API responses, and local media processing. It describes current behavior; it
does not assert completed Google verification. Update the policy when behavior
changes. Support contact: timo456.op@gmail.com.

The current desktop implementation has no timed expiry of cached API responses
and no automatic removal after OAuth revocation. Publishing a policy does not
resolve that implementation gap. Review retention, revocation/deletion handling,
and minimum scopes against YouTube policies before seeking production approval.

## Google Branding and domain verification

Use the three public URLs above for the Homepage, Privacy Policy and Terms of
Service fields, subject to Google's domain and app-review requirements. The
candidate authorized domain is `timo456.github.io`, without a protocol or path;
`github.io` is on the Public Suffix List. That is a domain-format determination,
not evidence that Google has accepted or verified it.

Search Console supports a **URL-prefix** property for the full project URL.
Ownership can be proved by publishing the unique HTML meta tag or HTML file
Google supplies. No verification token has been added to this repository, and
Search Console ownership has not been claimed as verified.

Google's current OAuth domain-verification guide specifically requires a
**Domain property with DNS verification**. GitHub Pages does not give this
repository owner DNS control of `timo456.github.io`. Therefore HTML URL-prefix
verification alone must not be treated as OAuth domain approval. Google may
require a domain whose DNS the project owner controls or an explicitly accepted
alternative. No domain purchase, Google Branding change, verification submission,
OAuth-token change, or application publishing-setting change is part of this
website deployment.

Official references (checked 2026-10-25):

- [Google OAuth branding](https://support.google.com/cloud/answer/15549049?hl=en)
- [Google OAuth domain verification](https://support.google.com/cloud/answer/13804266?hl=en)
- [Search Console verification methods](https://support.google.com/webmasters/answer/9008080?hl=en)
- [Public Suffix List](https://publicsuffix.org/list/public_suffix_list.dat)
- [YouTube developer policies](https://developers.google.com/youtube/terms/developer-policies)
- [GitHub Pages documentation](https://docs.github.com/en/pages)
