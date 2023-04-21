
<h1>Prédire les ventes d'un jeu vidéo à l'aide du machine learning. En collaboration avec : C.Anselmo, K.Minatchy, D.Rivet</h1>

A partir du scrapping du site [vgchartz](https://www.vgchartz.com/gamedb/) nous avons analysé le marché du jeu vidéo et tenter de prédire les ventes à travers un modèle de regression.

Pour prédire les ventes nous avons tenté de collecter le plus de variables possible en scrappant également les sites [jeuxvideo.com](https://www.jeuxvideo.com/tous-les-jeux/) et [metacritic](https://www.metacritic.com/browse/games/score/metascore/all/all/filtered).
La spécificité de ce jeu de données et que celui-ci contient beaucoup d'outlier et n'a pas de temporalité de ventes (c'est à dire qu'elles sont toutes cumulées).
