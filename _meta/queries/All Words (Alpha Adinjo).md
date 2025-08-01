# All Words

```dataview
TABLE englishGloss as "English"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
SORT (file.name)ASC
```
