# Kevin Feng’s personal website

Live at [kevinfwl.github.io](https://kevinfwl.github.io).

The website source lives in [kevinfwl/personal-site](https://github.com/kevinfwl/personal-site/tree/gh-pages), on its `gh-pages` branch. This repository contains the GitHub Pages deployment workflow.

To publish updates, edit the source repository, then open **Actions → Publish personal website → Run workflow** in this repository. Each run builds the latest source with Jekyll and deploys it here over HTTPS. Changes pushed to this repository’s `master` branch also trigger deployment.

The build sets the site URL to `https://kevinfwl.github.io`, uses an empty base path, omits the old custom-domain CNAME, and fixes the obsolete stylesheet reference and self-referencing home layout in the build copy.
