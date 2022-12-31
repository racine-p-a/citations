# citations

[Présentation en français ici](https://racine.pro/articles/citotron).

This project is a multilingual citations stash.

## Presentation

The code is in fact a simple *json* file containing many authors and quotes **separately**. Why ? Because it is
multilingual (but mostly in french and english language), you have authors name in as much language as you wish : just
add it to the code !

Here is Aristotle :

```json
"Ἀριστοτέλης":{
      "name":{
        "en": "Aristotle",
        "fr": "Aristote"
      },
```

And the same applies to the quotes :

```json
{
  "author": "Antoine de Saint-Exupéry",
  "quote": {
    "fr": "Il est vain, si l'on plante un chêne, d'espérer s'abriter bientôt sous son feuillage."
  },
  "keywords": [
    "Poetry",
    "Wisdom"
  ],
  "context": {
    "en": "Wind, Sand and Stars, 1939",
    "fr": "Terre des hommes, 1939"
  }
}
```

As you can see, you can even use and add keywords and context (the origin of the quote). By doing so, you can easily
sort them by authors, languages and keywords.

## License

**BE CAREFUL!** 

The code is Apache2.
Pictures are mostly public domain. Those that are not have (mostly) their license in their filename. In doubt, do not
use them !
