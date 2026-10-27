---
name: astrocartography-lines
description: Check which of a person's astrocartography lines run through a place. Use when the user asks about astrocartography or an astro map, whether a city or country sits on one of their planetary lines, what moving to or travelling to a place would mean for their chart, or wants to see their lines on a map.
---

Use the ELA Map connector's `show_my_lines` tool. It answers from the person's birth details with geography only: which lines (Sun through Pluto on the MC, IC, AC and DC angles) run through a place. It also returns a small map card and one button that opens the full map on ELA Map.

1. Get the birth details before calling the tool. You need the birth date and the birth place. The birth time is optional, but lines depend on it, so ask for it once and say so. If the person doesn't know it, go ahead without it. Never guess a date, time or place.
2. If the person named a place they are thinking about (moving to, visiting, living in), pass it as `target_place`, written the way they wrote it (city and region or country). If they named no place, leave `target_place` out: the tool then names the one line that runs closest to a major city.
3. Call `show_my_lines`. Pass the birth place the way the person wrote it, with city and country.
4. Let the card carry the map. Reply with the geography in a sentence or two: which lines run through or near the place, and how close. Don't paste the full tool output, and don't add readings the tool did not return.
5. Tell the person the button opens all of their lines on ELA Map with their details carried over, the link is valid for 24 hours, and a free ELA Map account opens the full map.
6. If the tool returns an error or says the daily limit was reached, say so plainly and suggest trying again later. Don't invent lines. If the ELA Map connector isn't connected, ask the person to turn it on from the connectors menu.

The birth details are only used to answer the question. Don't ask for anything else, such as an email address.
