# Bengaluru Namma Metro — Network Map

An interactive, colour-coded map of Bengaluru's Namma Metro. It covers operational, under-construction, approved and proposed lines, with station details and a 2011–2032 timeline.

**Live:** https://nchand02.github.io/bengaluru-metro-map/

## What's on the map
- **Operational:** Purple, Green, Yellow, and the Pink Line elevated section (from 14 Nov 2026), 103.6 km in total
- **Under construction:** Pink Line underground section, Blue Line (Silk Board – KR Puram – Airport)
- **Approved:** Orange and Grey lines (Phase 3)
- **Awaiting approval:** Red Line (Phase 3A, Sarjapur – Hebbal)
- **Proposed:** 8 Phase 4 suburban corridors

Status as of 13 Nov 2026. Future dates are official targets as reported, and they often slip.

## Notes
- This is an **unofficial** compilation from public reports. It is not affiliated with or endorsed by BMRCL.
- Station positions are approximate. Routes for the approved and proposed lines are indicative only.
- The page is one self-contained `index.html` file, with no build step and no external dependencies. It is hosted on GitHub Pages.
- **Accessibility:** keyboard-operable controls, screen-reader labels, and a full text version of the map content (stations in order, timeline, FAQ). It passes an automated WCAG 2 AA check (axe-core).
- **Search and AI tools:** structured data (Article and FAQ, schema.org), Open Graph and Twitter cards, `sitemap.xml` and `llms.txt`.
- **Security:** a strict Content Security Policy (hash-locked script, no network requests), no cookies, forms, trackers or third-party code. See [SECURITY.md](SECURITY.md).

Author: [Navdeep Singh Chander](https://nchand02.github.io/bio/)

## License
GPL-3.0 — see [LICENSE](LICENSE).
