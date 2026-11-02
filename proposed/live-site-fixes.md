# PFSVC live site fix list, 2026-11-02 [REVIEW REQUIRED]

The live site is static HTML on Vercel and its code is not in this repo. These are exact edits for whoever deploys the site. Nothing here has been applied.

## Fix now (wrong or unsupported on the live site)
| Where | Live text today | Replace with | Why |
|---|---|---|---|
| Stats strip | "22%" acceptance rate | "14% acceptance rate (as of 2026-10-27)" | Owner confirmed 14% on 2026-10-27. Live figure is wrong. |
| Stats strip | "1,200+" fraud denials | "700+ fraud attempts denied (as of 2026-10-27)" | Owner confirmed 700+. Live figure is wrong. |
| Hero / stats | "4,000,000+ Pakistani freelancers" | Remove until a primary source exists | Owner took it from an AI chat. For scale: DigiSkills, the government-backed training program, reports "more than 3 million trainings since 2018" and counts trainings, not people (https://digiskills.pk/WhatsDigiSkills.aspx). A 4 million freelancer claim has no support. |
| Hero | "The Official Standard of Competence", "Official institution" | "Pakistan's independent verification body for freelancers" | The site's own FAQ says PFSVC is not a government body. "Official" reads as state-backed. Owner decision. |
| Hiring section | "zero-risk" | "reduced risk" | A verification badge cannot promise zero risk. Owner decision. |
| Hero card | Member "Ayesha Khan", badge PF-478291, 85% tracker | Add visible label "Sample profile" | Reads as a real member. Do not show a real-looking ID that is not real. |
| Footer, hero | "(c) 2025", "2025 global market demands" | Current year | Stale. |

## Needs owner proof before keeping
- Client logo strip: keep only logos with written permission. Techspirex appears in it. Confirm that is permitted.
- "HR-Certified Assessors" and "Assessment Board": add real names or roles, or remove.

## Technical
- Title: "Freelancer verification in Pakistan | PFSVC". Current homepage title has no category words.
- Accessibility score is 82 on mobile PageSpeed (2026-11-02). Performance 94, LCP 2.2 s, CLS 0. The failing audits were not read. Run the report and fix contrast and labels first.
- Mobile test redirects pfsvc.com.pk to www.pfsvc.com.pk. Pick one host, redirect the other with a 301, and use it in canonicals, sitemap and schema.
- Bing Webmaster: sitemap has 12 URLs and was last crawled 2026-03-25. Resubmit after deploying the changes.
- Add services.html, schema-organization-services.json and llms.txt from this folder after the claims above are fixed. Schema must match visible text.

## Search and AI answers (2026-11-02)
- Search Console 28 days: 1 click, 33 impressions, position 4.1. One query, "professional association" (10 impressions). No query includes "freelancer verification" or "Pakistan".
- Perplexity, "How can a freelancer in Pakistan get skills verified?": answer named Freelancer.com's Verified program and PSEB freelancer registration. PFSVC was not mentioned. Source list not captured.
- Gap: no page answers "how to get verified as a freelancer in Pakistan" with steps and fees. That is the page to write once claims are fixed. Do not copy PSEB or Freelancer.com details without citing their own pages.
