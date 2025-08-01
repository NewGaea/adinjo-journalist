# All Words
```dataview
TABLE englishGloss as "English", (file.name) as "Adinjo Journalist"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
SORT (englishGloss)ASC
```
