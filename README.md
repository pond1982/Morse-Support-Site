# Morse Code with Flint support site

A standalone static website for Suwitcha Sugthana. Public contact: **pondd.me@gmail.com**. Prepared October 1, 2026. No deployment, push, repository creation or live URL is included.

## Files

- `index.html` — support, setup and troubleshooting FAQs.
- `privacy.html` — owner-review privacy draft describing the audited local app, GitHub Pages hosting and support email separately.
- `assets/site.css` — responsive styles using system fonts.
- `assets/` — optimized copies of existing Flint, campsite and icon artwork from the Morse project.
- `.nojekyll` — serves this folder as ordinary static files.

No server, build step, JavaScript, trackers, CDN, external fonts, forms or cookie-setting code are required. All local links and assets use relative paths, including when the site is hosted beneath a project subdirectory.

## Preview locally

Open `index.html` in a browser. `privacy.html` and the artwork also work directly from local files. An optional ordinary static-file server works too; none is required.

## Host on GitHub Pages yourself

1. Review the public contact, support copy and privacy draft before hosting. The app is still in development; there is no invented App Store download link.
2. Copy **the contents of this folder** into the root of your chosen GitHub Pages repository, or into its configured `/docs` folder. Preserve `assets/` and `.nojekyll`.
3. In that repository's **Settings → Pages**, choose the applicable branch and folder. You control this publishing action; no repository or account was created by this work.
4. After GitHub provides the actual live URL, check the support page, `privacy.html`, image loading, phone layout and email links. Use the confirmed URLs in App Store Connect only then.

Intended relative paths for a project Pages repository:

- Support: `/<repository-name>/` (or `/<repository-name>/index.html`)
- Privacy: `/<repository-name>/privacy.html`

For a user/organization Pages site or a custom domain mapped to its root, the equivalent paths are `/` and `/privacy.html`. These are path templates, **not live URLs or a guessed username/repository**. No `CNAME` file is included.

## Before making the privacy page public

The policy is an accurate draft based on source and built-app inspection as of October 1, 2026; it is not claimed to be legally reviewed. The owner should review its wording, support email retention practices, GitHub/provider handling and applicable requirements before hosting. Remove or revise the owner-review draft designation only after that review. Update the date and content if the shipping app adds networking, purchases, services or different data handling. Local app processing must not be confused with hosting logs or email processing.

Physical-iPhone Receive validation remains open. The support page describes setup and current limits without promising decoder accuracy. Confirm the final shipping feature set before changing the development label or adding an App Store link.

## Maintenance

Keep support content aligned with the app's visible controls. The guide replay is in app Settings → Field guide. Camera Receive begins at 10 WPM. Send accepts A–Z and spaces. Avoid publishing private bug-report material or support attachments in this repository.

Existing artwork was reused; no new art generation or app-code changes were needed. Assets are small local files. Human-selected links to GitHub and Google privacy information do not load external resources until followed.

## Validation performed

Both pages were rendered in a new isolated headless browser at 1440, 390 and 320 pixels wide. Local files and section links resolve; images load; no horizontal overflow or automatic external subresource requests were found. Keyboard access to the skip link and native FAQ disclosure was checked, and reduced-motion behavior was verified. Core text/panel color pairs meet at least 4.5:1 contrast. Desktop and phone screenshots received separate visual inspection. No native foreground browser session, App Store record or app source was changed. Manual assistive-technology and real-device checks are outside this browser validation.

References: [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages), [GitHub privacy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), [Google privacy](https://policies.google.com/privacy).
