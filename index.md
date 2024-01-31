# La réforme des retraites est-elle équitable ?

![image_illustration_examen_depart_retraite](https://github.com/Peaceyearn/DEFI_M2_EXAM_Laiz-_Loucia_DATAVISUALISATION/assets/121464401/ea769c87-5805-4eba-98f0-97c1f309d6de)

La réforme des retraites révisant le système de retraite français réalisées pendant la mandature d'Emmanuel Macron, validée par le Conseil constitutionnel, le 14 avril 2023 et promulguée le jour même, a suscité de vives débats et des grèves violentes à travers tout le pays. Pourtant, la réforme a été présenté comme inéluctable par ses partisans. En effet, « Nous vivons plus longtemps et donc (…) nous devons travailler plus longtemps », a déclaré le ministre du travail, Olivier Dussopt. Pourtant, beaucoup de France ont jugé cette réforme inique et convoyeuse d’inégalité. Nous chercherons à travers quelques visualisations à explorer de façon impartiale les angles des inégalités potentielles véhiculée par la réforme.


# Sommaire 
1. [Présentation des jeux de données](#presentation-jeux-de-donnees)
2. [L’espérance de vie de 30 à 80 ans selon le niveau d’éducation](#esperance-de-vie) 
3. [L’âge de départs en retraite des catégories socioprofessionnelles](#age-de-departs-retraite)
4. [Les groupes socioprofessionnels les plus touchés par les maladies](#groupes-plus-touches-maladies)
5. [Inégalité d’espérance de vie due au maladie chronique selon les catégories socioprofessionnelles](#inegalite-esperance-vie)

# Présentation des jeux de données (#presentation-jeux-de-donnees)

▶ Le jeux de données n°1 :

Ce jeu de données porte sur l’espérance de vie de 30 à 90 ans selon le niveau d’éducation ou diplôme.J'ai effectué une modification en réconciliant les colonnes hommes et femmes. J'ai procédé au data cleaning en enlevant par années et les éléments de textes. Enfin, j'ai enlevé données avec un âge excédant les 80 ans puisqu'au delà, les écarts ne sont plus significatifs et tendent à se réduire.

> Sources : [Insee, Échantillon Démographique Permanent et état civil, 2009-2013.](https://www.insee.fr/fr/accueil) 

▶ Le jeux de données n°2 :
Ce jeu de données porte sur l’âge conjoncturel de départs en retraite des catégories socioprofessionnelles par année, sexe et régime. J'ai enleve les données au dessus de 2009 et excédant 2013 car le jeux de données précédent à la même date et est lié.Puis j'ai enlevé les catégories CC et sexe qui ne m'intéressaient pas ainsi que des catégories comme la CNAV puisque tout le monde cautise à la CNAV donc ce n‘est pas vraiment représentatif et aussi car certaines données étaient incomplètes au niveau des dates. Enfin j'ai fait la moyenne par catégories de 2009 à 2013 pour chaque catégorie (CNIEG) sur Excel avec les fonctions calcul de moyennnes.


| Caisse       | Ensemble     |
|--------------|--------------|
| Banque de France | 59,3     |
| CNIEG        | 57,02        |
| CNRACL       | 61,3         |
| CRPCEN       | 62,5         |
| ERAPF        | 65,325       |

> Source : [Insee, Échantillon Démographique Permanent et état civil, 2009-2013.](https://www.insee.fr/fr/accueil) 


▶ Le jeux de données n°3 :
Ce jeu de données porte sur les groupes de catégories socio-professionnels  ("Agriculteurs exploitants","Artisans", "commerçants", "chefs d'entreprise", qui sont le plus touchés par les maladies comme le "Cancers", "Diabète"... avec comme référent de 1, la catégorie cadre avec une probabilité de 1, les cadres et professions intellectuelles supérieures.
J'ai enleve les éléments de textes superflus por le traitement et j'ai les nombres en desssous de chaque case dans les colonnes principales de catégories car elles faisaient trop de valeurs à traiter pour l’outil et je les ai remis au propre.

> Source :  [data.drees.solodarities-sante.gouv.fr](https://data.drees.solodarities-sante.gouv.fr/explore/dataset/er_inegalites_maladies_chroniques/information/) 

▶ Le jeux de données n°4 :

Ce jeu de données porte sur les inégalité d’espérance de vie due au maladie chronique selon les catégories socioprofessionnelles. Il comporte des colonnes "Categorie",	"Dixieme de niveau de vie",	"Sante"Esperance de vie" avec des données sur la "Population sans la maladie" et des données sur les types de maladies "Diabète", "Maladies du foie ou du pancréas". J'ai enlevé le reste des données "toutes catégories confondues" après la ligne "Maladies du foie ou du pancréas" car les données semblaient erronnées et se répétaient. Enfin le but était de montrer les écarts entre chaque groupe de 1 à 6 pour chaque catégorie de maladie et pour ce faire,les données précédentes qui semblaient juste suffisaient. Hormis ces erreurs remarquées le dossier n'a pas nécessité de datacleaning hormis le fait d'enlever les données textuelles.
> Source :  [data.drees.solodarities-sante.gouv.fr](https://data.drees.solodarities-sante.gouv.fr/explore/dataset/er_inegalites_maladies_chroniques/information/) 


## L’espérance de vie de 30 à 80 ans selon le niveau d’éducation (#esperance-de-vie)
Notre premier jeu de données traite de l’espérance de vie selon les diplômes couvrant la période de 2009 à 2013, et les années de 30 à 80 ans.Cette visualisation vise à illustrer la différence d’espérance de vie selon les diplômes (sans diplôme, Brevet, CAP-BEP, Baccalauréat, Supérieur). Il s’agit pour nous de montrer avec cette visualisation qu’il existe à déjà une inégalité basée sur l’éducation qui influe sur l’espérance de vie des personnes et que la réforme des retraites pourrait potentiellement renforcer cette inégalité en rallongeant la durée de travail de personne défavorisé alors que leur espérance de vie est moindre en comparaison avec les personnes des classes supérieure.

<div class="flourish-embed flourish-chart" data-src="visualisation/16619337"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Ab initio, nous observons un écart encore plus grand entre les hommes et les femmes, lorsque celles-ci sont plus diplômées sachant qu’en moyenne les femmes ont à l’origine une espérance de vie plus haute que les hommes (pour diverses raisons hormonales, sociétales…).En outre, le même phénomène entre les femmes est observable. Par exemple, une femme sans diplôme à 30 ans aura une espérance de vie de 52.9 quand une femme dans le supérieur aura une espérance de vie de 57.1. L’écart est de 4,2 ans. Cet écart d’espérance de vie selon les diplômes se retrouve dans toutes les catégories et se poursuit dans les tranches d’âges de 30 à 53 ans (puis tend à se réduire).Cet écart d’espérance de vie due au niveau d’éducation est encore plus marqué chez les hommes. Un homme sans diplôme a une espérance de vie de 45,4 ans à 30 ans, une espérance de vie de 40 ans à 36 ans et une espérance de vie de 34, 6 à 42 ans.A contrario, un homme avec un Brevet a une espérance de vie de 48,4 ans à 30 ans, une espérance de vie de 42,8 ans à 36 ans et une espérance de 37, 2 à 42 ans. Enfin, un homme dans le supérieur à une espérance de vie de 49,4 ans à 30 ans, une espérance de vie de 43,7 ans à 36 ans et une espérance de 38, 1 à 42 ans. On constate donc un bond de 3 points à l’âge de 30 entre un homme ayant un simplet brevet et un homme diplômé ce qui est plus que pour les femmes.


Enfin, nous constatons une tendance selon les genres : 
A partir de 70 ans pour les femmes, l’écart d’espérance de vie diminue sensiblement, il n’est plus « que » de 2 ans au lieu de 4 ans à l’âge de 30, et à partir de 80, il n’est plus que de 1 an.
Pour les hommes, l’écart d’espérance de vie est encore plus important à 30 ans, il est de 8 ans. 
A partir de 70 ans pour les hommes, l’écart d’espérance de vie diminue sensiblement, il n’est plus « que » de 3 ans au lieu de 8 ans à l’âge de 30, et à partir de 80, il n’est plus que de 1 an comme les femmes.
Nous concluons d’après ces données que l’espérance de vie est indéniablement liée au niveau d’éducation car des études ont montrées que plus le niveau d’éducation est élevée plus grande est la sensibilisation à la qualité de vie. Et donc l’impact sur l’espérance de vie est plus conséquent.Suivant cette visualisation, il paraît alors juste de se demander, dans le cas où l’espérance de vie est asymmétrique selon le niveau d’éducation, est-elle prise en compte dans le temps de travail et le droit de prendre sa retraite prématurément et d’échapper au prolongement de la durée de travail prévue par la loi récemment passée ?


## L’âge de départs en retraite des catégories socioprofessionnelles(#age-de-departs-retraite)

Ces données représentent l'âge de départ à la retraite pour différents régimes de retraite ou caisses en France de 2009 à 2013… Ces données de caisses de retraites permettent de faire une visualisation rendant compte de l’âge de départ des catégories socioprofessionnelles. Chaque chart indique le nom de la caisse et l'âge de départ à la retraite présumé ou conjecturel associé. L'âge de départ à la retraite peut varier en fonction de la caisse et des spécificités du régime de retraite associé.

<iframe title="Age conjoncturel de départ à la retraite" aria-label="Stacked Bars" id="datawrapper-chart-F5xE6" src="https://datawrapper.dwcdn.net/F5xE6/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="510" data-external="1"></iframe>

Le régime des caisses de retraites donne les modalités selon lesquelles les prestations de retraite sont gérées et distribuées par une caisse de retraite spécifique. En France, il existe plusieurs caisses de retraite, chacune gérant les pensions de retraite pour des catégories spécifiques de travailleurs ou de secteurs d'activité. 


- CNIEG = caisse nationale des industries gazières et électriques
- CNRACL = retraite des fonctionnaires territoriaux et hospitaliers
- CRPCEN = clercs et employés de notaire
- ERAPF = retraite additionnelle de la fonction publique
- FSPOEIE = retraite des ouvriers d’état
- SSI = sécurité des sociales des indépendants
- CAVIMAC = ministres des cultes et des membres des congrégations et des collectivités religieuses
- CANSSM = Caisse autonome nationale de la sécurité sociale dans les mines
- AGIRC = la quasi-totalité des salariés de l’industrie, du commerce, des services de l’agriculture
- ARCCO = cadres
- RATP / SNCF = deux grandes entreprises de transport en France

Nous observons que les CRPCEN (clercs et employés de notaire) partent à la retraite à 62 ans et que les travailleurs des grandes entreprises de transport en France (RATP, SNCF) partent à la retraite à 55 ans grâce aux régimes de retraite spéciaux avec des caisses dédiées. Le départ à la retraire n’est pas le même selon les catégories socioprofessionnelles 
Or, l’article 1 de la réforme des retraites prévoit la suppression de la majorité des régimes spéciaux de retraite. Cela comprend la RATP, la branche des industries électriques et gazières (IEG), les clercs et employés de notaires, les personnels de la Banque de France, et les membres du Conseil économique social et environnemental (Cese). Réforme des retraites : ce qu’il faut savoir (demarchesadministratives.fr)



> Source : [Outil datawrapper](https://datawrapper.dwcdn.net/) 




## Les groupes socioprofessionnels les plus touchés par les maladies (#groupes-plus-touches-maladies)
Cette visualisation permet de rendre compte de la rareté des maladies chez les cadres et professions intellectuelles supérieures et de leur prévalence chez les autres professions,Agriculteurs exploitants, Artisans, commercants.

<div class="flourish-embed flourish-chart" data-src="visualisation/16635501"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Dans le jeu de données, les cadres servent de points de référence, fixé à 1. Les autres professions dépassent ce point de référence et sont plus touchés par le diabète, les maladies chroniques et autres. Les ouvriers ont 1,88 % plus de chances d'avoir du diabète que les cadres et professions supérieurs qui sont la valeur de référence.




## 5. Inégalité d’espérance de vie due au maladie chronique selon les catégories socioprofessionnelles (#inegalite-esperance-vie)



<iframe title="Inégalité d’espérance de vie due au maladie chronique selon les catégories socioprofessionnelles" aria-label="Grouped Bars" id="datawrapper-chart-5sreo" src="https://datawrapper.dwcdn.net/5sreo/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="4650" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>


Catégorie: Le type de maladie.
Dixième de niveau de vie: La subdivision des données en dix groupes en fonction du niveau de vie.
Santé: La condition de santé de la population (dans ce cas, "Population sans la maladie" semble indiquer l'état de santé sans la maladie spécifiée).
Espérance de vie: L'espérance de vie associée à chaque groupe.
Par exemple, dans la catégorie "Cancers", le dixième groupe de niveau de vie a une espérance de vie de 88,87 ans pour une population sans la maladie, tandis que le premier groupe a une espérance de vie de 83,20 ans dans des conditions similaires.



Cette visualisation montre que la réforme dessert les plus défavorisés qui travailleront plus longtemps alors qu'ils auront une espérance de vie plus réduite et sont plus touchés par les maladies chroniques.
Le chiffre de 1 représente le 1er décile et donc correspond au 10 % des ménages les plus modestes qui ont un revenu disponible inférieur aux 13 630 euro par an et les 10 % de ménages les plus aisés ont un revenu supérieur à 63 000 euros dans le 9 ème décile. 







# Conclusion


Les limites: 
Certains jeux de données liées à la santé étaient complexes et difficiles à croiser avec des données socio-économiques, ils auraient fallu par exemple comprendre comment chaque groupe et les détails ou les descriptions spécifiques associées à chaque groupe dans la source d'origine des données. Ces détails auraient pu inclure des informations sur les caractéristiques socio-économiques, les comportements liés à la santé, ou d'autres facteurs qui pourraient influencer la santé dans chaque groupe.


