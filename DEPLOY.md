# Cloudflare Pages Deploy

## Cost: $0/month (free tier)

Both clawfactory.net and clawfactory.me deploy as static sites on Cloudflare Pages.

## Steps (repeat for each domain)

1. Push the site folder to a GitHub repo
   - clawfactory-net/ → github.com/YOUR_USER/clawfactory-net
   - clawfactory-me/  → github.com/YOUR_USER/clawfactory-me

2. Go to dash.cloudflare.com → Workers & Pages → Create application → Pages

3. Connect your GitHub repo

4. Build settings:
   - Framework preset: None
   - Build command: (leave empty)
   - Build output directory: /

5. Click Save and Deploy
   - Cloudflare assigns a free *.pages.dev subdomain immediately

6. Add your custom domain:
   - Go to your project → Custom domains → Add domain
   - Enter: clawfactory.net (or clawfactory.me)
   - Cloudflare will show you DNS records to add

7. In your DNS registrar (you have Premium DNS):
   - Add CNAME: @ → <your-project>.pages.dev
   - Or if @ CNAME not supported, use A records Cloudflare provides
   - Propagation: usually under 5 minutes with Cloudflare DNS

8. Done. HTTPS auto-provisioned. Global CDN. $0/month forever.

## Free Tier Limits (more than enough)
- Unlimited bandwidth
- 500 builds/month
- 100 custom domains
- Automatic HTTPS

## To update the site
Push a new commit to GitHub → Cloudflare auto-deploys in ~30 seconds.
