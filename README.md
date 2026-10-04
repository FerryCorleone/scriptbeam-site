# ScriptBeam legacy legal site

This repository preserves the original support and legal pages published on July 20, 2026. The production website is hosted by the Cloudflare Worker `scriptbeam-app`; its source repository is `FerryCorleone/ScriptBeam-Website`.

## Migration — October 5, 2026

The root, privacy, support, and terms pages redirect to the corresponding HTTPS routes at `https://scriptbeam-app.com`. The original bilingual legal content remains in the HTML as a fallback for clients that do not follow JavaScript or meta redirects. Privacy and terms preserve the supported language anchors; Chinese-language browsers default to the Chinese section. No analytics, forms, credentials, or app source have been added.

**Keep this repository public and GitHub Pages enabled while the live App Store privacy policy URL still points here.** App Store Connect only releases privacy URL changes with the next app version. Do not privatize, archive, delete, or disable Pages merely because a draft contains the new URL.

Before retiring this compatibility site, verify both iOS and macOS public product pages, both English and Simplified Chinese privacy links, TestFlight metadata, and the production privacy/support/terms routes. Retain redirects while published links or third-party references still need them.
