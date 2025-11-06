Talka — English Correction Assistant

This is a small static web app that uses OpenAI's Chat Completions API (via user-provided API key in the browser) to correct English sentences and provide a brief explanation.

How to use

- Open the site in your browser (when hosted): https://ehsuan3.github.io/talka/
- Enter your OpenAI API key and the sentence you want corrected.
- Choose tone and click "Correct My Sentence".

Notes on hosting and security

- API keys are stored only in the user's browser localStorage (optional). The app does not store keys on the server.
- If you see "There isn't a GitHub Pages site here.", go to GitHub repository Settings → Pages and set the source to the `gh-pages` branch (root). It may take a minute to activate.

Development

- The main file is `index.html` in the repository root.
- To deploy manually, an easy approach is to create and push a `gh-pages` branch that contains `index.html`.

Contact

If you want additional features (examples: server-proxy for centrally managed keys, usage tracking, or UI improvements), tell me which and I'll implement them.