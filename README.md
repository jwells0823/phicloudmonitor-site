# PHICloudMonitor Site

Static website for Cloudflare Pages.

## Deploy

1. Create a GitHub repo named `phicloudmonitor-site`.
2. Add `index.html` to the repo.
3. In Cloudflare Pages, create a new project from the GitHub repo.
4. Build settings:
   - Framework preset: None
   - Build command: leave blank
   - Output directory: `/`
5. Add custom domains:
   - phicloudmonitor.com
   - www.phicloudmonitor.com

## Before publishing

- Confirm `james@phicloudmonitor.com` works, or replace it in `index.html`.
- Do not commit secrets, AWS account IDs, customer names, tokens, or real customer scan results.
