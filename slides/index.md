---
title: "Open Cantine"
author: ""
highlighter: highlight.js
output: html
job: ""
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: "Visualiser des données parcellaires"
framework: io2012
widgets: []
---

<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

## Les données de la cantine

Variables
- Date
- Heure
- Numéro du ticket
  - Incrémenté à chaque passage
- Numéro de caisse
  - 1: Cantine
  - 2: Cantine
  - 3: Cafétéria
  - 4: Cantine

--- .class #id 


## Évolution des numéros de ticket par caisse

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

--- .class #id 

## Passage par minute ces derniers jours

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id 

## Fréquences par jour de la semaine

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

--- .class #id 

## Débit moyen par caisse sur un service

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 
