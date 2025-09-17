# All Words

## Bases

![Adinjo to English](_meta/queries/Adinjo%20Journalist%20Lexicon.base#Adinjo%20to%20English)


## Dataview

### Adinjo Journalist to English

```dataview
TABLE WITHOUT ID file.link as "Adinjo Journalist", englishGloss as "English"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
SORT (file.name)ASC
```

### English to Adinjo Journalist

```dataview
TABLE WITHOUT ID englishGloss as "English", file.link as "Adinjo Journalist"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
SORT (file.name)ASC
SORT (englishGloss)ASC
```
