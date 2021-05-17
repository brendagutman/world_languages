This data contains data obtained from [Glottolog](https://glottolog.org/), a comprehensive reference for the world's languages, supplemented by information scraped from Wikipedia.

column name | description
-----------|----------
pk | primary key
id | Glottocode associated to the language
name | Language name
latitude | 
longitude |
speakers_count | Number of speakers (obtained from Wikipedia); Warning - lots of missing values.
father_pk | The primary key of this language's father language
family_pk | The primary key of this language's family
level | dialect, language, or family
child_family_count | the total number of descendant families 
child_language_count | the total number of descendant languages
child_dialect_count | the total number of descendant dialects
macroareas | An area of the globe, as defined by [glottolog](https://glottolog.org/glossary#macroarea)
status | [The Agglomerated Endangerment Status](https://glottolog.org/langdoc/status), a measure of how endangered a language is.