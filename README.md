# Legal Stone LLP Website

Static website for Legal Stone LLP (formerly S&G Associates), Hazratganj, Lucknow.
No build step is needed. It is plain HTML, CSS and JavaScript.

## Files

- index.html : the full website (all pages and the disclaimer)
- netlify.toml : settings for Netlify
- robots.txt and sitemap.xml : help search engines find the site
- images/ : place your own images here

## Step 1: Put it on GitHub

1. Log in to github.com and click New repository.
2. Name it legalstone-website, keep it Public or Private, and click Create repository.
3. On the next page click "uploading an existing file".
4. Drag in everything from inside this folder (not the folder itself).
5. Click Commit changes.

## Step 2: Put it on Netlify

1. Log in to app.netlify.com (you can sign in with GitHub).
2. Click Add new site, then Import an existing project, then GitHub.
3. Choose the legalstone-website repository.
4. Leave Build command empty. Set Publish directory to . (a single dot).
5. Click Deploy. You will get a link like something.netlify.app.

Every time you change a file on GitHub, Netlify updates the site automatically.

## Step 3: Connect legalstone.in

1. In Netlify open your site, then Domain management, then Add a domain.
2. Type legalstone.in and follow the steps.
3. Netlify shows DNS records. In GoDaddy go to My Products, legalstone.in, DNS, and:
   - Set the A record for @ to 75.2.60.5
   - Set the CNAME record for www to your-site-name.netlify.app
   (Always use the exact values Netlify shows you, in case they change.)
4. Wait from a few minutes up to 24 hours. Netlify adds free HTTPS automatically.

## Before going live

- The statue photo still loads from GoDaddy. Download it and put it in images/ so it keeps working if the GoDaddy site is closed.
- Replace the "LS" mark with your real logo if you have one.
