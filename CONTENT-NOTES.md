# Profile content to complete

This revision uses the existing public profile as its factual source. Bracketed copy in the current-role panel is explicitly a placeholder, not a claim.

Before publishing:

- Replace the Mighty Jaxx role-details block with a short remit statement and 2–3 verified achievements. Include scope, a decision or challenge, and a concrete outcome. Remove the “Role details · placeholder” label.
- Add dates and one specific contribution for each previous role when available. These are HTML comment placeholders, so the current page does not display invented dates.
- Confirm the three focus-area descriptions match your preferred positioning. Add your own leadership principles and examples if desired.
- Supply a professional portrait if you want to replace the existing conference photograph. Update the caption, alt text, and sharing image together.
- Supply your LinkedIn profile URL. No guessed URL or inactive LinkedIn button has been added.
- Add official event links, recordings or slides, and approved session takeaways. Existing talk titles and event details are preserved.
- After the 29 September 2026 event, update its presentation when materials are ready. A small script changes the label from “Upcoming speaking” to “Selected speaking” after noon Singapore time on the event day; the rest of the page works without JavaScript.

## Implementation

The page remains a self-contained HTML file with inline CSS, existing local photographs and no build process or external font dependencies. Update `index.html` and keep `images/` beside it. The canonical URL and sharing metadata point to the existing Vercel domain.

Local preview: `python3 -m http.server 8765 --bind 127.0.0.1` from this directory, then open http://127.0.0.1:8765.
