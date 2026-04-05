# BugDrop Demo

Live demo of [BugDrop](https://github.com/mean-weasel/bugdrop) — a free, open-source widget: in-app feedback → GitHub Issues.

**Try it:** https://bugdrop-widget-test.vercel.app

Click the 🐛 bug button to submit feedback with screenshots & comments → creates a GitHub Issue.

## What is BugDrop?

A free, open-source **GitHub App** that adds a feedback widget to your app:
- Screenshots, annotations, comments
- Submits directly to GitHub Issues
- [Install the GitHub App](https://github.com/apps/bugdrop/installations/new)

## About This Demo

WienerMatch is a fictional landing page used to demonstrate BugDrop. Issues submitted here go to this repo's [Issues](https://github.com/mean-weasel/bugdrop-widget-test/issues).

## Widget Configuration

This demo uses the **default configuration** (title + description only). Developers can optionally collect submitter name/email by adding data attributes:

```html
<script
  src="https://bugdrop.neonwatty.workers.dev/widget.js"
  data-repo="your-org/your-repo"
  data-show-name="true"
  data-show-email="true"
></script>
```

| Attribute | Description | Default |
|-----------|-------------|---------|
| `data-repo` | Your GitHub repository | **required** |
| `data-show-name` | Display name input field | `false` |
| `data-require-name` | Make name required | `false` |
| `data-show-email` | Display email input field | `false` |
| `data-require-email` | Make email required | `false` |

See the [BugDrop documentation](https://github.com/mean-weasel/bugdrop#widget-options) for all options.
