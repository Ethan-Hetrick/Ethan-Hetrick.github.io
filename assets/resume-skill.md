# Compact Two-Page CV PDF

Convert the user's Markdown CV into a polished, readable two-page PDF.

## Source of truth

Use the supplied `.md` CV as the authoritative content. Do not rewrite, shorten, add, or remove content unless explicitly requested.

## Layout

* US Letter, exactly 2 pages.
* Single-column layout.
* Aim for both pages to be visually well filled and reasonably balanced.
* Use narrow margins, approximately 0.35–0.40 inches.
* Prefer reducing paragraph spacing and margins before reducing font size.
* Body text should remain comfortably readable; target approximately 7.1–7.5 pt minimum.
* Use compact line spacing without crowding.
* Add visible breathing room:

  * before and after major section headings;
  * between job, education, and other major entries.
* Avoid unnecessary forced page breaks, but use one when it improves page balance.

## Styling

* Name: centered, bold, approximately 16–17 pt.
* Professional title: centered beneath name.
* Contact information: centered and compact.
* Major section headings: bold, dark navy, approximately 9.5–10 pt.
* Do **not** place boxes, borders, or rules around section headings.
* Entry titles: bold.
* Dates/location lines: italic where appropriate.
* Body: serif font.
* Headings: sans-serif font.
* Use conventional bullet indentation and compact spacing.
* Include a subtle centered footer:
  `Name | CV | page number`

## Content formatting

Preserve:

* Markdown bold and italics.
* Scientific-name italics where present.
* Numbered publications/presentations.
* Bulleted experience, project, skill, and service entries.
* URLs where present.

Use simple ASCII-compatible substitutions only when required for reliable PDF rendering.

## Quality control

After generating the PDF:

1. Confirm it is exactly 2 pages.
2. Render both pages to images and visually inspect them.
3. Check that:

   * neither page has excessive unused space;
   * text is not uncomfortably small;
   * headings and entries have enough separation;
   * nothing is clipped or overlapping;
   * page breaks occur at sensible locations.
4. Adjust spacing, margins, and page distribution iteratively until the two pages look balanced.
5. Return the final PDF.

