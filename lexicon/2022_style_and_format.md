# 2022 Style & Formatting Update

This is a metadocument meant to document the updated style and format for lexicon entries, to be used for all markdown files in this lexicon directory tree starting from 2022-Oct-01. While time is expected to convert all files, it is hoped that all current files can be converted by early 2023.

- [2022 Style \& Formatting Update](#2022-style--formatting-update)
  - [Pre-2022 Format](#pre-2022-format)
    - [Lexicon Master Lists](#lexicon-master-lists)
      - [Masterlist Mother Entries](#masterlist-mother-entries)
    - [Masterlist Daughter Entries](#masterlist-daughter-entries)
    - [Lexicon Subpage Lists](#lexicon-subpage-lists)
      - [Lexicon Subpage Format](#lexicon-subpage-format)
  - [Post-2022 Format](#post-2022-format)
    - [Lexicon Lists](#lexicon-lists)
      - [Daughter Entries](#daughter-entries)
    - [Dictionary Lists](#dictionary-lists)
    - [Dictionary Pages](#dictionary-pages)
      - [Verbal Paradigms](#verbal-paradigms)
        - [**Paradigm for TON Verbs**](#paradigm-for-ton-verbs)
        - [**Paradigm for KUN Verbs**](#paradigm-for-kun-verbs)
  - [Straightforward Transcription](#straightforward-transcription)
    - [Punctuation in Transcriptions](#punctuation-in-transcriptions)
      - [Apostrophe](#apostrophe)
      - [Dash](#dash)
      - [Full Stop](#full-stop)
      - [Other Punctuation](#other-punctuation)
  - [Use of LaTeX](#use-of-latex)
    - [Numeric Values](#numeric-values)
      - [Notation of Base-12](#notation-of-base-12)
      - [Notation of Base-16](#notation-of-base-16)

## Pre-2022 Format

### Lexicon Master Lists

#### Masterlist Mother Entries

Lexicon mother entries are direct entries within the lexicon which do not have a parent other than their initial letter. Prior to October 2022, these are formatted roughly as follows:

```plaintext
+ **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_
```

This format renders roughly as:

- **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_

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

- **[alma](a/alma.md).ru** _ton verb_ ruling, leading, governing `#2008.06.22` formerly _aluma.ru_
  - **[almán](a/almán.md)** _noun_ leader by circumstance, acting leader
  - **[almatax](a/almatax.md)** _noun_ leader by profession, manager
  - **[alnom](a/alnom.md)** _noun_ a rule or law

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

- **[almaru](a/alma.md)**
  1. (_ton verb_) leading, exercising or showing leadership
  2. ruling, interpreting rules or laws, passing judgement
  3. governing, exercising authority
  - **[almán](a/almán.md)**
    1. (_noun_) a leader, as of a group or team
    2. a leader or ruler appointed without regard for qualifications, usually for a short term until a properly qualified leader can be appointed
    3. a leader without the will to lead or govern
  - **[almatax](a/almatax.md)**
    1. (_noun_) ruler, governor
    2. manager, coach
    3. teacher, professor, preacher
    4. judge, court
  - **[alnom](a/alnom.md)**
    1. (_noun_) a rule or regulation
    2. a protocol or procedure
    3. a law

In this format, each word is listed as a single line, with each set of glosses or definitions receiving its own ordered list, with daughter entries receiving unordered list entries after the ordered list for the mother word. Parts of speech are listed along with the first gloss or definition, and are assumed to remain consistent until a new part of speech is listed.

## Post-2022 Format

From the start of this update, it is intended that all lexicon pages within the primary lexicon use a more consistent formatting that is easy to read and follow. The lexicon lists are still intended to be a lexicon and glossary, not a full dictionary, but some cues are being taken from dictionary formats.

### Lexicon Lists

Going forward, all lexicon lists should stop using mother-daughter hierarchies for words, and should instead reference related words in a parenthetical. The proposed format is as follows:

```plaintext
- **[alma.ru](a/alma.md)** 1. (_ton verb_) ruling, leading, governing (attested 2008-Jun-22; formerly _aluma.ru_)
- **[almán](a/almán.md)** 1. (_noun_) leader by circumstance, acting leader (cf. _almaru_)
- **[almatax](a/almatax.md)** 1. (_noun_) leader by profession, manager (cf. _almaru_)
- **[alnom](a/alnom.md)** 1. (_noun_) a rule or law (cf. _almaru_)
```

Which ought to render, roughly, as such:

- **[alma.ru](a/alma.md)** 1. (_ton verb_) ruling, leading, governing (att. 2008-Jun-22; formerly _aluma.ru_)
- **[almán](a/almán.md)** 1. (_noun_) leader by circumstance, acting leader (cf. _almaru_)
- **[almatax](a/almatax.md)** 1. (_noun_) leader by profession, manager (cf. _almaru_)
- **[alnom](a/alnom.md)** 1. (_noun_) a rule or law (cf. _almaru_)

1. All entries are part of an _unordered list_ denoted with a \- symbol. Ordering of this list is manual, following the alphabetic conventions of the language in which entries are listed.
   1. In the updated lexicon, a **straightforward transcription** is preferred to the use of IPA or special characters for digraphs.
2. When linked to a lexicon entry page, the full dictionary form of the entry is included in the link, though the lexicon entry page should still be named based on the (infinitive) verb stem.
3. Each sense of the lexicon entry receives a numbered listing, helping to alleviate confusion over comma-separated and semicolon separated entries.
   1. The part of speech is _emphasis formatted_ and contained in a pair of parentheses
      1. A comma may be used to concatenate multiple parts of speech within parentheses
      2. A set of escaped \\\[square brackets\\\] may follow these parentheses to specify a field of knowledge or context for a given sense.
   2. The list of glosses suitable to the sense is separated as makes logical sense
   3. Any parenthetical information, such as earliest attestation or older forms of a word, is contained in a single pair of parentheses and located at the end of the sense to which it applies
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
- **[almaru](a/alma.md)**
  1. (_ton verb_) leading, exercising or showing leadership
  2. (_ton verb_) ruling, interpreting rules or laws, passing judgement
  3. (_ton verb_) governing, exercising authority
- **[almán](a/almán.md)** (cf. _almaru_)
  1. (_noun_) a leader, as of a group or team
  2. (_noun_) a leader or ruler appointed without regard for qualifications, usually for a short term until a properly qualified leader can be appointed
  3. (_noun_) a leader without the will to lead or govern
- **[almatax](a/almatax.md)** (cf. _almaru_)
  1. (_noun_) ruler, governor
  2. (_noun_) manager, coach
  3. (_noun_) teacher, professor, preacher
  4. (_noun_) judge, court
- **[alnom](a/alnom.md)** (cf. _almaru_)
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

- **(Applicable Sense/s)**
  - **_alternate form_** (_part of speech_) usage or definition

## Derivation

- **(Applicable Sense/s)**
  - Derivational information

### Etymology (optional)

- **(Applicable Sense/s)**
  - etymological information

## Related Words

- **related word** (_part of speech_) definition or gloss
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

## Straightforward Transcription

The transcription standard preferred for lexicon and dictionary usage as of this update is the **Formal** column of this transcription table for all single letters:

| Letter Name  | Simple | **Formal** | IPA    |
|:-------------|:------:|:----------:|:------:|
| adob (asent) | a (á)  | **a (á)**  | ä (æ)  |
| baten        | b      | **b**      | b      |
| gaym         | gh     | **g**      | g      |
| droma        | d      | **d**      | d      |
| enx (asent)  | e (é)  | **e (é)**  | ɛ (e)  |
| zapen        | z      | **z**      | z      |
| hort         | h      | **h**      | h      |
| cumit        | c      | **c**      | ts     |
| iom (asent)  | i (í)  | **i (í)**  | ɪ (i)  |
| kasi         | k      | **k**      | k      |
| qorn         | qu     | **q**      | kᵂ     |
| lama         | l      | **l**      | l      |
| mu           | m      | **m**      | m      |
| nyu          | n      | **n**      | n      |
| jema         | zh     | **j**      | ʒ      |
| pente        | p      | **p**      | p      |
| rom          | r      | **r**      | r      |
| swen         | s      | **s**      | s      |
| tar          | t      | **t**      | t      |
| unta (asent) | u (ú)  | **u (ú)**  | ʌ (u)  |
| yast         | y      | **y**      | j      |
| fil          | f      | **f**      | f      |
| vé           | v      | **v**      | v      |
| xoi          | kh     | **x**      | x      |
| omoj (asent) | o (ó)  | **o (ó)**  | ɔ (o)  |
| wes          | w      | **w**      | w      |

All digraphs in the new format should be represented using their literal transcriptions, letter by letter, based on this standard, without the use of IPA or other special characters.

### Punctuation in Transcriptions

The following punctuation marks are used in the **label** of lexicon and dictionary entries:

#### Apostrophe

An apostrophe may be included only if it indicates:

1. A syllable break is forced, whether as a glottal stop or simple distinction between two letters, and is particularly important to indicate when two letters do _not_ form a digraph. Of particular note, the _Simple Romanization_ method requires an apostrophe any time Adinjo Journalist uses the combination of _kasi + hort_, as _kh_ is the Simple form for Romanizing _xoi_.
2. An entry represents a contraction, a word formed by combining two words and dropping one or more sounds from the result.

#### Dash

The dash is used on various _affixes_ to indicate the direction in which the root word attaches. Any affix without a dash may be attached on either side of a root word, while a prefix always goes before the root, and a suffix always goes after the root.

#### Full Stop

The full stop, or period, symbol is used to indicate the gerund suffix of **ton verbs**.

#### Other Punctuation

Other punctuation is reserved for use in labels only for expressions, such as **qe'c dama?** which is a question and expression.

## Use of LaTeX

It is recommended that ${\LaTeX}$ be used when inserting numeric information into the lexicons and dictionaries. This allows for superscript, subscript, and mathematical formatting.

### Numeric Values

${\LaTeX}$ is not required for integer values from $-9$ to $9$, but should be used on all values greater than $9$ or lower than $-9$, unless these numbers are in a base lower than decimal, or base-ten. All numbers outside of this range, or requiring more then one digit, should include a subscript indicating the base, as, for example ${16_{10}}$ or ${29_{12}}$

#### Notation of Base-12

In general, we use the Greek letter _chi_ (Χχ) or the Latin letter _ex_ (Xx) for the value of ${9+1}$ and the Greek letter _epsilon_ (Εε) or the Latin letter _ee_ (Ee) for the value of ${9+2}$ when using base-12 notation in Adinjo documentation. It is preferred to use

- The lowercase Greek letters if a number is _not_ being used in ${\LaTeX}$ markup.
- Either the Greek or Latin capital form is preferred within ${\LaTeX}$ markup.
- The Latin lowercase should generally be avoided except in the process of composing a draft.

These characters should be presented using the markup \text{foo} provided by ${\LaTeX}$, as they are not meant to be mathematical variables, but numerals.

#### Notation of Base-16

We notate base-16 values using the convention common among programmers, using the letters ${\text{ABCDEF}}$ for the values of ${9+1}$ through ${9+6}$.

If you feel a need for further clarity than using subscript base notation, you may refer to base-16 values with the prefix ${0\text{x}}$.

As with the characters used as numerals for base-12 notation, the letters in such numeric values should be enclosed in the markup \text{foo} provided by ${\LaTeX}$
