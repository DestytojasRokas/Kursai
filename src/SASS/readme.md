Isirasyti Sass extension
Isisrasyti Live Sass Compiler
Isirasyti Beautify css/sass/scss/less
Isirasyti Rainbow brackets

<!-- Ar veikia SASS? -->

Susikurti nauja folderi "SASS"

jame "index.html" ir "style.scss"

i index isitrauti "style.css"

apacioje paspausti mygtuka watch SASS

pabandyti isideti div {
    width: 100px;
    height: 100px;
    background: blue;
}

__________________________________


<!-- Kintamieji -->

pakeisti background su SASS kintamuoju
(pavadinimai prasideda su $)

<!-- Nesting -->

Susikurti isvis 3 div elementus taip:

   <div>
        <div>
            <div></div>
        </div>
    </div>

"style.scss" failiuki nusirodyti jiem skirtingas spalvas (red, blue, green) ir dydzius (100px, 75px, 50px) naudajant "Nesting" funkcionaluma

_________________________________


<!-- Mixins -->

Susikurti mixin cube() kuris ima parametra $dimensions

default $dimensions reiksme: 100px;

Tada panaudoti @include savo divuose ir atkartoti praeitos uzduoties rezultata;

_________________________________________________________________

Prideti i "index.html":
<div class="flex">
        Flex example
</div>

pasirasyti "flex-layout" mixin, kuriame galesite keisti "justify-content" ir "align-items" reiksmes;

includinti mixina i .flex klase;