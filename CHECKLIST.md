# The Cutting Edge Belfast — build checklist

Audit: 16 September 2026. Existing design and stack retained.

## Implementation

- [x] Full homepage, gallery.html, terms.html and privacy.html; shared styling.
- [x] Opening fade/slide animation with reduced-motion support.
- [x] Three full-bleed hero images, dark fallback/overlay and 5-second crossfade. First eager; others lazy. Pause/play control.
- [x] Glass Google widget uses verified aggregate, or an honest profile link when count unavailable.
- [x] Service photographs, three gallery images, supporting imagery, alt text, dimensions and responsive image variants.
- [x] No forms, reCAPTCHA, rating gate or feedback funnel. Contact has two prominent native Call/Email buttons.
- [x] Plain Leave a Review buttons link directly to the identified Google Place ID. Separate read-reviews link.
- [x] Responsive lazy Google map on every page near the footer.
- [x] Footer legal links and social SVGs; unverified discovery links labelled as searches.
- [x] Mobile menu, visible phone action, focus styles and at least 44px principal controls.
- [x] Original images and downloaded business assets remain on Desktop; responsive copies included.

## Verification

- [x] Homepage inspected at 375px, 768px and 1440px. No horizontal document overflow.
- [x] All supporting pages inspected at 375px, 768px and 1440px; no horizontal document overflow.
- [x] Local image paths/internal links resolved; every homepage image decoded successfully.
- [x] Mobile menu opens and closes after navigation.
- [x] Three-slide rotation and pause control exercised in a browser.
- [x] No page JavaScript errors in interaction checks.
- [x] Contact/review screenshots inspected; native links verified without calling, emailing or posting reviews.
- [x] Production deployed; all four pages, CSS and JavaScript return HTTP 200 and match local files byte-for-byte.

## Source checks and honest limitations

- Google 4.9 from 144 reviews verified. Two exact short excerpts with full names and Google-relative dates replace paraphrased testimonials.
- Google links to the official Facebook page; its phone/address/email match the business and it cross-links the Instagram account used on the site.
- All seven existing original images preserved byte-for-byte; SHA-256 baseline in verification/original-image-hashes.json. Responsive WebP copies contain the same photos.
- Services/prices replaced with the actual public Facebook haircut/restyle/clipper/razor/fringe-beard list. Invented colour, extensions and treatment pricing removed.

- Google Place ID: `ChIJpWjkLTGMMW0RKUCrgDrDiJ8`. [Read Google reviews](https://search.google.com/local/reviews?placeid=ChIJpWjkLTGMMW0RKUCrgDrDiJ8); [direct write-review link](https://search.google.com/local/writereview?placeid=ChIJpWjkLTGMMW0RKUCrgDrDiJ8). Review dates retain the relative wording Google displayed at capture.
- Social sources: https://www.facebook.com/thecuttingedgebelfast/, https://www.instagram.com/thecuttingedgebelfast/
- 4K enhancement: NOT claimed. The image-tool trial in this workflow returned a smaller, reinterpreted image. Faithful source images are retained and optimized; missing detail is not invented.
- Legal pages are explicitly labelled drafts, as requested. Owner approval is needed for final business policies.
- Google/Meta can require login, cookies or a human check. Verification is a dated snapshot, not a guarantee of permanent third-party availability.

## Evidence

`verification/business.json`, `google-listing.json`, `google-details.json`, `asset-sources.json`, `browser-checks.json`, `interactions.json`, `static-checks.json`, and screenshots. Source captures and originals are excluded from the public Vercel website, but retained locally and in GitHub.

## Published build

Live: https://the-cutting-edge-belfast-demo.vercel.app

GitHub: https://github.com/scaledsolutionsnz-sketch/the-cutting-edge-belfast-demo

Local folder: /Users/wiremubartlett/Desktop/builds/the-cutting-edge-belfast-demo

## Image shape correction

- [x] Responsive image heights override fixed HTML pixel-height attributes.
- [x] Service photographs share the same rendered dimensions at 375px, 768px and 1440px.
- [x] All homepage images checked for stretched rendering; none detected.
- [x] No horizontal overflow at those sizes.
- [x] Source photos unchanged; cover cropping preserves image proportions.

Evidence: `verification/image-shapes.json` and `verification/cards-*.png`.
