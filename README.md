# HTML Basics: Fix the Issues

A small practice repo for learning basic HTML structure and the `<h1>` to `<h6>` and `<p>` tags.

The file `index.html` has **10 deliberate mistakes**. Each one is filed as a GitHub Issue. Your job is to fix them, one issue at a time, using the Git and GitHub workflow.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The page with the mistakes. This is the only file you edit. |
| `README.md` | These instructions. |

## How to solve an issue

1. **Fork** this repository (button at the top right).
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/Html-bug-hunt.git
   cd Html-bug-hunt
   ```
3. **Pick one issue** and comment `I would like to work on this` on it.
4. **Create a branch** named after the issue:
   ```bash
   git checkout -b fix-issue-1
   ```
5. **Open `index.html`** in your editor and fix the problem described in the issue.
6. **Check your work** by opening `index.html` in your browser.
7. **Commit** with a clear message that links the issue:
   ```bash
   git add index.html
   git commit -m "Fix #1: add page title"
   ```
8. **Push** your branch:
   ```bash
   git push origin fix-issue-1
   ```
9. **Open a Pull Request** to the original repo. Write `Closes #1` in the description.

## Rules

- Fix **only the issue you picked** in each Pull Request.
- Do not change anything else in `index.html`.
- One issue = one branch = one Pull Request.
- Do issue 4 before issue 5.

## Issue list

| # | Topic |
|---|-------|
| 1 | Empty `<title>` |
| 2 | Missing `lang` attribute |
| 3 | Missing `<meta charset>` |
| 4 | First heading should be `<h1>` |
| 5 | Only one `<h1>` per page |
| 6 | Heading level skipped (`<h5>`) |
| 7 | Paragraph not closed |
| 8 | Wrong closing paragraph tag |
| 9 | `<br>` used for spacing |
| 10 | Placeholder `...` text in paragraphs |

## Useful links

- [MDN: Headings](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
- [MDN: Paragraph](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
# project-practice
