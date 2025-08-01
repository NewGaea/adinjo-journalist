# Search Lexicon in Adinjo Journalist
Click the \</> icon at the top right of this Dataview query and change the quoted portion of the line: `WHERE contains(englishGloss,"a")` to the English string you want to search for.

By default, this will search within all list entries of the `englishGloss` field for every page. To alter the scope, change `contains` to `icontains` for case-insensitive matching, or to `econtains` for an exact match.

```dataview
TABLE englishGloss as "English", coinDate as "Coined/Attested"
FROM "lexicon" AND #dictionary
FLATTEN englishGloss
WHERE icontains(file.name, "al")
SORT (file.name)ASC
```
