<div align="right">
  <a href="https://ixxie.codeberg.page/bergmirror/redirect/?cb=ixxie/bergmirror&gh=ixxie/bergmirror"><img src="https://ixxie.codeberg.page/bergmirror/badge.svg" alt="Codeberg → GitHub mirror"/></a>
</div>

# bergmirror

A small badge for repositories that are primarily developed on [Codeberg](https://codeberg.org) and mirrored to GitHub.

## Badge

![Codeberg → GitHub mirror](https://ixxie.codeberg.page/bergmirror/badge.svg)

## Usage

Place the badge at the top-right, above your title:

```markdown
<div align="right">
  <a href="https://ixxie.codeberg.page/bergmirror/redirect/?cb=USER/REPO&gh=USER/REPO"><img src="https://ixxie.codeberg.page/bergmirror/badge.svg" alt="Codeberg → GitHub mirror"/></a>
</div>

# Your project title
```

Fill in:
- `cb=<codeberg-user>/<codeberg-repo>` — your canonical Codeberg location
- `gh=<github-user>/<github-repo>` — your GitHub mirror (can differ in user *and* repo name)

The link goes through a tiny redirect page on Codeberg Pages that bounces you to the **other** platform from the one you're currently viewing:

- Viewing on Codeberg → redirects to the GitHub mirror
- Viewing on GitHub → redirects to the Codeberg canonical

If JavaScript is disabled, the redirect page shows fallback links to both.
