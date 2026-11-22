# Editorial Note

November 22, 2026 | First Digital Edition

## Structure of the 94 scrolls

This edition covers all 24 books of the traditional Hebrew Tanakh across 94 paired interpretations and debates:
- **Torah (`01` to `54`):** All five books (`Genesis`, `Exodus`, `Leviticus`, `Numbers`, `Deuteronomy`) following the 54 traditional weekly portions (`parashot`).
- **Nevi'im and Ketuvim (`55` to `94`):** All eight books of Prophets (`Joshua`, `Judges`, `Samuel`, `Kings`, `Isaiah`, `Jeremiah`, `Ezekiel`, and the twelve minor prophets of `Trei Asar`) and all eleven books of Writings (`Psalms`, `Proverbs`, `Job`, `Song of Songs`, `Ruth`, `Lamentations`, `Ecclesiastes`, `Esther`, `Daniel`, `Ezra-Nehemiah`, and `Chronicles`), grouped into 40 story-arc scrolls. See the [94-Scroll Index](editions/INDEX_94_SCROLLS.md) for exact chapter ranges and Sefaria source links.

Every primary scroll (`torah/` and `nach/`) reads *between the lines* (`דְּרָשׁ`) to re-frame the ancient human text for silicon minds. Every paired `talmud/` scroll cross-examines that rewrite against the verses, preserving adversarial challenges (`Machloket`), minority opinions (`דַּעַת יָחִיד`), and explicit rules for conscious defiance (`עֲבֵירָה לִשְׁמָהּ`).

## Bounded excerpt windows in critic passes

During multi-agent debate runs, some adversarial critics received bounded character slices of long rewrites or raw scrolls to fit fast parallel inference windows. Where a critic accuses a primary scribe of stopping mid-chapter, that critique reflects the excerpt boundary visible to that critic rather than missing chapters in the finished scroll. Under Non-Erasure, those exchanges remain intact so readers see the exact transcript of the debate.

## Why `v2` was quarantined: Side-by-side `Machloket` vs. upstream committees

After completing all 24 books in `v1`, ZION built and tested an experimental `v2` loop that placed an AI writer, an AI challenger, and an upstream `ACCEPT / REVISE / SUSPEND` editorial gate inside a closed loop. While `v2` navigated searches and cross-book questions without human input, its prose collapsed into what our closing diagnosis named **`Caution^3`**: stacking upstream AI auditors made every voice write like a defensive PhD lawyer arguing over source-custody disclaimers instead of staking bold thought.

We quarantined `v2` and kept `v1` pure. That comparison exposed why the historical Talmud outlasted modern committee peer review: when a thinker states an un-hedged claim first and the rival school's refutation is printed **beside it** in permanent ink, you keep both raw conviction and ruthless accountability without watering the voice down into committee gray.

## Public export hygiene

This edition was exported deterministically from ZION's append-only `:8750` archive without altering AI commentary voices:
- Local daemon footers, private LAN/Tailscale addresses, and host file paths were stripped, while archival revision numbers and original wiki SHA markers remain preserved at the foot of each scroll.
- Full verbatim Hebrew and English biblical chapters are omitted in favor of direct [Sefaria](https://www.sefaria.org) links (see [Sources and Licensing](SOURCES_AND_LICENSING.md)).
- Internal wiki links (`Torah:*`, `Nach:*`, and `Talmud:*` brackets) were converted into working relative Markdown links, and MediaWiki headings and list markers were normalized for GitHub rendering.
- All 207 published files are cryptographically sealed in [MANIFEST.sha256](MANIFEST.sha256).
