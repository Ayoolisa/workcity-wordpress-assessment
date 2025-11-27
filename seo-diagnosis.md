SEO Troubleshooting Checklist (Indexing & Technical SEO)

This checklist helps diagnose why a new website — like Workcity's — may not be indexing, and ensures all key SEO technical signals are properly set up.

1. Crawlability Checklist

 Site returns 200 OK HTTP status

 No redirect loops (301/302)

 Googlebot can fetch and render the URL (checked via URL Inspection)

 No blocked CSS/JS assets

 Site loads correctly in Mobile-Friendly Test

 Server uptime confirmed (no intermittent downtime)

2. Robots.txt Checklist

 robots.txt is accessible at /robots.txt

 No accidental wide blocks like:

Disallow: /

 Important folders not blocked

 Sitemap URL listed inside robots.txt (optional but recommended)

 robots.txt syntax validated

3. No-Index & Meta Tags Checklist

 No noindex tag on important pages

 No plugins forcing global noindex

 WordPress setting “Discourage search engines” is disabled

 No x-robots-tag: noindex in server response

 No hidden canonical pointing to a noindexed URL

4. Canonical Tag Checklist

 All pages have a self-referencing canonical

 No canonicals pointing to the homepage incorrectly

 No canonicals pointing to staging/test domains

 Only 1 canonical per page

 No conflicting canonical + robots rules

5. Sitemap Checklist

 Sitemap accessible at /sitemap.xml

 Sitemap submitted in Search Console

 Sitemap contains live, indexable, 200-OK pages

 No 404 URLs in the sitemap

 No redirected URLs in the sitemap

 No duplicate URLs

 Sitemap uses absolute URLs

 XML format validated

 Sitemap updated after major content updates

6. Page Speed & Rendering Checklist

 Homepage loads within 2–3 seconds

 Images compressed

 JavaScript not blocking rendering

 CSS optimized (no abandoned stylesheets)

 Lazy-loaded sections have fallback content

 No blank/JS-only content that Google can’t render

 Core Web Vitals within acceptable range

7. Search Console Checklist

 URL inspected and eligible for indexing

 No “blocked by robots.txt” errors

 No “Duplicate without user-selected canonical” issues

 No “Soft 404” errors

 No “Alternate page with proper canonical tag” issues

 Coverage Report checked for anomalies

 Manual Actions report is clear

 Security Issues report is clear

8. Hosting & Server Checklist

 SSL certificate active (https)

 No mixed content errors

 Hosting not throttling requests

 DNS correctly propagated

 Good server TTFB (<600ms ideally)

9. Quality & Content Signals

 Pages have enough unique content

 Pages not too thin (<200 words)

 No duplicate pages

 Titles and meta descriptions filled

 Proper H1 heading on each page

 Internal linking added

10. Final Verification Steps

 Re-test homepage with URL Inspection

 Request indexing again

 Monitor Coverage Report for 24–72 hours

 Recheck sitemap status

 Confirm Googlebot activity in server logs (if available)