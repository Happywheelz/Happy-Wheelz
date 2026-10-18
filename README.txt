HAPPY WHEELZ — PREMIUM WEBSITE PACKAGE

Included:
- index.html — complete responsive single-page website
- assets/logo/happy-wheelz-logo.png — supplied Happy Wheelz logo
- sitemap-new.xml — sitemap (kept with your requested filename)
- robots.txt — search-engine crawl instructions
- CNAME — custom domain for GitHub Pages

Brand and business details included:
Happy Wheelz — Certified Pre-Owned Cars
55/6, Melur Main Road, Uthangudi, Madurai, Tamil Nadu 625107, India
+91 87785 75659
Instagram: https://www.instagram.com/happy_wheelz_madurai/
Map/directions: https://share.google/EUqi9mmHXbddjZo0e
Domain: https://www.thehappywheelz.com/

IMPORTANT
1. The car photos used in the design are illustrative remote images, not confirmed current stock. The site says this clearly.
2. The map embed is based on the supplied address. The directions button opens your supplied Google share link. Check that the pin is the exact entrance after publishing.
3. No introducing offer is included.
4. This package does not publish the website or change GoDaddy DNS automatically; follow the steps below.

PUBLISH USING GITHUB PAGES
1. Extract this ZIP on your laptop.
2. Open your GitHub repository (username remembered as Happywheelz) or create a repository named happywheelz-website.
3. Upload the CONTENTS of this folder to the repository root. Do not upload the ZIP itself. index.html, CNAME, robots.txt and sitemap-new.xml should appear at the top level; assets should be a folder.
4. In the repository, open Settings > Pages. Under Build and deployment, choose Deploy from a branch, select branch main and folder /(root), then Save.
5. Wait until GitHub Pages says the site is published. In Custom domain, enter www.thehappywheelz.com and save. Keep the CNAME file in the repository.
6. In GoDaddy DNS for thehappywheelz.com, set these records (remove conflicting A/CNAME records for the same host first):
   CNAME  Host: www  Points to: Happywheelz.github.io  TTL: 1 hour/default
   A      Host: @    Points to: 185.199.108.153
   A      Host: @    Points to: 185.199.109.153
   A      Host: @    Points to: 185.199.110.153
   A      Host: @    Points to: 185.199.111.153
   Optional AAAA records for @ (GitHub Pages IPv6):
   2606:50c0:8000::153
   2606:50c0:8001::153
   2606:50c0:8002::153
   2606:50c0:8003::153
   Note: GitHub username is case-insensitive; use your exact GitHub Pages hostname if GitHub shows a different one.
7. Return to GitHub Settings > Pages after DNS updates and enable Enforce HTTPS when it becomes available. DNS propagation and certificate setup may take some time.
8. Test https://www.thehappywheelz.com/ and https://thehappywheelz.com/. The preferred canonical domain is the www version.

SEO AFTER PUBLISHING
- Submit https://www.thehappywheelz.com/sitemap-new.xml in Google Search Console.
- Add/verify the domain property in Search Console and check indexing.
- Replace the illustrative car photos with real Happy Wheelz vehicle photos when available.
- Verify the map pin, phone/WhatsApp actions and all pages on mobile.

If GitHub Pages DNS settings shown in GitHub differ from these instructions, follow the current instructions shown inside your repository's Settings > Pages.
