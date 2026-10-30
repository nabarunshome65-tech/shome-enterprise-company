# Shome Enterprise — advanced SEO update

This package improves the existing GitHub Pages website while keeping the main website as **one self-contained HTML file** (CSS and JavaScript remain embedded in `index.html`). The additional files support search crawling and social sharing; they are not CSS or JavaScript dependencies.

## Package contents
- `index.html` — clearer search title and description, service-focused heading and copy, expanded service descriptions and FAQs, Kolkata-based/nationwide enquiry wording, and Organization + WebSite structured data. Existing phone numbers, email and Google Form link are retained.
- `robots.txt` — allows public crawlers and points to the sitemap.
- `sitemap.xml` — currently lists the homepage because the website is a one-page site.
- `assets/shome-enterprise-social-preview.jpg` — social sharing preview. It is a promotional illustration, not a photograph of a real completed installation.
- `assets/shome-enterprise-icon.svg` — browser tab icon (favicon).

## Upload to the existing GitHub repository
1. Extract this ZIP file on your computer.
2. Open https://github.com/nabarunshome65-tech/shome-enterprise-company
3. Replace the existing root `index.html` with the new `index.html` from this package.
4. Upload or replace `robots.txt` and `sitemap.xml` in the repository root.
5. Create an `assets` folder if needed, then upload **both** files from this package's `assets` folder into it. Preserve the exact filenames.
6. Commit the changes. Keep GitHub Pages set to branch `main` and folder `/(root)`.

## Check these URLs after deployment
- Homepage: https://nabarunshome65-tech.github.io/shome-enterprise-company/
- Robots: https://nabarunshome65-tech.github.io/shome-enterprise-company/robots.txt
- Sitemap: https://nabarunshome65-tech.github.io/shome-enterprise-company/sitemap.xml
- Social preview: https://nabarunshome65-tech.github.io/shome-enterprise-company/assets/shome-enterprise-social-preview.jpg
- Favicon: https://nabarunshome65-tech.github.io/shome-enterprise-company/assets/shome-enterprise-icon.svg

## Submit to Google Search Console
1. Open Google Search Console and select the verified URL-prefix property for the exact GitHub Pages URL.
2. Open **Sitemaps**, enter `sitemap.xml`, and submit it.
3. Open **URL Inspection**, enter the homepage, click **Test Live URL**, then **Request Indexing** if the page is available to Google.
4. Check **Pages / Indexing** and **Performance** periodically. Google does not guarantee indexing or a particular ranking, and recrawling can take time.

## Accuracy and policy notes
- The site states that Shome Enterprise is based in Kolkata and welcomes project enquiries from across India. It also states that outstation execution depends on site location, scope, mobilisation, scheduling and availability. Keep this wording only if it accurately describes what the business can offer.
- No private residential address, fabricated review, rating, employee count, licence, award or unverified social profile has been added to structured data.
- Publish client and partner names only where details are accurate and you have permission to use them.
- Do not add blocks of repeated keywords, fake reviews or near-identical city pages. Google's spam policies identify keyword stuffing, doorway pages and scaled low-value pages as practices that can harm search visibility.

## What this update can and cannot do
This update improves the way the page describes the business, adds crawl-support files and provides machine-readable organisation details. It cannot guarantee indexing, first-page placement, Google Maps ranking or customer enquiries. The site is still a one-page website, so it has a natural limit for ranking separately for many service searches. The next substantial step is to create genuinely useful individual service pages (CCTV, networking, OFC/CAT6 cabling, intercom/EPABX, fire alarm/PA and maintenance), each with original details, real project evidence where available and its own URL. Avoid thin duplicate pages made only to target city names.
