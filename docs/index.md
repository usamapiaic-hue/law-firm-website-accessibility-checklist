# Law Firm Website Accessibility Checklist

A practical accessibility checklist for law firm websites, organised by where the problem usually lives and who can fix it. Published by [Legal Web Agency](https://legalwebagency.com/).

An accessible website lets people who use screen readers, keyboards, magnification or captions contact the firm as easily as anyone else. For a law firm that matters for two reasons: some prospective clients have disabilities, and website accessibility lawsuits under the ADA are common in the United States. This checklist follows the Web Content Accessibility Guidelines (WCAG) 2.1 at level AA, which is the standard most courts and settlements refer to. It is general information, not legal advice. For the background, read our guide: [is your law firm website ADA compliant?](https://legalwebagency.com/law-firm-website-ada-compliant/)

## Before you start

- Automated checkers find only part of the problems. A real person testing with a keyboard and a screen reader finds the rest.
- "Accessibility overlay" widgets that promise one-line compliance do not fix the underlying code, and firms using them have still been sued.
- Fix the pages that lead to a consultation first: the homepage, practice pages, attorney bios and the contact page.

## 1. Text and images (content editors)

| Check | Pass condition |
|-------|----------------|
| Image alt text | Every meaningful image has alt text that says what it shows; decorative images have empty alt |
| Attorney photos | Alt text names the person, e.g. "Jane Doe, partner" |
| Headings | One H1 per page, then H2 and H3 in order, never chosen for size alone |
| Link text | Says where it goes ("Read our car accident guide"), not "click here" |
| PDFs | Forms and guides are tagged PDFs, or the same content exists as a web page |
| Video | Captions on every video; a transcript for long ones. See [law firm website video](https://legalwebagency.com/law-firm-website-video/) |

## 2. Colour and design (designer)

| Check | Pass condition |
|-------|----------------|
| Text contrast | At least 4.5:1 for normal text, 3:1 for large text |
| Buttons and form borders | Visible against the background (3:1) |
| Colour alone | Never the only way to show meaning (for example, red form errors also have text) |
| Zoom | Page still works at 200% zoom with no sideways scrolling |

Our guides to [law firm website colors](https://legalwebagency.com/law-firm-website-colors/) and [law firm website fonts](https://legalwebagency.com/law-firm-website-fonts/) cover choices that look professional and pass contrast.

## 3. Keyboard and navigation (developer)

- Every menu, button and form field can be reached and used with the Tab key alone.
- A visible focus outline shows where the keyboard is.
- A "skip to content" link is the first focusable item.
- Pop-ups and chat widgets can be closed with the keyboard and do not trap focus.
- Mobile menus open and close with a keyboard and announce their state.

## 4. Forms (developer and intake)

The contact form is the most important page on the site for a law firm, and the most common place accessibility breaks.

- Every field has a visible label, not just placeholder text.
- Required fields are marked in text, not only with colour or an asterisk.
- Errors are described in words next to the field and announced to screen readers.
- CAPTCHAs offer an accessible alternative.
- The phone number is a tappable link, so callers have a second way in.

See our guides to the [law firm website intake form](https://legalwebagency.com/law-firm-website-intake-form/) and [law firm contact page design](https://legalwebagency.com/law-firm-contact-page-design/).

## 5. Structure and code (developer)

- The page language is set (`<html lang="en">`, plus `lang="es"` on Spanish pages). See [bilingual law firm websites](https://legalwebagency.com/bilingual-law-firm-website/).
- Landmarks (header, nav, main, footer) are used so screen readers can jump between sections.
- Page titles are unique and descriptive.
- Accordions, tabs and sliders use proper ARIA attributes, or are replaced with simpler patterns.

## 6. Keep it accessible

Accessibility breaks quietly when new pages, plugins or designs are added. Add a short check to your routine: test new pages with a keyboard, run an automated checker after updates, and review the contact form each quarter. See [law firm website maintenance](https://legalwebagency.com/law-firm-website-maintenance/).

If you are planning a redesign, build accessibility in from the start; it costs far less than fixing it later. See the [law firm website redesign guide](https://legalwebagency.com/law-firm-website-redesign-guide/).

## An accessibility statement

Publish a short accessibility statement: the standard you aim for (WCAG 2.1 AA), a phone number and email for anyone who has trouble using the site, and the date of the last review.

## Other free checks

Our free [law firm website scan](https://legalwebagency.com/free-website-scan/) does not test accessibility. It checks titles, H1s, schema, robots.txt, llms.txt, the sitemap, the mobile viewport and click-to-call, plus common bar advertising wording problems, so it is a useful companion to the accessibility review above.

---

*Published by Legal Web Agency, a website design and SEO studio for law firms. General information, not legal advice.*
