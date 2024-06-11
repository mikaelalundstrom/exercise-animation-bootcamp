![Poster](poster.png)
# CSS Animation Bootcamp

## 1. Transitions

### Hover Button
Gör en knapp som på ```:hover``` gör en mjuk övergång på följande egenskaper: 

* width x height ( alt. padding )
* background-color
* box-shadow


### Slide in menu

Gör en meny som slide:ar in från valfri sida.

För att trigga animeringen togglar du CSS-classen ```.open``` på en ```<nav>``` genom att lägga in detta script längst ner i bodyn.

```html
<script>
    document.querySelector('nav')
    .addEventListener('click', (e) => {
        e.target.classList.toggle('open')
    })
</script>
```

#### Levelup
Varje menyalternativ ska slidea in med en delay för maximal coolhetsfaktor.

![screen](/examples/02_slidein_menu/screen.png)


### Pride cards

Gör en kortlek med 9 kort som vid hover av body sprider ut sig i en solfjäder.

![screen](/examples/03_cardspread/screen.png)



## 2. Keyframes

### Four corners

* Gör en fyrkant på 500 x 500px centrerad på skärmen. 
* Inuti denna ska du nu animera en kub som går från hörn till hörn. 
* För varje hörn ska den stanna upp och byta färg innan den fortsätter.

![screen](/examples/04_fourcorners/screen.png)


### Spinner

Gör en loader eller spinner som kan visas medan en sida eller del av sida laddas.

![screen](/examples/05_spinner/screen.png)


### Stopwatch

Gör ett tidtagarur med en snurrande sekund- samt en minutvisare. 

![screen](/examples/06_stopwatch/screen.png)

## 3. 3D animations

### Starwars crawler
Gör en *text crawler* som likt [introt till Starwars](https://www.youtube.com/watch?v=h5psCjg5-cI) scrollar [text](https://starwars.fandom.com/wiki/Opening_crawl) bort mot horisonten.

Extra stjärnor i rymdkanten om det liknar introsekvensen med rymdbakgrund, rätt fonter, [logotyp](https://upload.wikimedia.org/wikipedia/commons/9/9b/Star_Wars_Yellow_Logo.svg), färger etc.

![screen](/examples/07_sw_crawler/screen.png)

### Flip a card

Skapa ett kort som lyfts upp, snurrar runt 360 grader och sen läggs ner igen.

**Levelup:** Gör kortet tvåsidigt med olika fäger / sida.

![screen](/examples/08_flipcard/screen.png)

# Level up!!!

### The Cube

Gör en kub med 6 sidor. Varje sida ska ha en text samt semitransparent bakgrund. Avslutade kuben med att lägga på en animering som får den att snurra runt lite coolt.

![screen](/examples/09_cube/screen.png)

### Organic

Gör 20(ish) ringar som animeras likt en våg i 3d. Gör den intressant genom att snurra runt hela vågen i 3d-rummet.

![screen](/examples/10_organic/screen.png)
