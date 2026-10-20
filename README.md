# Clipword dictionary packs

Offline dictionary packs for the Clipword Android app (a vocabulary flashcard app). The app downloads them by itself from the latest release; there's nothing to install by hand.

Each release has, per language, a `<lang>-manifest.json` (version, size, SHA-256 checksums, sources and licence) and a gzipped SQLite file.

## Sources and licences

The packs are reduced versions of open dictionaries and are shared under the same licences:

- **Japanese:** [JMdict](https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project), property of the Electronic Dictionary Research and Development Group, used in conformance with the [Group's licence](https://www.edrdg.org/edrdg/licence.html) (CC BY-SA 4.0). Converted with [jmdict-simplified](https://github.com/scriptin/jmdict-simplified).
- **German:** [Wiktionary](https://en.wiktionary.org), extracted by [kaikki.org](https://kaikki.org) with wiktextract (Tatu Ylonen, "Wiktextract: Wiktionary as Machine-Readable Structured Data", LREC 2022). CC BY-SA 4.0 and the GNU FDL.

Each release's notes carry the exact source versions and attribution text.
