# Travaux pratiques: BRISBANE City Bike
Dans le cadre de notre enseignement sur les Big Data, nous avons réalisé ce projet pour mettre en pratique nos compétences en matière de Spark. </br>
Nous avons utilisé la base de données des stations vélos dans la ville BRISBANE. </br>
L'objectif de ce travail est d'effectuer un clustering par la méthode de KMeans ainsi que la visualisation du résultats sur une carte. </br>
La structure du projet est comme suit: </br>

:arrow_right_hook: <b> config </b>:  </br>
&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right_hook: <b> properties.conf</b>: Le fichier config contenant les configuration nécessaires pour ce projet à savoir le chemin des données, le chemin de sauvgarde et le nombre de classe pour la méthode KMeans  </br>
  
:arrow_right_hook: <b> data </b>:  </br>
&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right_hook: <b> Bristol-city-bike.json </b>: Le jeux de données utilisé   </br>

:arrow_right_hook: <b> enonce </b>:  </br>
&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right_hook: <b> kmeans.pdf </b>: L'énoncé de ce projet   </br>

:arrow_right_hook: <b> exported </b>:  </br>
&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right_hook: <b> part-[RDD-partition-number].csv </b>: Le fichier final sauvgardé sous format csv et contenant les colonnes: 
  * latitude  
  * longitude  
  * prediction  
  
:arrow_right_hook: <b> output </b>:  </br>
&nbsp;&nbsp;&nbsp;&nbsp;:arrow_right_hook: <b> Bristol-City-bike.html </b>: La carte sauvgardée sous format HTML  </br>

:arrow_right_hook: <b> KMeans.ipynb </b>: Un jupyter notebook contenant les réponses à l'énoncé  </br>
