# AMC North Waco location site: Design preview, not live

Ticket AMC-2026-11-25-northwaco-site-build. Built the same way as amc-copperascove-design-preview, including the
Nov 25 review changes: button hover, menu matching this location's live menu minus Home, scroll-away
header + sticky bottom CTA, Short Answer stock images on service and condition pages.

Full North Waco location site on the AMC main design (Local Ember Alpine, AMC palette). Every URL on
the live northwaco.anthonychiro.com site (sitemap and menu) is kept at the same slug so rankings can
carry over, except /additional-offers/ and /ai-generated-content-disclaimer/, removed on John's
instruction (same as the Copperas Cove preview). The live FAQ URL is included even though it is not
in the page sitemap. Texas Consumer Notice is the Local Ember standard (the live footer links to
anthonychiro.com; this preview also keeps a local copy).

- noindex,nofollow on every page and robots.txt Disallow: /
- Forms off: disabled inputs and buttons, no form actions, no tracking scripts
- Service and condition pages use the Local Ember catalog. Kinesio taping has no catalog file, so it is draft copy.
- services/weight-loss.json is not used. It describes a non-medical program with no medications. This office publishes a medical program, and that published description is what the weight-loss pages use.
- Blog: 2 posts rewritten as the pattern (car-accident-tips-chiropractor, sciatic-leg-pain); remaining placeholders at their exact live URLs
- Legal pages are the Local Ember standards, at the live site's slugs
- Review layer: assets/review-comments.js adds a Local Ember reviewer toolbar. It is not part of the site design and must not ship to the live site.
- Not the live site. Not sent to the client.
- Do not expand the homepage-only folder in amc-main-design-preview/north-waco/.

NAP from the live site: Anthony Medical & Chiropractic Center, 1139 N Loop 340, Waco, TX 76705, (254) 799-8343. Monday to Friday 8:00am to 6:00pm. Saturday and Sunday closed.

Catalog files:
- arm-leg-pain uses conditions/extremity-pain.json
- back-pain uses conditions/back-pain.json
- car-accident uses conditions/auto-injury.json
- carpal-tunnel uses conditions/carpal-tunnel.json
- chiropractic-care-kids uses services/pediatric.json
- chiropractic-necessary uses services/chiropractic.json
- corrective-therapy-north-waco-tx uses services/corrective-therapy.json
- disc-injury uses conditions/disc-injury.json
- headaches-migraines uses conditions/headaches.json
- knee-pain uses conditions/knee-pain.json
- low-back-pain uses conditions/low-back-pain.json
- management-of-pain uses services/management-of-pain.json
- neck-pain uses conditions/neck-pain.json
- pain-management uses services/pain-management.json
- pregnancy uses services/prenatal.json
- sciatica uses conditions/sciatica.json
- scoliosis uses conditions/scoliosis.json
- shoulder-pain uses conditions/shoulder-pain.json
- sports-injury uses conditions/sports-injury.json
- vertigo uses conditions/vertigo.json
- wellness-care uses services/wellness-care.json
- whiplash uses conditions/whiplash.json
- work-injury uses conditions/work-injury.json
- faq-about-chiropractor-north-waco-tx uses faq-general.json

Pages: 103
