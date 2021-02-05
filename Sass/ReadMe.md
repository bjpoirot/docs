[home](../ReadMe.md)

# Info #
Sass wordt vooral gebruikt om terugkerende waarden in CSS bestanden zoals een kleur of lettertype in een variabele
te zetten zodat je allleen de variabele hoeft te wijzigen.
[Documentatie](https://sass-lang.com/documentation)
[Trainingsvideo](https://app.pluralsight.com/library/courses/better-css/table-of-contents)

Sass kan direct in [combinatie met Angular](https://angular.io/guide/workspace-config#style-script-config) worden
gebruikt.

# Install #

[Installeren met behulp van node](https://sass-lang.com/install)

```dotnetcli
npm install -g sass
```
# Use #

[Stylesheets genereren](https://sass-lang.com/guide)

In HTML wordt verwezen naar CSS, je kan niet direct een SCSS file in HTML gebruiken.
Als je gebruik maakt van Angular dan kan Angular de CSS file vanuit SCSS genereren.

```dotnetcli
sass .\styles.scss .\styles.css
```

```dotnetcli
sass --watch .\styles.scss .\styles.css
```

Configuratie in angular.json
```json
           ],
            "styles": [
              "src/styles.scss"
            ],
```

Indien de PrimeNG templates worden gebruikt dan aanpassingen doen aan de bestanden in de folder:
`..\src\assets\sass\overrides`