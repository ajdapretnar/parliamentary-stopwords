# Parliamentary stopwords

A collection of parliamentary stopwords. Parliamentary speech is often very structured, using rhetorical devices such as "My hon. friend" or "Esteemed colleague" ("Spoštovani kolega").

# British parliamentary stopwords

A collection of British parliamentary stopwords, extracted from the ParlaMintGB 4.0 corpus.

- [GBparl_stopwords-empirical.txt](GBparl_stopwords-empirical.txt): manually compiled list of stopwords, based on empirical analysis of parliamentary debates. They don't require lemmatization beforehand but we recommend using it.
- [GBparl_stopwords-procedural.csv](GBparl_stopwords-procedural.csv): keywords, extracted from the NoSketch Engine by comparing ParlaMintGB 4.0 to ukWaC (British Web). These words are strictly procedural. Scores assigned are the [simple maths score](https://www.sketchengine.eu/wp-content/uploads/2015/04/2009-Simple-maths-for-keywords.pdf) from NoSke.
- [GBparl_stopwords-additional.csv](GBparl_stopwords-additional.csv): additional keywords, extracted from the NoSketch Engine by comparing ParlaMintGB 4.0 to ukWaC (British Web). These words (mainly adjectives) had high scores but are not related strictly to parliamentary speech. However, MPs tend to use more such adjectives on average. Scores assigned are the [simple maths score](https://www.sketchengine.eu/wp-content/uploads/2015/04/2009-Simple-maths-for-keywords.pdf) from NoSke.

# Slovenian parliamentary stopwords

Slovenian parliamentary stopwords, extracted from the ParlaMintSI 4.0 corpus.

- [SIparl_stopwords-empirical.txt](SIparl_stopwords-empirical.txt): : manually compiled list of stopwords, based on empirical analysis of parliamentary debates. They require lemmatization beforehand (nominative nouns and infinitives only).