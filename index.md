
<!DOCTYPE html>
<html lang="en-US">

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="/M2_DEFI_Datavisualisation_2024/assets/css/style.css?v=ae309da5faa596e50fc06130fcc4b2c4a3bf3fe4">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>Temps de parole des hommes et femmes à la radio et la télé | M2_DEFI_Datavisualisation_2024</title>
<meta name="generator" content="Jekyll v3.9.3" />
<meta property="og:title" content="Temps de parole des hommes et femmes à la radio et la télé" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="Datavisualisation de temps de parole dans les médias" />
<meta property="og:description" content="Datavisualisation de temps de parole dans les médias" />
<link rel="canonical" href="https://odilestar.github.io/M2_DEFI_Datavisualisation_2024/" />
<meta property="og:url" content="https://odilestar.github.io/M2_DEFI_Datavisualisation_2024/" />
<meta property="og:site_name" content="M2_DEFI_Datavisualisation_2024" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="Temps de parole des hommes et femmes à la radio et la télé" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","description":"Datavisualisation de temps de parole dans les médias","headline":"Temps de parole des hommes et femmes à la radio et la télé","name":"M2_DEFI_Datavisualisation_2024","url":"https://odilestar.github.io/M2_DEFI_Datavisualisation_2024/"}</script>
<!-- End Jekyll SEO tag -->

    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/M2_DEFI_Datavisualisation_2024/favicon.ico" -->

<!-- end custom head snippets -->

  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          
            <a id="forkme_banner" href="https://github.com/Odilestar/M2_DEFI_Datavisualisation_2024">View on GitHub</a>
          

          <h1 id="project_title">M2_DEFI_Datavisualisation_2024</h1>
          <h2 id="project_tagline">Datavisualisation de temps de parole dans les médias</h2>

          
        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        
<h1 id="temps-de-parole-des-hommes-et-femmes-à-la-radio-et-la-télé">Temps de parole des hommes et femmes à la radio et la télé</h1>
<p><img src="https://img.etimg.com/thumb/width-1800,height-900,imgsize-458873,resizemode-75,msid-70322833/industry/media/entertainment/media/tv-and-radio-companies-want-broadcast-policy-to-protect-media-freedom.jpg" alt="Image de média" /> 
source:image google</p>
<h1 id="sommaire">Sommaire</h1>
<ol>
  <li><a href="#introduction">Introduction</a></li>
  <li><a href="#jeuDeDonnées">Choix et recueil du jeu de données</a></li>
  <li><a href="#traitement">Visualisation avec Flourish</a></li>
</ol>

<h2 id="1-introduction-">1. Introduction <a name="Introduction"></a></h2>
<p>J’ai choisi de travailler sur la différence de temps accordée aux hommes et aux femmes sur les médias notamment à la radio et à la télé.
Pour faire une visualisation sur le thème de temps de parole des hommes et femmes dans les médias, il a fallu recueillir des open data sur différents sites. Après collecte des données, j’ai décidé de réduire et de synthétiser mes données et de ne travailler que sur la plage qui m’interesse. J’ai donc réduit les données sur une période de 5 ans à savoir entre 2015 et 2019.</p>

<p><strong>Les chaînes de télé analysées sont les suivantes:</strong>  Arte, Animaux, BFM TV, Canal+, Canal+ Sport, Chasse et pêche, Chérie 25, Comédie+, D8/C8, Euronews, Eurosport France, France 2, France 24, France 3, France 5, France O, Histoire, I-Télé/CNews, L’Equipe 21, LCI, LCP/Public Sénat, La chaîne Météo, M6, Monte Carlo TMC, NRJ 12, Paris Première, Planète+, TF1, TV Breizh, TV5 Monde, Toute l’Histoire, Téva, Voyage, W9.</p>

<p><strong>Les chaînes de radio analysées sont les suivantes:</strong> Chérie FM, Europe 1, France Bleu, France Culture, France Info, France Inter, France Musique, Fun Radio, Mouv’, NRJ, Nostalgie, RFM, RMC, RTL, RTL 2, Radio Classique, Radio France Internationale, Rire et Chansons, Skyrock, Sud Radio et Virgin Radio.</p>

<p>Les temps de parole sont estimés en heure.</p>

<h2 id="2-choix-et-recueil-du-jeu-de-données">2. Choix et recueil du jeu de données</h2>
<p><img src="https://previews.123rf.com/images/forestrun/forestrun1902/forestrun190200024/133670236-professional-microphone-in-radio-studio.jpg" alt="Image micro" />
source:image google</p>

<p>Les données sont recueillies en open data sur le site data.gouv</p>
<blockquote>
  <p><a href="https://www.data.gouv.fr/fr/datasets/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio/#/resources">Données sur temps de parole des hommes et des femmes à la radio et à la télé</a></p>
</blockquote>

<p>J’ai choisi le jeu de données de temps de parole des hommes et femmes à la radio et à la télé parmi les données proposées. J’ai décidé de reduire la période à 5ans.</p>

<h3 id="voici-un-extrait-du-fichier-analysé">Voici un extrait du fichier analysé:</h3>

<table>
  <thead>
    <tr>
      <th>ANNEE</th>
      <th>channel_name</th>
      <th>male_duration</th>
      <th>female_duration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2015</td>
      <td>Animaux</td>
      <td>1 645 238</td>
      <td>956 988</td>
    </tr>
    <tr>
      <td>2015</td>
      <td>ARTE</td>
      <td>3 123 603</td>
      <td>1 231 907</td>
    </tr>
    <tr>
      <td>2015</td>
      <td>BFM TV</td>
      <td>3 501 573</td>
      <td>1 773 802</td>
    </tr>
    <tr>
      <td>2015</td>
      <td>Canal+</td>
      <td>3 339 791</td>
      <td>916 718</td>
    </tr>
    <tr>
      <td>2015</td>
      <td>Canal+ Sport</td>
      <td>2 761 056</td>
      <td>142 649</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>Animaux</td>
      <td>1 634 839</td>
      <td>942 338</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>ARTE</td>
      <td>3 164 116</td>
      <td>1 246 289</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>BFM TV</td>
      <td>3 326 119</td>
      <td>1 841 251</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>Canal+</td>
      <td>3 321 179</td>
      <td>942 185</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>Canal+ Sport</td>
      <td>2 845 340</td>
      <td>144 663</td>
    </tr>
    <tr>
      <td>2017</td>
      <td>Animaux</td>
      <td>1 550 192</td>
      <td>937 349</td>
    </tr>
    <tr>
      <td>2017</td>
      <td>ARTE</td>
      <td>3 001 213</td>
      <td>1 277 691</td>
    </tr>
    <tr>
      <td>2017</td>
      <td>BFM TV</td>
      <td>3 299 401</td>
      <td>1 860 405</td>
    </tr>
    <tr>
      <td>2017</td>
      <td>Canal+</td>
      <td>3 154 239</td>
      <td>890 497</td>
    </tr>
    <tr>
      <td>2017</td>
      <td>France 2</td>
      <td>2 936 590</td>
      <td>1 681 791</td>
    </tr>
    <tr>
      <td>2018</td>
      <td>Animaux</td>
      <td>1 475 340</td>
      <td>1 025 229</td>
    </tr>
    <tr>
      <td>2018</td>
      <td>ARTE</td>
      <td>3 644 717</td>
      <td>1 648 909</td>
    </tr>
    <tr>
      <td>2018</td>
      <td>BFM TV</td>
      <td>4 051 134</td>
      <td>2 378 788</td>
    </tr>
    <tr>
      <td>2018</td>
      <td>Radio Classique</td>
      <td>1 594 247</td>
      <td>910 651</td>
    </tr>
    <tr>
      <td>2018</td>
      <td>RFI</td>
      <td>6 046 376</td>
      <td>2 998 556</td>
    </tr>
    <tr>
      <td>2019</td>
      <td>Animaux</td>
      <td>1 310 231</td>
      <td>821 350</td>
    </tr>
    <tr>
      <td>2019</td>
      <td>ARTE</td>
      <td>1 448 996</td>
      <td>707 776</td>
    </tr>
    <tr>
      <td>2019</td>
      <td>BFM TV</td>
      <td>1 749 685</td>
      <td>910 678</td>
    </tr>
    <tr>
      <td>2019</td>
      <td>Canal+</td>
      <td>1 628 037</td>
      <td>478 149</td>
    </tr>
    <tr>
      <td>2019</td>
      <td>Canal+ Sport</td>
      <td>2 507 609</td>
      <td>135 782</td>
    </tr>
  </tbody>
</table>

<blockquote>
  <p>Tableau généré avec <a href="https://www.tablesgenerator.com">Tables Generator</a></p>
</blockquote>

<h2 id="3-visualisation-avec-flourish">3. Visualisation avec Flourish</h2>

<p>Pour cette première visualisation, j’ai utilisé Flourish pour visualiser pour chaque chaîne de télé et de radio le temps de parole des hommes et des femmes.</p>

<div class="flourish-embed flourish-chart" data-src="visualisation/16342816"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<p>Avec cette visualisation, on remarque que pour toutes les chaînes, que ce soit à la télé ou à la radio, les temps de parole des femmes est inférieur à celui des hommes.</p>

<h2 id="4-visualisation-avec-datawrapper">4. Visualisation avec Datawrapper</h2>

<p>Pour cette visualisation,</p>

<h3 id="test">test</h3>
<iframe title="Temps de parole des hommes et femmes à la télé et à la radio" aria-label="Barres regroupées" id="datawrapper-chart-q1kIy" src="https://datawrapper.dwcdn.net/q1kIy/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="17074" data-external="1"></iframe>
<script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>


      </section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        
        <p class="copyright">M2_DEFI_Datavisualisation_2024 maintained by <a href="https://github.com/Odilestar">Odilestar</a></p>
        
        <p>Published with <a href="https://pages.github.com">GitHub Pages</a></p>
      </footer>
    </div>
  </body>
</html>

