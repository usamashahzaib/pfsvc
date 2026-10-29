# Sitemap and URL fixes

Found on the live site on 2026-10-27:

1. Every URL in sitemap.xml has lastmod 2026-03-25. Remove lastmod until each page has a real edit date.
2. The sitemap lists .html URLs. The extensionless versions (/about, /faq, /contact) return 404. Either keep .html everywhere or add 301 redirects from the clean URLs. Pick one and use it in canonicals, nav and sitemap.
3. Add /services.html and /llms.txt after the pages exist.
4. robots.txt on the live site already allows GPTBot, ClaudeBot, PerplexityBot and Bingbot and points to the www sitemap. No change needed.
5. The footer lists a Contact link. I did not check its target. /contact returns 404, so confirm the link works.
