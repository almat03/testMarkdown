# tutorial markdown

## heading

Per fare gli heading si usa `#` testo , più cancelletti riducono la granedzza del heading.

### header livello 3

---

## List

Le liste si ottengono scrivendo `1.` elemento , per le liste non ordinate si usa `-`elemento.

1. primo elemento
1. secondo elemento
1. terzo elemento
1. quarto elemento

- elemento non ordinato
- elemento non ordinato

* elemento non ordinato usando \*
* elemento non ordinato usando \*

- elemento non ordinato usando +

---

## elementi inline

Il corsivo si ottiene racchiudendo la frase tra `_`, invece il grassetto tra due `__`.

_Esempio di testo in corsivo_

**Esempio di testo in grassetto di dio can**

---

## Blockquotes

Le citazione si ottengono con `>` all'inizio della frase.

> citazione casuale di un libro/canzone mainstream.

---

## Immagini

Le immagini si ottengono con due sintassi :

![alt immagine](https://images.unsplash.com/photo-1469854523086-cc02fe5d8800?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1008&q=80 ' title immagine')

oppure con:

[ballerina]: https://images.unsplash.com/photo-1527186504227-0a47da29a0d0?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=433&q=80 'Ballerina random'

![alt seconda immagine][ballerina]

##Link

I link vengono riconosciuti automaticamente da markdown, ma se voglioamo dare un title al link possiamo fare come per le immagini:

[wikipedia](https://it.wikipedia.org 'link a wikipedia')

---

## Table

Le tabelle si ottengono così:

| marca   | modello | costo  |
| ------- | ------- | ------ |
| fiat    | panda   | 9800   |
| ferrari | enzo    | 180000 |
| ford    | puma    | 16000  |

## Code snippets

Per del codice inline si può utilizzare un backtick per racchiudere la parola o codice.

Il file di configurazione `config.ini` si trova in `bin\src\config`.

Per del codice in blocco si possono usare 3 backtick, e si può anche spercificare il linguaggio:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
  </body>
</html>
```

```css
.container > div:nth-child(1n) {
background-color: #96ceb4;
}

.container > div:nth-child(3n) {
background-color: #88d8b0;
}

.container > div:nth-child(2n) {
    background-color: #ff6f69;
}

.container > div:nth-child(4n) {
    background-color: #ffcc5c;
}


.container {
  display: grid;
  grid-gap: 5px;
  grid-template-columns: repeat(auto-fill,minmax(100px,1fr));
  grid-auto-rows: 100px;
```

```javascript
function sum(x, y) {
  return x + y;
}
console.log(sum(2, 3));
```

---

## image 2

![monkey](https://cdn.pixabay.com/photo/2021/07/25/12/04/monkey-6491669_960_720.jpg "monkey 1")

[monkey2]: https://cdn.pixabay.com/photo/2021/07/25/12/04/monkey-6491669_960_720.jpg "monkey 2"


![monkey number 2][monkey2]