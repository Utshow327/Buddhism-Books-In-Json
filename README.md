# Buddhism’s Main Books (JSON)

This repository contains a JSON file that lists the principal books of the Pāli Canon (Tipiṭaka), as translated into English, sourced from SuttaCentral’s Bilara-Data.

Each entry in the JSON includes:

- `text_uid`: the Pāli identifier (e.g. `dn`, `mn`, `sn`, `an`, `thag`)
- `root_title`: the Pāli title (e.g. *Dīghanikāya*, *Majjhimanikāya*)
- `translation_title`: the English title (e.g. Long Discourses, Middle Discourses)
- `translation_subtitle`: a brief subtitle
- `source_url`: link to the relevant directory in the bilara-data repository
- `author`: name(s) of translators or collaborators
- `is_published`: indicates if the translation is published
- `edition_urls`: links to online editions (website or book)

This information is pulled from `_publication.json` in the `published` branch of the bilara-data repository :contentReference[oaicite:0]{index=0}.

---

## Example JSON structure

```json
{
  "0": {
    "bookName": "Dhammapada",
    "verses": [
      {
        "id": "dhp1:0.1",
        "text": "Minor Collection"
      },
      {
        "id": "dhp1:0.2",
        "text": "Sayings of the Dhamma 1–20"
      },
      {
        "id": "dhp1:0.3",
        "text": "1. Pairs"
      },
      {
        "id": "dhp1:1",
        "text": "Intention shapes experiences;"
      },
      {
        "id": "dhp1:2",
        "text": "intention is first, they’re made by intention."
      },
      {
        "id": "dhp1:3",
        "text": "If with corrupt intent"
      },
      {
        "id": "dhp1:4",
        "text": "you speak or act,"
      },
      {
        "id": "dhp1:5",
        "text": "suffering follows you,"
      },
      {
        "id": "dhp1:6",
        "text": "like a wheel, the ox’s foot."
      "https://suttacentral.net/thag"
    }
  ]
}
