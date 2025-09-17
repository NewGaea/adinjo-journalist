# All Words

```dataview
TABLE WITHOUT ID englishGloss as "English", (file.link) as "Adinjo Journalist"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
SORT (englishGloss)ASC
```
