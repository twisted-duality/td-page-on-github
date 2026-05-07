# Twisted Duality

The official website + radio player for **Twisted Duality** (TD), a music
brand under [AFEST Studio](https://afest.io).

🌐 **Live**: [twysted.afest.io](https://twysted.afest.io)
📻 **Radio**: [twysted.afest.io/radio/](https://twysted.afest.io/radio/)

## Brand names

The brand exists in two languages:

- **Twisted Duality** / **TWYSTED** (English wordmark)
- **双極の螺旋** / *Sōkyoku no Rasen* — "Spiral of the Two Poles" (Japanese wordmark)

**RE/IMAGINED** is a remix collection released under Twisted Duality.

### Internal naming conventions (not brand names)

These are catalog shorthands the team uses, like *FB* for *Facebook* —
recognizable references, not separate trademarks:

- **TD**, **TW-DU**, **TW_DU** — short forms of *Twisted Duality*
- **双極螺旋**, **双螺旋** (*Sōrasen*), **RS**, **SK-RS**, **SK_RS** — short forms of *双極の螺旋*
- **TDo** — original productions
- **TDre** — RE/IMAGINED remix collection releases
- **TDmo** — Motion Memories (live sets, mixes, visuals)

See [TRADEMARK.md](TRADEMARK.md) for the full breakdown.

## Stack

- Static site, hosted on GitHub Pages with custom CNAME (`twysted.afest.io`)
- Vanilla HTML / CSS / JavaScript — no build step
- Audio engine: native `<audio>` element + Blob URLs
- Asset cascade: Cloudflare R2 → local repo → CDN edge fallback
- Custom typography (TD brutalist style guide)
- Multi-language support across UI elements

## Structure

```
.
├── index.html              # Main landing page
├── CNAME                   # GitHub Pages custom domain
├── tower.svg               # TD tower mark
├── elements/               # Brand assets — logos, backgrounds, sub-brand graphics
├── fonts/                  # Custom typography
├── sounds/                 # UI SFX (button clicks, ambience)
├── Space ideas/            # Experimental backgrounds + WIP visuals
├── LICENSE                 # Apache 2.0 (covers source code only)
├── TRADEMARK.md            # Trademark notice for TD / Twisted Duality marks
└── README.md               # This file
```

## License

Source code in this repository is licensed under the
**[Apache License 2.0](LICENSE)**.

## Trademarks

**Twisted Duality**, **TD**, **TDo**, **TDre**, **TDmo**, the TD logo,
and associated visual marks are trademarks of AFEST Studio.

The Apache 2.0 code license **does not** grant rights to use these marks.
See [TRADEMARK.md](TRADEMARK.md) for full terms.

## Audio content

Audio recordings, mixes, stems, and musical compositions referenced or
streamed from this site are **separately copyrighted** and are
**All Rights Reserved** unless individually marked otherwise. The Apache 2.0
code license does not grant any rights to audio content.

## Contributing

This is the canonical home of the TD website. External contributions are
not actively solicited at this stage. Forks for personal study are welcome
under the Apache 2.0 terms — please respect the trademark notice when
publishing derivatives.

## Contact

AFEST Studio — see [afest.io](https://afest.io) for current contact channels.

---

*Maintained under AFEST Studio.*
