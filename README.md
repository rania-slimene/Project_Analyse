
<span style="color:#CB4335;font-family:serif; font-size:35px;">The GitHub History of the Scala Language 📚📈 <span>


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rania-slimene/project_Analyse/HEAD)

![Scala-Developer.jpg](https://cdn.educba.com/academy/wp-content/uploads/2021/01/Scala-Developer.jpg)


  ## :eyes: <span style="color:#CB4335;font-family:serif; font-size:32px;">Scala
</span> 
<p>Scala est un langage de programmation multi-paradigme comme Python, qui combine programmation fonctionnelle et orientée objet. Il fonctionne sur la machine virtuelle Java (JVM). Il a été développé en 2004 par Martin Oderski et est censé être plus rapide et plus convivial pour les développeurs.</p>


<!-- TABLE OF CONTENTS -->
<details>
  <summary style="color:#CB4335;font-family:serif; font-size:25px;">PLAN DE TRAVAIL</summary>
  <ol>
    <li>
      <a href="#about-the-project">Données du dépôt de projets réels de Scala</a>
    </li>
     <li>
      <a href="#about-the-project"> Préparation et nettoyage des données</a>
    </li>
     <li>
      <a href="#getting-started">Fusionner les DataFrames</a>
      <ul> </ul>
    </li>
    <li>
      <a href="#getting-started">Le projet est-il encore activement maintenu</a>
    </li>
    <li>
      <a href="#getting-started">Y a-t-il de la camaraderie dans le projet ?</a>
    </li>
     <li>
      <a href="#getting-started">Quels sont les fichiers qui ont été modifiés dans les dix dernières pull requests ?</a>
    </li>
    <li>
      <a href="#getting-started">Qui a fait le plus de pull requests sur un fichier donné ?</a>
    </li>
     <li>
      <a href="#getting-started"> Qui a fait le plus de pull requests sur un fichier donné ?</a>
    </li>
     <li>
      <a href="#getting-started">  Les pull requests de deux développeurs particuliers</a>
    </li>
     <li>
      <a href="#getting-started"> Visualiser les contributions de chaque développeur</a>
    </li>
    

</details>

<!-- ABOUT THE PROJECT -->
## :star2: <span style="color:#CB4335;font-family:serif; font-size:32px;"> A propos du projet
</span>
Les projets open source contiennent des historiques de développement complets, tels que les personnes qui ont apporté des modifications, les modifications elles-mêmes et les revues de code. Dans ce projet, vous devrez lire, nettoyer et visualiser le référentiel d'un projet Scala réel, qui comprend des données provenant d'un système de contrôle de version (Git) et d'un site d'hébergement de projets (GitHub). Avec près de 30 000 commits et une histoire qui s'étend sur plus de dix ans, Scala est un langage mature. Vous découvrirez qui a eu le plus d'influence sur son développement et qui sont les experts.

## :hammer_and_wrench:<span style="color:#CB4335;font-family:serif; font-size:32px;"> Prérequis
</span>
 
  * python
  * Jupyter Notebook

## :gear: <span style="color:#CB4335;font-family:serif; font-size:32px;"> Loading libraries 
</span>

<li> import pandas as pd</li>
<li> import matplotlib </li>

## 👩‍🏫 <span style="color:#CB4335;font-family:serif; font-size:32px;">Préparation des données
</span>

<p>notre projet composé de trois fichiers :<br/><mark>pulls_2011-2013.csv :</mark> contient les informations de base sur les demandes de pull, et s'étend de la fin de l'année 2011 jusqu'à (mais non compris) 
2014.s <br/>
<mark>pulls_2014-2018.csv :</mark> contient des informations identiques, et s'étend de 2014 à 2018.<br/>
<mark>pull_files.csv :</mark>contient les fichiers qui ont été modifiés par chaque demande de retrait.</p>

*  Et pour faciliter le travail nous devrons combiner les données des deux DataFrames pull  <code> pulls_2011-2013.csv</code> <code>pulls_2014-2018.csv </code> distincts pour travailler sur un seul dataframe.
</br>

* Ainsi nous avons fusionner  les des deux DataFrames  <code>pulls</code> <code>pull_files.csv </code> ,nous permettra d'analyser plus facilement les données dans les tâches futures.
  ####  Voila le resultat final : 
  <img src='data.PNG'/>


##  📊 <span style="color:#CB4335;font-family:serif; font-size:32px;"> Visualisation de données
</span>

* apres l'analyser nous avons constate que les personnes que a fait le plus nomber de pull et nomber de modification sur les fichiers se sont les personners qui a ete les plus implique sur le projet dans noter analyser  les des personners sont<mark>xeno-by</mark> et <mark>soc</mark> <br>
  <br/>
* Pour faire une distinction entre les niveaux d'expertise et de contribution globaux et les niveaux de contribution à un niveau plus granulaire (fichier, sous-module, etc.) Dans notre cas, nous voulons voir lequel de nos deux développeurs d'intérêt a le plus d'expérience avec le code d'un fichier donné. Nous mesurerons l'expérience par le nombre de pull requests soumises qui affectent ce fichier et la date à laquelle ces pull requests ont été soumises
et apres l'analyser on constate que <mark>xeno-by</mark> a eu le plus d'influence sur le  développement de scala et qui a  les puls experts.


 # <span style="color:#CB4335;font-family:serif; font-size:32px;"> MERCI  🥰
</span>