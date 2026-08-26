# NetiShield Pro — GitHub Pages Academy

Features:
- Modern Persian RTL educational website
- Article search, categories, tags and featured articles
- Individual article URLs using `article.html?slug=...`
- Markdown editor with live preview in admin
- GitHub API publishing directly to `data/articles.json`
- Category management
- Link management
- Site settings
- SEO meta tags and Open Graph
- Automatic sitemap generation workflow
- Responsive dark/light UI
- Admin token is kept only in browser memory

## Setup
1. Upload this repository to GitHub.
2. Edit `config.js`.
3. Enable GitHub Pages using GitHub Actions.
4. Create a fine-grained GitHub token restricted to this repository with Contents: Read and write.
5. Open `/admin.html` and enter the token.
6. Never commit the token to the repository.

## Security
GitHub Pages is static. A true server-side password cannot be securely implemented without a backend. This version uses a GitHub fine-grained token for authenticated publishing and does not store it in source files.
