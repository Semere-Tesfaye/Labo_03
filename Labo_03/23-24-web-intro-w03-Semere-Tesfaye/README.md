# 💻 03. Bootstrap inleiding & semantische tabellen

## 🥅 overzicht en leerdoelen

Tijdens de lessen van deze week leer je:

- HTML-code schrijven
- meta-informatie voor Bootstrap toevoegen
- Bootstrap gebruiken
- semantische tabellen samenstellen

## 🔍 week 03: Bootstrap inleiding & semantische tabellen

In deze repository vind je 6 oefeningen terug, elk in hun eigen map. De oefening staat telkens beschreven in het bestand `README.md` _in die map_.

Om Bootstrap te gebruiken (vanaf oefening 2) heb je volgende meta-informatie nodig. (plaats deze elementen in je `head`-element):

```html
<!DOCTYPE html>
<html lang="nl-BE">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
    
</head><!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <!-- JavaScript: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous" defer></script>
```

Wanneer je alle oefeningen hebt afgewerkt, kan je op je `Github Repo` gaan naar de knop `Code` > `Download ZIP`. Upload deze zip in de uploadzone op Digitap. Nadien corrigeer je zelf jouw labo op basis van de correctiesleutel op Digitap, om zo te leren uit jouw fouten.

## 💡 belangrijke termen

| term                 | definitie                                                                                                                                  |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| HTML                 | Een taal die gebruikt wordt om de structuur van een website te bepalen.                                                                    |
| CSS                  | Een taal die gebruikt wordt om de opmaak van een website te bepalen.                                                                       |
| commentaar           | Een stuk tekst in de code dat genegeerd wordt door de computer. Dit kan gebruikt worden om extra uitleg bij code te geven.                 |
| browser              | Het programma waarmee je een website kunt bezoeken.                                                                                        |
| \*.html              | Met deze bestands-extensie worden pagina's van een website opgeslagen als document.                                                        |
| index.html           | De standaard startpagina van een website. Als je geen pagina meegeeft aan het adres van de website, wordt deze pagina automatisch geladen. |
| tag                  | Een kleiner dan (`<`) en groter dan (`>`) teken waartussen een codewoord staat.                                                            |
| tagnaam              | Een codewoord dat inhoud aanduidt voor een bepaald doel.                                                                                   |
| openingstag          | Een kleiner dan (`<`) en groter dan (`>`) teken waartussen een codewoord staat, dat aanduidt waar de inhoud begint.                        |
| sluitingstag         | Een kleiner dan (`<`) en groter dan (`>`) teken waartussen een forward slash en codewoord staat, dat aanduidt waar de inhoud eindigt.      |
| `<h1>-<h6>`          | Een element dat een koptekst aanduidt.                                                                                                     |
| `<p>`                | Een element dat een alinea aanduidt.                                                                                                       |
| `<img>`              | Een element dat een afbeelding aanduidt. De attributes src en alt zijn verplicht voor dit element.                                         |
| `<hr>`               | Een element dat een horizontale lijn aanduidt.                                                                                             |
| `<br>`               | Een element dat inhoud op de volgende tekst-lijn plaatst.                                                                                  |
| `<a>`                | Een element dat een hyperlink aanduidt. Het attribute href is verplicht voor dit element.                                                  |
| element              | Een blok code, bestaande uit een openingstag, inhoud en sluitingstag.                                                                      |
| zelfsluitend element | Een element dat de inhoud dat het aanduidt zelf toevoegt. Dit element heeft daarom enkel een openingstag.                                  |
| nesten               | Het insluiten van één element in een ander element.                                                                                        |
| inhoud               | Alles dat tussen de openingstag en sluitingstag van een element staat.                                                                     |
| indentatie           | Het aantal spaties voor elke lijn code, dat aanduidt in welk element die lijn code is genest.                                              |
| `<html>`             | Een element dat de basis van de volledige webpagina bepaalt.                                                                               |
| `<head>`             | Een element dat meta-informatie over de webpagina bevat.                                                                                   |
| `<body>`             | Een element waarin alle zichtbare inhoud van de webpagina wordt geplaatst.                                                                 |
| `<title>`            | Een element dat de titel van de webpagina aanduidt. Dit element hoort thuis in het <head> element.                                         |
| attribute            | Een deel van de openingstag dat meer informatie geeft over het element.                                                                    |
| attribute-key        | De naam van het attribute. Dit staat aan de linkerkant van het = teken.                                                                    |
| attribute-value      | De waarde van het attribute. Dit staat aan de rechterkant van het = teken.                                                                 |
| src-attribute        | Dit attribute geeft een verwijzing naar een extern bestand (zoals een afbeelding of javascript bestand).                                   |
| alt-attribute        | Dit attribute geeft een naam aan een afbeelding. Wanneer de afbeelding zelf niet geladen kan worden, wordt deze naam getoond in de plaats. |
| href-attribute       | Dit attribute geeft een verwijzing naar een andere website of pagina.                                                                      |

## 📚 bronnen

- [AP cursus Webtechnologie (HTML)](https://apwt.gitbook.io/g_webtechnologie/)
- [w3schools](https://www.w3schools.com)
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Bootstrap](https://getbootstrap.com)
- [Bootstrap documentatie](https://getbootstrap.com/docs/5.3/getting-started/introduction/)