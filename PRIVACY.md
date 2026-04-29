TrustLens Privacy Policy
Effective: April 2026

TrustLens computes a trust score for the website you are viewing and for the Chrome extensions you have installed. Our design goal is that nothing about your browsing leaves your device unless you explicitly opt in.

What we collect by default: nothing. The default install makes no network calls beyond reading files bundled inside the extension. No URLs, no page content, no identifiers, no telemetry, no analytics, no crash reports.

What is stored locally: your settings (score weights, toggles), a per-origin cache of recent analyses, and a rolling audit log of recent scores. All of this lives in chrome.storage.local on this device. Nothing is synced.

Optional cloud features: each is off by default and can be enabled in Settings. Before any request runs, TrustLens shows you the exact payload it would send. The available toggles are: WHOIS / domain age (sends the registrable domain), Google Safe Browsing (sends a hash prefix of the URL), VirusTotal (sends a URL or file hash), Chrome Web Store metadata (sends extension IDs you have installed), and signed list auto-updates (sends only the current list version). Turning a toggle off stops all calls associated with it.

Paid plans (where offered): payment and account creation happen on our website, not in the extension. The extension only stores and verifies a license key you paste into Settings. Email addresses and payment details are never transmitted by the extension.

Data sharing: we do not sell user data, do not use it for personalized ads, and do not transfer it to third parties for purposes unrelated to the single purpose of the extension. Use of any data received from Google APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

Your controls: Settings -> Your local data lets you export everything as JSON or wipe it with one click.

Contact: privacy@trustlens.example
Source code: https://github.com/example/trustlens
