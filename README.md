# ELA Map for Claude

ELA Map draws your birth chart onto the Earth. Every planet sits on four lines around the globe, and astrocartography reads a place by the lines that run near it. This plugin teaches Claude to ask about your birth details, check them against a place you are considering, and show you a small map of the line.

## Use it

Connect the ELA Map connector, then ask something like:

- Do any of my astrocartography lines run through Berlin? I was born 11 Nov 1994 at 11:11 in Lisbon, Portugal.
- I was born 22 Sep 1985 at 6:40 AM in Toronto, Canada. Are any of my lines near Tokyo?
- Show my astrocartography lines. I was born 3 March 1990 in Sydney, Australia; I don't know the time.

Claude answers with the geography and a map card. The button on the card opens all of your lines on [ELA Map](https://elamap.com) with your details carried over. A free ELA Map account opens the full interactive map, plain-language readings and location reports.

## What is in this plugin

- One skill, `astrocartography-lines`, which tells Claude when to use the connector and how to ask for birth details.
- One connector reference in `.mcp.json` that points at `https://elamap.com/api/mcp`. It needs no account or credentials. It contains no scripts, hooks or commands.

## Data

When you ask a question, Claude sends your birth date, birth time (if you give one), birth place and the place you ask about to `https://elamap.com/api/mcp`, run by Spirit River Inc. The answer is geography only. No account is created and the birth details are not stored. The link on the card carries your details to ELA Map so you do not have to type them again, and it expires after 24 hours. See the [privacy policy](https://elamap.com/privacy). Questions: support@elamap.com.

## License

MIT, see [LICENSE](LICENSE).
