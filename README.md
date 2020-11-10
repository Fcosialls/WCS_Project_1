# WCS_Project_1

Retrouvez le code ICI : 
https://github.com/Fcosialls/WCS_Project_1/blob/main/projet_Climat_FCosialls.ipynb
(Projet réalisé avec Google Colab)

# Introduction

> Décrit comme “[Le plus grand défi de l'histoire de l'humanité](https://www.youtube.com/watch?v=wW-acBEjQEM)”, le réchauffement climatique et ses conséquences font régulièrement la une de l’actualité.

> “Il s’agit du phénomène d'augmentation des températures moyennes océaniques et
de l'air, induit par la quantité de chaleur piégée à la surface terrestre, mesurée depuis plusieurs décennies, du fait des émissions de gaz à effet de serre (CO 2 , etc.).” - **Wikipédia**

> Cette situation est considérée comme alarmante pour plusieurs raisons, parmi
lesquelles : globalisation mondiale, pétrodépendance, raréfaction des matières
premières...

> Sur la scène de ce drame annoncé, il y a le GIEC, groupe d’expert mondial, qui a pris le sujet au sérieux et publie régulièrement des rapports détaillés censés pousser les décideurs mondiaux à l’action, même si pour l’instant les résultats des COP ont été jugées décevants. Il y a également les [collapsologues](https://www.youtube.com/watch?v=VrljSX_Fz9I), qui essaient d’étudier et de se préparer à l'effondrement des sociétés (civilisations) de notre monde thermo-industriel, effondrement qu’ils estiment inévitable et imminent. De l’autre côté, il y a les climatosceptiques, qui certes sont discrédités et décriés, mais existent bel et
bien, et [dans certains pays augmentent](https://www.huffingtonpost.fr/2018/04/10/les-climatosceptiques-sont-de-plus-en-plus-nombreux-aux-etats-unis-depuis-que-trump-est-president_a_23406376/). Enfin il y a le peuple, les activistes
climatiques, vous, moi, les observateurs actifs, les sceptiques convaincus, tous
acteurs d’un drame annoncé réel ou fictif.

> C’est au milieu de tout ce monde que vous, un Data Analyst, entrez en jeu. En tant que tel, vous avez une vision empirique et rationnelle du monde, avec la “data” comme support de votre raisonnement.

# **PARTIE 1** : Le réchauffement climatique est-il un phénomène réel ?

Afin de savoir si le réchauffement climatique est un phénomène réel, il nous faut observer l'évolution des températures dans le temps.

Cela nous permettra de constater si les températures ont tendances à augmenter, stagner ou même baisser. 

## Evolution de la température dans le temps.

Pour observer l'évolution de la température, nous utiliserons les températures annuelles moyennes par pays depuis 1875.

Les données remontent jusqu'à 1750. Mais nous avons choisi l'an 1875 car avant cela de nombreux pays ne disposaient pas de données. Par ailleurs, les données antérieures à la première moitié du 19ème siècle ne sont pas très fiables. L'augmentation est d'autant plus impressionnante après les années 1980.

![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/graph01.png)
![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/graph02.png)

## Cartographie de l'augmentation de la température

Les couleurs claires indiquent qu'un pays subit des températures au-dessus de sa température moyenne. Les couleurs sombres montrent des températures en dessous de sa température moyenne.

On remarque que la carte devient de plus en plus claire dans le temps, ce qui indique que les températures dépassent les moyennes. On observe donc bien une augmentation de la température globale.

L'augmentation est d'autant plus impressionnante après les années 1980.

![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/final_5faaf6ee92b69f00abe7416a_380895.gif)

## Nos Insights

### Augmentation de la température globale

*   Nous constatons que la température augmente aussi bien sur terre qu'au niveau des océans. Les graphiques que nous avons réalisés, permettent de s'en rendre compte.
  *   En appliquant une régression polynomiale à l'augmentation globale de la température. Nous constatons une tendance vers une augmentation de la température qui s'accélère dans le temps.
  *   Le graphique montrant l'écart avec la température moyenne permet d'ailleurs de se rendre compte facilement que l'augmentation de la température va en s'accélérant.

*   Au niveau du globe, nous constatons, grâce à notre carte interactive, qu'aucun pays n'est épargné par l'augmentation de la température.
  *   Nous observons que les pays de l'hémisphère nord sont plus touchés par le réchauffement climatique

### Limites

*   Nous avons calculé la température globale des océans en supposant que le poids de la température des océans et de la température terrestre était identique. C'est un parti pris qu'il faut prendre en compte et qui peut impacter nos observations.
---
# **PARTIE 2** : Dans quelle mesure l’Homme impacte t il le réchauffement climatique ?

Maintenant que nous avons observé qu'il y avait bel et bien une hausse globale des températures, nous souhaiterions avoir si l'homme a un impact sur le réchauffement climatique.


---


### Les informations officielles 

Le cinquième Rapport (**[Rapport du GIEC de 2014](https://www.ipcc.ch/site/assets/uploads/2018/02/SYR_AR5_FINAL_full_fr.pdf)**) d’évaluation a été finalisé entre 2013 et 2014 est on ne peut plus explicite :  
*   Les émissions anthropiques de **gaz à effet de serre**, qui ont augmenté depuis l’époque préindus-trielle en raison essentiellement de la **croissance économique et démographique**, sont actuelle-ment plus élevées que jamais[...]. il est extrêmement probable* qu’ils aient été la cause principale du réchauffement observé depuis le milieu du XXe siècle.
 

Dans le premier volet de ce rapport, le groupe d'experts du GIEC précise : « Le cumul des émissions de CO2 détermine dans une large mesure la moyenne mondiale du réchauffement en surface vers la fin du XXIe siècle et au-delà ».


---



### Les données que nous allons étudier

Nous commencerons d'abord par vérifier la corrélation entre la population humaine, les émissions de CO2 ainsi que l'augmentation de la température.

Comme précédemment, nous baserons nos observations sur des données allant de 1875 à 2015.



## Les correlations

Le tableau de corrélation nous montre des corrélations positives très fortes entre l'évolution de la population, des émissions de CO2 et de la température.

Cela confirme nos intuitions obtenues à la lecture du Rapport du GIEC de 2014.

![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/Annotation%202020-11-10%20213737.png)
![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/graph03.png)

## Observation de l'évolution de la population, des emissions de CO2 et de la température

![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/graph04.png)

## Qui emet le plus de CO2
![](https://raw.githubusercontent.com/Fcosialls/FCosialls_Portfolio/main/Projet_1/final_5faaf654fb92d7005e2e007d_482707.gif)

## Nos Insights

### L'impact de l'humanité sur le réchauffement climatique


*   Une très forte corrélation existe entre la température, la population et les émissions de CO2 :
    *   Coefficient de corrélation positif de 0.86 entre température et émission de CO2
    *   Coefficient de corrélation positif de 0.90 entre température et population 
*   Cette corrélation est d'autant plus flagrante lorsque l'on compare les graphiques et leurs régressions, entre eux.
*   Notre "Bar Chart Race", montrant les émissions de CO2 par pays de 1875 à 2018, nous apprend que :
    *    Les pays ayant émis le plus de CO2 sur une longue période sont les USA et l'Europe ! Ce n'est que depuis une vingtaine d'année que l'Asie a rattrapé les pays occidentaux en termes d'émissions de CO2...

### Limites
*   Nous avons choisi d'utiliser une régression polynomiale pour illustrer les différentes tendances, il existe bien évidemment d'autres méthodes.
*   Par ailleurs, il aurait été intéressant de prendre en compte l'impact de la croissance économique sur le réchauffement climatique.

---


