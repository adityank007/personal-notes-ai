# Organization guide

## Choose a home

- **Travel:** `travel/YYYY/YYYY-MM-DD-destination/README.md`. Use the trip's start date and a short destination slug; the year is the start year. Example: `travel/2026/2026-10-07-monterey-carmel/README.md`.
- **Dated research:** `research/topic/YYYY-MM-DD-subject/README.md`. Use the original publication date; record later verification dates inside the document.
- **Evergreen notes:** `notes/topic/README.md`. Add named Markdown pages when a topic grows rather than forcing every note into a date hierarchy.
- **Assets:** create an `assets/` folder beside the page only when needed. Use relative links, descriptive filenames, and only material appropriate and licensed for public sharing.

Use lowercase kebab-case folder/file names, ISO dates (`YYYY-MM-DD`), and `README.md` for each folder's landing page. Do not create empty placeholder trees. Add categories only when they have a clear purpose.

## Keep navigation simple

- Root README: categories and a short featured list, not the full contents of every note.
- Category README: links to every published item in that category; newest trips/research first.
- Item README: a self-contained page someone can share directly.
- Prefer relative internal links. If moving an established page later, leave a short pointer at its old location when practical.

## Keep research useful

Start with the purpose, recommendation, scope and last-checked date. Separate verified facts from estimates, judgments and unresolved questions. Cite primary sources near important claims; disclose blocked or unverified details. Label prices with currency and note taxes/fees where known. Do not imply reservations or availability have been confirmed unless they have.

For travel, include the timezone, arrival/departure assumptions, a manageable itinerary, alternatives that replace activities, a budget and a booking checklist. Use [the trip template](templates/trip.md).

For comparisons, include decision criteria, tradeoffs, sources and open questions. Use [the research template](templates/research.md).

Update documents in place and record significant changes briefly in the document. Git history preserves previous versions; avoid duplicate `final-v2-new` copies. Keep completed trips at their original paths and mark them historical when appropriate.

## Public-sharing check

Before committing:

- Remove secrets, tokens, reservation/confirmation numbers, private addresses, IDs and private contact details.
- Include personal dates or itinerary details only when intended for public sharing; a generic name does not make a public repository private.
- Avoid hotel room/location details, personal screenshots and embedded file metadata containing sensitive information.
- Verify relative links, source URLs, dates and obvious pricing inconsistencies.
- Ensure copied content and images can legally be shared. Prefer original summaries and source links.
- Stage only the intended repository files, never unrelated workspace files.

If a secret is accidentally published, deleting the current file does not erase Git history; revoke/rotate it and address the history separately.
