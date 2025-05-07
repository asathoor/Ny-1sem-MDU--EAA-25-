# Ny 1sem MDU (EAA 25)

Udkast og didaktiske prototyper til ny 1. semester Efterår 2025.

## 1) Designsystem

* Alle væsentlige styles implementeres som classes.
* Alle væsentlige komponenter defineres som classes.
* Designsystemet implementeres ved at tilføje relevante classes til HTML.

Eksempel:

~~~~~
<aside class="colbr_350 bg_kontrast1 farveEx kant">
    Lorem ipsum sit dolor ...
</aside>
~~~~~

## 2) Landingpage implementeres

Når designsystemet er klar kan det anvendes i landingpagen, fordi stylesheetet fra designsystemet kan genbruges ved at tilføje denne kodelinje til head:

~~~~~
<link rel="stylesheet" href="css/style.css">
~~~~~

Herefter opbygges designet ved hjælp af de forud definerede klasser i designsystemet. Fx kan kolonner se sådan ud:

~~~~~
<section id="flexKolonner2" class="flex flex-space-around">
    <article>
        ... indhold her ...
    </article>
    <article>
        ... indhold her ...
    </article>
</section>
~~~~~


## Liniefag: Akvarium

## CSS Framework

Måske [Tailwind](https://tailwindcss.com/) er et godt framework for 1. sem.

Logikken ligner det skitserede designsystem, så det er en logisk fortsættelse af undervisningen.
