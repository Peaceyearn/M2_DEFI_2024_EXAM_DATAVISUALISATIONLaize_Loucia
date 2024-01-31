# La réforme des retraites est-elle équitable ?

![image_illustration_examen_depart_retraite](https://github.com/Peaceyearn/DEFI_M2_EXAM_Laiz-_Loucia_DATAVISUALISATION/assets/121464401/ea769c87-5805-4eba-98f0-97c1f309d6de)

La réforme des retraites révisant le système de retraite français réalisées pendant la mandature d'Emmanuel Macron, validée par le Conseil constitutionnel, le 14 avril 2023 et promulguée le jour même, a suscité de vives débats et des grèves violentes à travers tout le pays. Pourtant, la réforme a été présenté comme inéluctable par ses partisans. En effet, « Nous vivons plus longtemps et donc (…) nous devons travailler plus longtemps », a déclaré le ministre du travail, Olivier Dussopt. Pourtant, beaucoup de France ont jugé cette réforme inique et convoyeuse d’inégalité. Nous chercherons à travers quelques visualisations à explorer de façon impartiale les angles des inégalités potentielles véhiculée par la réforme.


# Sommaire 
1. Présentation du jeux de données
2. L’espérance de vie de 30 à 80 ans selon le niveau d’éducation 
3. L’âge de départs en retraite des catégories socioprofessionnelles
4. 

# Présentation des jeux de données

-Le jeux de données n°1 :

Ce jeu de données porte sur l’espérance de vie de 30 à 90 ans selon le niveau d’éducation ou diplôme.J'ai effectué une modification en réconciliant les colonnes hommes et femmes. J'ai procédé au data cleaning en enlevant par années et les éléments de textes. Enfin, j'ai enlevé données avec un âge excédant les 80 ans puisqu'au delà, les écarts ne sont plus significatifs et tendent à se réduire.

> Sources : [Insee, Échantillon Démographique Permanent et état civil, 2009-2013.](https://www.insee.fr/fr/accueil) 

Le jeux de données n°2 :
Ce jeu de données porte sur l’âge conjoncturel de départs en retraite des catégories socioprofessionnelles par année, sexe et régime
J'ai enleve les données au dessus de 2009 à 2013

Puis j'ai enlevé les catégories CC et sexe qui ne m'intéressaient pas ainsi que des catégories

Dans chaque categorie on enleve les données avant 2012 et on garde jusqu’à 2021. Puis j’ai enleve la CNAV puisque tout le monde cautise à la CNAV donc ce n‘est pas vrm représentatif.


| Caisse       | Ensemble     |
|--------------|--------------|
| Banque de France | 59,3     |
| CNIEG        | 57,02        |
| CNRACL       | 61,3         |
| CRPCEN       | 62,5         |
| ERAPF        | 65,325       |

Sources : Insee, Échantillon Démographique Permanent et état civil, 2009-2013.


## Première visualisation

<div class="flourish-embed flourish-chart" data-src="visualisation/16619337"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


Analyse

## Visualisation de l’espérance de vie de 30 à 80 ans selon le niveau d’éducation 




<iframe title="Age conjoncturel de départ à la retraite" aria-label="Stacked Bars" id="datawrapper-chart-F5xE6" src="https://datawrapper.dwcdn.net/F5xE6/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="510" data-external="1"></iframe>
https://datawrapper.dwcdn.net/F5xE6/1/


Analyse


## Troisième visualisation

<div class="flourish-embed flourish-chart" data-src="visualisation/16636184"><script src="https://public.flourish.studio/resources/embed.js"></script></div>



- Premieier
- Deuxième élément
  - Élément imbriqué 1
  - Élément imbriqué 2
- Troisième élément




## Maladies chroniques selon les groupes socioprofessionnel
<iframe title="Inégalité d’espérance de vie due au maladie chronique selon les catégories socioprofessionnelles" aria-label="Grouped Bars" id="datawrapper-chart-5sreo" src="https://datawrapper.dwcdn.net/5sreo/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="4650" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>



Analyse


# Conclusion



