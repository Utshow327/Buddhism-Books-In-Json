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
  "dn": {
    "text_uid": "dn",
    "root_title": "Dīghanikāya",
    "translation_title": "Long Discourses",
    "translation_subtitle": "A faithful translation of the Dīgha Nikāya",
    "source_url": "https://github.com/suttacentral/bilara-data/tree/published/translation/en/sujato/sutta/dn",
    "author": {
      "author_name": "Bhikkhu Sujato",
      "collaborators": []
    },
    "is_published": true,
    "edition_urls": [
      "https://suttacentral.net/dn"
    ]
  },
  "mn": {
    "text_uid": "mn",
    "root_title": "Majjhimanikāya",
    "translation_title": "Middle Discourses",
    "translation_subtitle": "A lucid translation of the Majjhima Nikāya",
    "source_url": "https://github.com/suttacentral/bilara-data/tree/published/translation/en/sujato/sutta/mn",
    "author": {
      "author_name": "Bhikkhu Sujato",
      "collaborators": []
    },
    "is_published": true,
    "edition_urls": [
      "https://suttacentral.net/mn"
    ]
  },
  "sn": {
    "text_uid": "sn",
    "root_title": "Saṁyuttanikāya",
    "translation_title": "Linked Discourses",
    "translation_subtitle": "A plain translation of the Saṁyutta Nikāya",
    "source_url": "https://github.com/suttacentral/bilara-data/tree/published/translation/en/sujato/sutta/sn",
    "author": {
      "author_name": "Bhikkhu Sujato",
      "collaborators": []
    },
    "is_published": true,
    "edition_urls": [
      "https://suttacentral.net/sn"
    ]
  },
  "an": {
    "text_uid": "an",
    "root_title": "Aṅguttaranikāya",
    "translation_title": "Numbered Discourses",
    "translation_subtitle": "A sensible translation of the Aṅguttara Nikāya",
    "source_url": "https://github.com/suttacentral/bilara-data/tree/published/translation/en/sujato/sutta/an",
    "author": {
      "author_name": "Bhikkhu Sujato",
      "collaborators": []
    },
    "is_published": true,
    "edition_urls": []
  },
  "thag": {
    "text_uid": "thag",
    "root_title": "Theragāthā",
    "translation_title": "Verses of the Senior Monks",
    "translation_subtitle": "An approachable translation of the Theragāthā",
    "source_url": "https://github.com/suttacentral/bilara-data/tree/published/translation/en/sujato/sutta/kn/thag",
    "author": {
      "author_name": "Bhikkhu Sujato & Jessica Walton",
      "collaborators": ["Bhikkhu Sujato", "Jessica Walton"]
    },
    "is_published": true,
    "edition_urls": [
      "https://suttacentral.net/thag"
    ]
  }
}
