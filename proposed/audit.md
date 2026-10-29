# PFSVC audit, 2026-10-27

Source: live pages fetched through the owner's Chrome. Search Console, 28 days to 2026-10-25: 0 clicks, 29 impressions, average position 3.8, one query ("professional association", 7 impressions).

PFSVC is a freelancer verification council, not a financial services firm. The earlier FinancialService schema template was wrong and is removed.

## Claims
Owner said the claims are real, then corrected two figures. Owner will verify the rest. Unverified until then.

| Claim on site | Status | Action |
|---|---|---|
| "Official institution in Pakistan", "The Official Standard of Competence" | Owner did not address. The FAQ says PFSVC is not a government body, so "Official" can read as state-backed. | Consider "independent". Owner decision. |
| "4,000,000+ Pakistani freelancers" | Owner got it from an AI chat, not a source. UNVERIFIED. | Remove until a primary source is found. Not used in these files. |
| "22% acceptance rate", "1,200+ fraud denials" | WRONG on the live site. Owner says the real figures to date are 14% and 700+. | Correct the live site now. Add an "as of" date. Files here use 14% and 700+. |
| Biometric liveness, sanctions and AML screening, proctored tests, AI detection | Owner confirmed. | Used on services.html. |
| "Zero-risk" hiring wording | Owner confirmed claims. Wording still promises an outcome. | Consider "reduced risk". Owner decision. |
| Client logo strip | Owner confirmed claims. | Keep only entries with written permission. |
| Hero card with a sample member | Looks like a real member. | Label it "Sample". |
| "HR-Certified Assessors", "Assessment Board" | No names shown. | Add real names or roles. |
| "(c) 2025", "2025 global market demands" | Stale. | Update. |

## Other findings
- Two contact emails, both valid per owner: verify@pfsvc.com.pk (footer) and pfsvc.pakistan@outlook.com (FAQ). Both go in schema as separate contact points. State on the site which one is for what.
- Homepage title has no category words. Proposed: "Freelancer verification in Pakistan | PFSVC".
- No Service, Organization or FAQPage schema was visible in page text. I could not read page source, so confirm before adding.
- No services page. Proposed: services.html.
- FAQ already has a plain answer format. Good base for FAQPage schema, which needs the same text visible on the page.

## What changed from the first proposal
The first run assumed a YMYL financial site. The real site is a credential product, so regulator citations do not apply. The risk here is overclaiming. Keep every claim tied to a source or date.
