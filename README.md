# Blockchain na Escola Website

Website of Blockchain na Escola - Democratizing Web3 education across Latin America.

## Structure

```
├── index.html        # Home page with hero and highlights
├── about.html        # Mission, history, core competencies
├── impact.html       # Impact metrics and success stories
├── partners.html     # 44+ strategic partnerships
├── projects.html     # Key initiatives and programs
├── publications.html # Articles, reports, media coverage
├── contact.html      # Partnership opportunities and contact info
├── styles.css        # Minimal, clean styling
└── README.md
```

## Deployment

### GitHub Pages

1. Go to repository Settings > Pages
2. Select branch `main` (or your deployment branch) and root folder
3. Save and wait for deployment
4. Your site will be available at `https://blockchainnaescola.github.io/website/`

### Custom Domain (blockchainnaescola.com.br)

1. Deploy to GitHub Pages first
2. In Settings > Pages > Custom domain, enter `blockchainnaescola.com.br`
3. Add DNS records at your domain registrar:
   - A record: `185.199.108.153`
   - A record: `185.199.109.153`
   - A record: `185.199.110.153`
   - A record: `185.199.111.153`
   - CNAME record: `www` -> `blockchainnaescola.github.io`
4. Enable "Enforce HTTPS" after DNS propagation

### Vercel / Netlify

1. Connect your GitHub repository
2. Deploy from main branch
3. Configure custom domain in platform settings

## Contact

- Email: blockchainnaescola@gmail.com
- Instagram: @blockchainnaescola
- GitHub: @BlockchainnaEscola
- Medium: @blockchainnaescola
