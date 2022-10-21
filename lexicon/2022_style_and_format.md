# 2022 Style & Formatting Update

This is a metadocument meant to document the updated style and format for lexicon entries, to be used for all markdown files in this lexicon directory tree starting from 2022-Oct-01. While time is expected to convert all files, it is hoped that all current files can be converted by early 2023.

## Pre-2022 Format

### Lexicon Master Lists

#### Masterlist Mother Entries

Lexicon mother entries are direct entries within the lexicon which do not have a parent other than their initial letter. Prior to October 2022, these are formatted roughly as follows:

```plaintext
+ **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_
```

This format renders roughly as:

+ **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_

These entries are:

1. Left-aligned, using the \+ symbol to indicate an _unordered list_, or a list using bullet points, rather than an _ordered list_ using numbers.
2. The _lexeme_ is formatted in **strong** format, with a _full stop_ or _period_ separating verbal stems from their gerund endings.
3. The _part of speech_ is formatted in **emphasis** format, with no other indicator or separator.
4. A list of _glosses_ is provided with a comma between sub-senses and a semicolon between major senses. Some major senses are listed as separate entries.
   1. A list of _tags_, most notably an **attested date**, follows any glosses or senses it can be meaningfully applied to.
5. _Usage_ and other _notes_ trail at the end of the lexicon entry.

### Masterlist Daughter Entries

A daughter entry is any word which is dependent on a mother entry, or which derives from at least one other lexeme. Based on the example of **alma.ru** above, here is an example of daughter entries:

```plaintext
+ **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_
  + **[almán](a/almán.md)** _noun_ leader by circumstance, acting leader
  + **[almatax](a/almatax.md)** _noun_ leader by profession, manager
  + **[alnom](a/alnom.md)** _noun_ a rule or law
```

As above, this renders roughly as:

+ **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_
  + **[almán](a/almán.md)** _noun_ leader by circumstance, acting leader
  + **[almatax](a/almatax.md)** _noun_ leader by profession, manager
  + **[alnom](a/alnom.md)** _noun_ a rule or law

In general, a daughter lexeme varies from a mother lexeme only in that it is nested within the _unordered list_ structure, and may contain all of the same information as its mother entry.

### Lexicon Subpage Lists

In contrast to the masterlists, containing all words, subpages may list subsets of words, say those beginning with a single letter or filling a specific semantic field. These lists are more likely to be dictionary like already, but as most of them are based off th masterlist files, this is not fully consistent.

#### Lexicon Subpage Format

Currently, the only dedicated subpage is the file `a.md`, and entries are listed in the following format:

```plaintext
+ **[almaru](a/alma.md)**
  1. (_ton verb_) leading, exercising or showing leadership
  2. ruling, interpreting rules or laws, passing judgement
  3. governing, exercising authority
  + **[almán](a/almán.md)**
    1. (_noun_) a leader, as of a group or team
    2. a leader or ruler appointed without regard for qualifications, usually for a short term until a properly qualified leader can be appointed
    3. a leader without the will to lead or govern
  + **[almatax](a/almatax.md)**
    1. (_noun_) ruler, governor
    2. manager, coach
    3. teacher, professor, preacher
    4. judge, court
  + **[alnom](a/alnom.md)**
    1. (_noun_) a rule or regulation
    2. a protocol or procedure
    3. a law
```

This format renders, roughly, thus:

+ **[almaru](a/alma.md)**
  1. (_ton verb_) leading, exercising or showing leadership
  2. ruling, interpreting rules or laws, passing judgement
  3. governing, exercising authority
  + **[almán](a/almán.md)**
    1. (_noun_) a leader, as of a group or team
    2. a leader or ruler appointed without regard for qualifications, usually for a short term until a properly qualified leader can be appointed
    3. a leader without the will to lead or govern
  + **[almatax](a/almatax.md)**
    1. (_noun_) ruler, governor
    2. manager, coach
    3. teacher, professor, preacher
    4. judge, court
  + **[alnom](a/alnom.md)**
    1. (_noun_) a rule or regulation
    2. a protocol or procedure
    3. a law

In this format, each word is listed as a single line, with each set of glosses or definitions receiving its own ordered list, with daughter entries receiving unordered list entries after the ordered list for the mother word. Parts of speech are listed along with the first gloss or definition, and are assumed to remain consistent until a new part of speech is listed.

## Post-2022 Format

From the start of this update, it is intended that all lexicon pages within the primary lexicon use a more consistent formatting that is easy to read and follow. The lexicon lists are still intended to be a lexicon and glossary, not a full dictionary, but some cues are being taken from dictionary formats.

### Lexicon Lists

Going forward, all lexicon lists should stop using mother-daughter hierarchies for words, and should instead reference related words in a parenthetical. The proposed format is as follows:

```plaintext
+ **[alma.ru](a/alma.md)** 1. (_ton verb_) ruling, leading, governing (attested 2008-Jun-22; formerly _aluma.ru_)
+ **[almán](a/almán.md)** 1. (_noun_) leader by circumstance, acting leader (cf. _almaru_)
+ **[almatax](a/almatax.md)** 1. (_noun_) leader by profession, manager (cf. _almaru_)
+ **[alnom](a/alnom.md)** 1. (_noun_) a rule or law (cf. _almaru_)
```

Which ought to render, roughly, as such:

+ **[alma.ru](a/alma.md)** 1. (_ton verb_) ruling, leading, governing (att. 2008-Jun-22; formerly _aluma.ru_)
+ **[almán](a/almán.md)** 1. (_noun_) leader by circumstance, acting leader (cf. _almaru_)
+ **[almatax](a/almatax.md)** 1. (_noun_) leader by profession, manager (cf. _almaru_)
+ **[alnom](a/alnom.md)** 1. (_noun_) a rule or law (cf. _almaru_)

1. All entries are part of an _unordered list_ denoted with a \+ symbol. Ordering of this list is manual, following the alphabetic conventions of the language in which entries are listed.
   1. In the updated lexicon, a straightforward transcription is preferred to the use of IPA or special characters for digraphs.
2. When linked to a lexicon entry page, the full dictionary form of the entry is included in the link, though the lexicon entry page should still be named based on the verb stem.
3. Each sense of the lexicon entry receives a numbered listing, helping to alleviate confusion over comma-separated and semicolon separated entries.
   1. The part of speech is _emphasis formatted_ and contained in a pair of parentheses
      1. A comma may be used to concatenate multiple parts of speech within parentheses
      2. A set of square brackest may follow these parentheses to specify a field of knowledge or context for a given sense.
   2. The list of glosses suitable to the sense is separated as makes logical sense
   3. Any parenthetical information, such as earliest attestation or older forms of a word, is contained in a pair of parentheses and located at the end of the sense to which it applies
      1. Dates should be listed as _att. YYYY-MMM-DD_, always using 3-letter month and leading 0 for dates.
      2. A reference to a related word should use the format _cf._ (confer) followed by the word, or words, in **emphasis format**.
4. A list of significant forms may be included in square brackets after either a specific sense or the end of the entry

#### Daughter Entries

Going forward, daughter entries should be reserved for expressions or set phrases which begin with or center upon the mother entry, not simply for words which share the same stem or root words.

1. A daughter entry should be a phrase or expression, rather than a single word.
2. Daughter entries should follow the rules above, except that they are indented below their mother entry.

### Dictionary Lists

The letter-based lists will now use the new rules for Dictionary Lists, which should be as follows:

```plaintext
+ **[almaru](a/alma.md)**
  1. (_ton verb_) leading, exercising or showing leadership
  2. (_ton verb_) ruling, interpreting rules or laws, passing judgement
  3. (_ton verb_) governing, exercising authority
+ **[almán](a/almán.md)** (cf. _almaru_)
  1. (_noun_) a leader, as of a group or team
  2. (_noun_) a leader or ruler appointed without regard for qualifications, usually for a short term until a properly qualified leader can be appointed
  3. (_noun_) a leader without the will to lead or govern
+ **[almatax](a/almatax.md)** (cf. _almaru_)
  1. (_noun_) ruler, governor
  2. (_noun_) manager, coach
  3. (_noun_) teacher, professor, preacher
  4. (_noun_) judge, court
+ **[alnom](a/alnom.md)** (cf. _almaru_)
  1. (_noun_) a rule or regulation
  2. (_noun_) a protocol or procedure
  3. (_noun_) a law
```

Note some differences from the lexicon:

1. Dictionary entries exclude lexical markers like the full-stop to indicate verb formation.
2. Links to related words should be included as a parenthetical _cf._ on the unordered line for the word.
3. Each ordered list entry _must_ contain a part of speech.
4. Each sense shall receive its own line.
   1. Sub-senses may be listed beneath their primary sense.

### Dictionary Pages

Dictionary pages should be formatted in a manner that makes their migration to Mediawiki as easy as possible. The Mediawiki dictionary page format being used is represented in Markdown thusly:

```plaintext
# lexeme

## Forms

1. **lexical form** (_part of speech_, _field of knowledge (optional)_) **[Tags: `#tag1` ...]
   1. definition or gloss
      + Usage Notes

### Other Forms

+ **(Applicable Sense/s)**
  + **_alternate form_** (_part of speech_) usage or definition

## Derivation

+ **(Applicable Sense/s)**
  + Derivational information

### Etymology (optional)

+ **(Applicable Sense/s)**
  + etymological information

## Related Words

+ **related word** (_part of speech_) definition or gloss
```

This format should provide the easiest translation into the preferred Mediawiki structure, though some changes may still need to be made at the time of conversion (such as stripping of the H1/title of the dictionary page).

#### Verbal Paradigms

Dictionary pages for verbs may include tables to show the primary paradigm for the verb. This should follow one of the following layouts, for _ton verbs_ or _kun verbs_. The terms _foo_ and _bar_ are used as placeholders in these paradigm templates.

##### **Paradigm for TON Verbs**

```plaintext
|          | Gerund       | Infinitive  |
|:--------:|:------------:|:-----------:|
| Positive | foo.GER      | foo         |
| Negative | foo.GER.(h)a | foo.(h)a    |

|             | Past       | Present   | Future      |
|:-----------:|:----------:|:---------:|:-----------:|
| Active      | foo.tot    | foo.ton   | foo.toçi    |
| Passive     | foo.tolot  | foo.tol   | foo.toloçi  |
```

##### **Paradigm for KUN Verbs**

```plaintext
|          | Gerund     | Infinitive |
|:--------:|:----------:|:----------:|
| Positive | fo.no.o    | foo        |
| Negative | fo.no.ya   | fo.ya      |

|         | Past   | Present | Future   |
|:-------:|:------:|:-------:|:--------:|
| C Final | bar.ns | bar.s   | bar.ykun |
| V Final | foo.ns | foo.c   | foo.kun  |
```
