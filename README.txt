GOOSEROOT — COMING SOON PAGE (Lens identity, 74B)
=================================================
Upload everything in this folder to the root of your hosting for www.gooseroot.com.
It also works opened straight from your computer or from a subfolder (all paths are relative).

SETTINGS — open index.html and search for "SETTINGS"
  CONTACT_EMAIL  Shown in the footer. Placeholder: hello@gooseroot.com — change it to your real inbox.
  FORM_ENDPOINT  Where sign-ups go. Empty = "Notify me" opens the visitor's email app addressed to you.
                 To collect emails automatically, create a free form at Formspree / Basin / Getform and paste its URL.
  LAUNCH_DATE    Optional countdown, e.g. '2027-01-15T10:00:00+05:30'. Empty = hidden.

TWO DOMAINS
  Make https://www.gooseroot.com the main address and set gooseroot.in + www.gooseroot.in to a permanent (301)
  redirect to it. The included .htaccess does this on Apache/cPanel hosting; on Netlify, Vercel or Cloudflare
  use their domain redirect settings. The page tells search engines gooseroot.com is the main address.

SHARING
  og-image.png is the preview shown when the link is shared on WhatsApp, LinkedIn, X, Slack.
  It loads from https://www.gooseroot.com/og-image.png once the site is live.

FILES
  index.html, og-image.png, favicon.ico / .svg / -16x16 / -32x32, apple-touch-icon.png,
  android-chrome-192x192 / -512x512, site.webmanifest, assets/fonts (Poppins, self-hosted), .htaccess
