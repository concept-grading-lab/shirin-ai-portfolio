# Shirin Deochand Lade — AI portfolio (final GitHub Pages release)

Four-page responsive portfolio, including the approved skills section, experience timeline, publications, and hobby projects. All website content is static; it needs no backend, database, app keys, paid server, or build process.

## The intended GitHub repository and site URL

- **Repository owner:** `concept-grading-lab` (you must have permission to create repositories under this organisation)
- **Repository name:** `shirin-ai-portfolio`
- **Intended site:** https://concept-grading-lab.github.io/shirin-ai-portfolio/

The SEO metadata, canonical URLs, social preview URLs, structured data and `sitemap.xml` match this **exact** address. If you use a different GitHub owner, repository name, or custom domain, update those URLs before publishing. Relative internal links will still work.

## Upload using GitHub's website

1. Sign into https://github.com/ and open the `concept-grading-lab` organisation.
2. Create a new **public repository** named `shirin-ai-portfolio` with the **main** default branch. If the repository already exists, check it before overwriting anything.
3. Extract the release ZIP on your computer. Inside is `index.html` directly alongside `experience.html` and `assets/`.
4. In the GitHub repository, choose **Add file → Upload files** (if the repository is completely empty, use **uploading an existing file**). Upload **all contents of the extracted folder**, including the `assets/` directory. Do **not** upload only the ZIP or leave everything nested inside a parent folder.
5. Commit changes to **main**. Confirm `index.html` appears at the repository root.
6. In the repository choose **Settings → Pages → Build and deployment**. Set **Source = Deploy from a branch**, **Branch = main**, **Folder = /(root)**. Save.
7. When GitHub says it is published, open https://concept-grading-lab.github.io/shirin-ai-portfolio/ using a private/incognito browser window and inspect all four pages. Publishing may take several minutes.

## What to check on your public website

- About: portrait, seven grouped skills categories, contact cards, **both** `shirin3lade@gmail.com` and `shirin.lade@open.ac.uk`.
- Experience: blue-dot timeline, dates in the left column, dark-blue badge on the current PhD role, clickable RoadSense repository.
- Publications: two papers, author name highlighted in blue, clickable paper titles and Scholar link.
- Hobby Projects: Closet Compass demo and code, GlucoDiary repository, on-page Read More sections.
- Mobile: tap Menu, check all page links and make sure text doesn't overflow.

External apps and GitHub repositories may depend on their own permissions, availability and deployment. The local tests assert destination URLs, not third-party uptime.

## Google Search Console: help Google discover your portfolio

1. Once your site is live, open https://search.google.com/search-console/ .
2. Choose **Add property → URL prefix** and enter the exact URL `https://concept-grading-lab.github.io/shirin-ai-portfolio/` (include the trailing slash).
3. Select the **HTML file** or **HTML tag** ownership-verification method offered by Google. For HTML file: download the unique verification file from Google, upload it unmodified to the repository root, commit to main, confirm Google’s specified verification URL works, then click Verify. For HTML tag: add the specific `google-site-verification` meta tag supplied by Google to the head of `index.html`, commit, and click Verify. Do not make up your own verification token.
4. In **Sitemaps**, submit `sitemap.xml` (full URL: https://concept-grading-lab.github.io/shirin-ai-portfolio/sitemap.xml).
5. In **URL inspection**, inspect your homepage and choose **Test live URL** then **Request indexing** when available. Repeat for the other three page URLs if needed.
6. Link the published site from your LinkedIn profile, your GitHub organisation/profile README, and your OU/Scholar profile where you have permission.
7. Monitor indexing, impressions, clicks and queries in Search Console. For a simple spot check search Google for `"Shirin Lade"` or `site:concept-grading-lab.github.io/shirin-ai-portfolio/`. The `site:` search is a rough check, not a reliable complete indexing report.

**Important:** Google can take days or weeks to crawl a new site, and a request does not guarantee it will be indexed or ranked first. Search Console is the source of truth for indexing and search performance. The portfolio is *not* published by creating this ZIP.

## Files

- `index.html` — About and skills
- `experience.html` — professional career timeline
- `publications.html` — two linked publications
- `hobby-projects.html` — independent AI applications
- `404.html` — not found page
- `assets/` — CSS, JS, portrait and favicon
- `.nojekyll` — disables default Jekyll processing for this static site
- `sitemap.xml` — four intended public site URLs
- `QA_SUMMARY.md` — local testing scope and limitations

## Sources

- GitHub Pages quickstart: https://docs.github.com/en/pages/quickstart
- Publishing from a branch: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Adding files to a GitHub repository: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Google Search Console: https://search.google.com/search-console/about
- Google site verification: https://support.google.com/webmasters/answer/9008080
- Google indexing requests: https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
- Sitemap guidance: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- SEO starter guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
