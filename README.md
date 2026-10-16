# AI Assurance — website

The public website of **AI Assurance**, an AI risk assessment and guardrails platform by the Ethical and
Trustworthy AI team: https://aiagent1024.github.io/ai-assurance/

It is a static page with no build step:

| File | What it holds |
|---|---|
| `index.html` | All the content: the illustrative example, the challenge, what sets the platform apart, how it works, the four workspaces (tabs), deploying it, who we work with (tabs), publications and FAQ; a small inline script drives the tabs and the phone menu |
| `assets/site.css` | The styles, with light and dark themes |
| `assets/favicon.svg` | The brand mark |
| `assets/social-card.png` | The 1200 × 630 preview image shown when the link is shared |

GitHub Pages serves the `main` branch as it is (`.nojekyll` turns Jekyll off), so a push to `main` updates the site
within a minute or two. To preview a change locally:

```bash
python3 -m http.server 8765
```

then open http://127.0.0.1:8765.
