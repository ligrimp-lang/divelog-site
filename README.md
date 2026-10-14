# divelog-site

The landing, privacy and support pages for **Dive log**, the Shearwater dive log for iPhone.
Served by GitHub Pages from `main` / root, the same arrangement as the planners' sites.

- <https://ligrimp-lang.github.io/divelog-site/>
- <https://ligrimp-lang.github.io/divelog-site/privacy.html>
- <https://ligrimp-lang.github.io/divelog-site/support.html>

App Store Connect links the privacy and support pages; Apple rejects a submission whose
privacy-policy URL is dead.

## This folder is the source; the GitHub repo is a publishing target

The pages live in the `sharewater_dive_log` repository at `divelog-site/`. Edit them there;
`ligrimp-lang/divelog-site` is only where they are published to.

    .claude/skills/ship/scripts/publish-site.sh dive-log --dry-run   # what would change
    .claude/skills/ship/scripts/publish-site.sh dive-log             # commit and push

Contact: divelog@ismailov.net

© 2026 Rustam Ismailov
