# AI-rings

Interactive map of AI money flows: who funds whom, and where to watch.

Live site: `https://jb-db05.github.io/AI-rings/`

## Files

- `index.html` is the whole site. HTML, CSS, JS and the logo (base64) are all in this one file.
- `.nojekyll` tells GitHub Pages to serve the files as they are, without running Jekyll.
- `UPDATING.md` covers how to edit the page and publish the changes.

## Publishing

GitHub Pages publishes the `claude/gifted-pascal-ua4od8` branch, from `/ (root)` (set under **Settings → Pages**). Anything pushed or merged into that branch goes live after about a minute. Changes on any other branch stay off the live site until they are merged into it.

Claude Code sessions each work on their own new branch. To publish a session's work, either merge its pull request into `claude/gifted-pascal-ua4od8`, or tell the session at the start to push directly to that branch.
