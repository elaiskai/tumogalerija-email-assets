# TUMO Gallery — Theo Bardsley / Echoes of the Room

English-language campaign prepared 13 September 2026.

Subject: Theo Bardsley: from residency to Echoes of the Room

Preheader: A recent residency in Vilnius, a new solo exhibition, and six works to discover.

## Klaviyo import

Import newsletter.html through Content → Templates → Email templates → Import. All eight image sources use absolute public GitHub raw URLs in this repository. No image ZIP, separate image upload, or URL replacement is needed. The footer already uses Klaviyo’s {% unsubscribe_link %} tag. The hidden preheader is included; set the subject in the campaign setup.

newsletter.txt is the matching plain-text version. preview.html is an offline preview using the bundled assets. preview-desktop.png and preview-mobile.png show the approved composition.

The files are publicly hosted in this repository. They have not been imported, scheduled or sent in Klaviyo. If sending later, recheck current artwork availability.

## Verified source information

- Exhibition and residency: https://tumogalerija.lt/en/collections/theo-bardsley-echoes-of-the-room-exhibition
- Live collection: https://tumogalerija.lt/en/collections/theo-bardsley-echoes-of-the-room-exhibition/products.json?limit=50
- Gallery address, contact email and visiting hours: https://tumogalerija.lt/en/pages/contacts
- Artist biography: official artwork pages linked in the email.
- Klaviyo custom HTML import: https://help.klaviyo.com/hc/en-us/articles/115005254068
- Klaviyo unsubscribe link tag: https://help.klaviyo.com/hc/en-us/articles/4408802648731

The residency began on 24 August; open studio visits took place on 3–6 September. The exhibition runs from 10 September to 11 October 2026 at TUMO Gallery, Užupio St. 28, Vilnius. Admission is free. Visiting hours: Thursday–Friday 13:00–19:00 and Saturday–Sunday 12:00–18:00. Past opening and tour events are not presented as upcoming.

Theo Bardsley (b. 1997) is a London-based British figurative painter, self-taught in painting, with History of Art studies at the University of Manchester. The selected artworks are not described as created during the Vilnius residency: individual catalogue signatures include London.

## Six selected paintings

| Artwork | Year | Medium | Size | Listed price |
|---|---|---|---|---|
| The Tea House | 2026 | Oil and oil stick on canvas | 102 × 81.5 cm | €2,200 |
| Chalk | 2026 | Oil on canvas | 102 × 81.5 cm | €2,200 |
| Houseplant's | 2026 | Oil and oil stick on canvas | 102 × 81.5 cm | €2,200 |
| Self Portrait in Hackney Studio | 2026 | Oil and oil stick on canvas | 102 × 81.5 cm | €2,200 |
| Hoping They Cancel | 2026 | Oil on canvas | 51 × 41 cm | €700 |
| Heatwave | 2026 | Oil on canvas | 51 × 41 cm | €700 |

All six were listed as available on 13 September 2026. The catalogue’s spelling “Houseplant's” is retained. Sold and reserved works were excluded.

## Design and assets

The gallery logo and six product images are authentic, unaltered source files. Artwork images preserve their full composition and aspect ratio. The hero is an AI-assisted editorial expansion of the gallery’s The Tea House photograph; it is not documentary evidence of the Vilnius residency. The visitor is not identified. Original reference assets are included.

The campaign follows the official exhibition poster and gallery identity: #FCFCFC background, #020912 text, #231F20 logo/header, and #88AE73 green sampled from the poster. #E9EFE3 pale green and #E9EAE5 outer neutral are supporting choices. The website uses Nunito/Figtree; the email uses Arial/Helvetica fallbacks with live HTML text and buttons.

## Validation

The 600 px email was inspected on desktop and at 390 px and 320 px mobile widths. Eight images load, exactly six artwork cards appear, and there is no horizontal overflow. A correction pass balanced mobile headline wrapping. The GitHub delivery variant changes only image source URLs and the Klaviyo unsubscribe tag; layout and factual content remain unchanged. The final HTML is approximately 23 KB. Browser checks are not a certification across all inbox clients.

## Hero generation prompt

Tool: built-in image_gen; image editing mode, two local reference images. Source image saved as assets/editorial/hero-gallery-v2-source.png (1536 × 1024). Delivery JPEG assets/editorial/hero-gallery-v2.jpg (1536 × 1024, about 376 KB). Only format compression was applied after generation.

> Use case: compositing / editorial image editing. Asset: wide premium art-gallery email hero, landscape aspect ratio 3:2, ideally 1536x1024. Edit image 1 into a beautiful wide photographic composition through lateral outpainting and careful reframing. Image 1 is the photo to edit: a real visitor on the left looking at Theo Bardsley's The Tea House on a lightly textured off-white gallery wall. Image 2 is the exact original painting, supporting preservation reference ONLY. Keep the original painting's identity, every figure, pose, facial expression, brushwork, colors, cups, teapot, hookah and exact full composition as faithfully as possible: do not reinterpret the art, do not invent new marks, do not crop any edge of the painted canvas. Preserve the existing visitor's visible identity, black shirt and glasses. The portrait painting should be prominent on the center-right, filling about 83% of the image height, with the visitor's head and upper torso in the left foreground looking toward it. Expand the genuine off-white plaster wall on the left and right to create a wide magazine photograph, with a small amount of natural breathing room around the whole canvas. Preserve the real photo's perspective and restrained soft daylight. Rich deep red, cobalt blue and green in the untouched artwork are the dominant color accents. Elegant editorial photograph, gallery visit, tactile wall, believable subtle canvas shadow. One artwork only. No new objects, no extra people, no gallery architecture, no captions, no headline, no logos, no letters, no graphics, no frame added. This will sit immediately below live email typography. Do not create a poster or a webpage mockup; output the photograph only.
