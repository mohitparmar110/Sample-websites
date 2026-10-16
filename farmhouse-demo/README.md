# Fern Cabin — Single-Property Farmhouse Website (Staging Demo)

A single farmhouse website adapted from the supplied **Fern Cabin** HTML and its original cream / forest palette, Cormorant Garamond + Jost typography, booking bar, woodland hero and illustrated footer.

## Staging URL

https://fern-field-farmhouse-demo.pages.dev

- Cloudflare Pages project: `fern-field-farmhouse-demo`
- GitHub: `mohitparmar110/Sample-websites` → `main`
- Output directory: `farmhouse-demo`
- Each commit to `main` automatically triggers a deploy.

## Working frontend features

- Single-property hero, photo gallery, six image-led amenities, surroundings and editorial wellness section
- Responsive navigation and mobile sticky enquiry CTA
- Check-in/check-out date validation and guest selection
- Enquiry dialog with name, email, optional phone and note fields
- Copy enquiry to clipboard / open a prefilled **email draft** (guest must add real host email)
- Three **clearly marked fictional sample reviews**, to demonstrate the eventual testimonials layout
- Ten expandable FAQ entries mirrored in valid FAQPage JSON-LD
- How-it-works and policy preview sections
- Separate `policies.html`: booking, cancellation, house rules, website terms, privacy and accessibility

## What the prototype does NOT do

- It **does not verify availability, send enquiries to a host, accept bookings, collect payments, or store visitors' contact details in a property CRM**.
- Room counts, guest limits, address, access details, listing photography, amenities, reviews, pricing and check-in hours are **unverified / demonstrative**. Avoid publishing them as facts.
- No ratings or aggregate review scores are provided as schema.

## SEO & accessibility

- Unique title and meta description; Open Graph + Twitter metadata; canonical URL
- Descriptive content, semantic section structure, responsive imagery, descriptive alt text, and branded SVG favicon
- `WebSite` and `FAQPage` structured data
- Accessible native FAQ accordions, keyboard-visible focus, skip link, mobile menu, and modal enquiry dialog
- Staging site **deliberately noindex** via `robots.txt`, HTML robots tags and Cloudflare Pages `_headers` to keep sample property content out of live Google results.

## Production launch checklist

1. Replace sample imagery with properly licensed property photos and verified room / occupancy / amenities data.
2. Supply confirmed address, nearby attractions with actual drive times, maps, operator identity, email and phone.
3. Publish genuine consented guest reviews if any; only then consider valid review/rating structured data.
4. Provide approved rates, deposit, tax, cancellation policy, check-in/out times, and actual house rules.
5. Connect booking availability, payment provider and an enquiry backend or verified inbox; provide privacy notice, secure handling and retention rules for submitted personal data.
6. Set custom production domain and correct canonical / OG URLs and images.
7. Remove **all** staging noindex directives and the robots disallow **only when production content is approved**; add an accurate sitemap, submit to Google Search Console, and monitor indexing.
8. Test forms, email delivery, booking edge cases, keyboard navigation, mobile breakpoints, image loading, and Core Web Vitals in production.

Do not reuse the sample site as a verified commercial listing without these changes.
