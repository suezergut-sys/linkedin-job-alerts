# OpenClaw LinkedIn Job Alerts — information pages

Static pages prepared for GitHub Pages and Google OAuth Branding. This directory
contains public-safe website source only, not the OpenClaw skill or runtime.

Status: published on GitHub Pages. Google ownership verification and OAuth
production setup are tracked separately and must be confirmed in Google.

## Deployment

- Repository: [suezergut-sys/linkedin-job-alerts](https://github.com/suezergut-sys/linkedin-job-alerts).
- Pages source: `main`, root directory; `.nojekyll` disables Jekyll processing.
- Homepage: [OpenClaw LinkedIn Job Alerts](https://suezergut-sys.github.io/linkedin-job-alerts/).
- Privacy: `privacy.html` under that URL.
- Terms: `terms.html` under that URL.

The owner approved public publication of these pages on 25 October 2026.
Only commit the explicit files in this directory. Never copy the infrastructure
repository, parent workspace, private drafts, Gmail samples or runtime data.

## Preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1 --directory .
```

Open `http://127.0.0.1:8765/`. The pages use local CSS and no JavaScript, fonts,
analytics or external embeds. External policy links are normal navigation links.

## After publication

1. Confirm all three deployed HTTPS pages are public and reachable.
2. Add the exact Pages URL as a URL-prefix property in Google Search Console.
3. The homepage includes the HTML verification meta tag supplied by Google for
   that property. Keep it in place after verification; do not replace it with a
   guessed token or the token belonging to another account/property.
4. Use the Google-accepted owner-controlled domain in Authorized domains and set
   the three exact page URLs in OAuth Branding. A platform subdomain's acceptance
   must be checked in Google, not assumed from a working website.
5. Complete the OAuth publication confirmation. Personal-use verification
   exemptions do not guarantee that every Branding prerequisite is waived.
6. Obtain a fresh production OAuth grant, retain the previous working grant until
   replacement succeeds, and test readonly refresh and labelled preview on VPS.
7. Update the public descriptions when product capabilities or data handling change.

See Google's [Branding requirements](https://support.google.com/cloud/answer/15549049?hl=en)
and [ownership verification instructions](https://support.google.com/webmasters/answer/9008080?hl=en).
