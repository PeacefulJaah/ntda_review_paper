# feedbacks avec le prof
## Feedback 1
Parler des différences d'évaluation (modèles)
Positionner les différentes méthodes (par rapport aux performances) -- Extrêmement difficile à comparer

Différents jeux de données (à quoi ils ressemblent)
nb données d'entraînement
Ressources nécessaires

Différencier les différentes méthodes d'analyse

Actualité des données? pas important

Avantages désavantages des modèles, est-ce qu'il y a des modèles que personne n'a appliqué

L'état de l'art TECHNIQUE sur le sujet

Lecteurs potentiels ? 
Manager sportif/ Coach de club:
Il se demanderait surtout : quelle méthode il appliquerait sur ses data (=> on s'en fiche des performances sur les données actuelles) Elle veut comprendre quelles sont les méthodes utilisables et fiables (parce qu'elle va l'utiliser sur ses propres données auxquelles on n'a pas accès nous).
Cherche à faire tourner un modèle.

Expert en DS :
Lui il chercherait à comprendre quelles sont les méthodes actuelles, (il ne va pas l'utiliser tel quel) mais il va vouloir comprendre les méthodes et comment les améliorer. Faire de la recherche approfondie sur le sujet.

## Feedback 2
Est-ce qu'on pourrait se poser la question d'analyser ce qui a permis la performance ou non à-posteriori, au lieu de chercher à prédire la future performance?
--> En quoi ça change dans les modèles et dans les résultats

 Dans la performance sportive et e-sportive les plus performant ont plusieurs de ces atouts:
	- Ceux qui ont la meilleure maîtrise technique de leur art/sport
	- Ceux qui ont la capacité d'analyse de la situation la plus rapide et la plus précise (décision-making)
	- Ceux qui détectent les faiblesses et points forts dans les temps morts (préparation stratégique)
	- Ceux qui ont le meilleur décision-making en temps réel (doublon avec le 2)
	- Ceux qui ont la meilleure résilience mentale, psychologique et physique

Comment on définit la performance au fait? Est-ce que c'est purement objectif, ou parfois subjectif aussi?
i.e on peut bien performer mais quand même perdre => la performance est qqch qui se mesure individuellement ou collectivement.
Un joueur avec un passif très bon doit faire des choses très bonnes pour avoir une bonne performances. Tandis qu'un joueur avec un passif pas très bon, doit faire nettement moins que le joueur 'talentueux' pour qu'on se dise que c'est une bonne performance pour qqun comme lui.

fonctionnement d'un SVM vs transformer-lstm

LSTM : Utilise les données temporelles
SVM : Pas temporelles mais données hautement dimensionnelles

Pourquoi l'un ou l'autre? BAE ?(check)

Dans d'autres domaines il y a des modèles très performants, pourquoi ne pas les appliquer ici pour les données séquentielles (Physiologiques). Est-ce qu'ils sont bien adaptés

Quelle est la norme établie pour ce domaine ? Il n'y en a pas vraiment => on peut facilement dire que notre méthode est meilleure.

La conclusion peut être subjective et critique sur l'état de l'art.

Trouver si une source a la même critique que nous sur l'état de l'art actuel.

# Notes autres
### Algorithmes regression linéaire :
	- LR
	- Stepwise regession
	- Ridge regression
	- Lasso regression
	- Elastic net regression
	- Principal component regression
Logistic regression

C'est quoi le ML dans le sport ?
utilisation des signaux physiologiques comme données supplémentaires 
	ECG, EMG, EG, Activité électrique de la peau, 

On veut améliorer les performances individuelles et collectives
	- Prédiction des conditions idéales individuelles
	- Détection des faiblesses des adversaires et soi-même
	- Détection des talents (caractéristiques physiques et mentales)


Diminuer les risques de :
	- blessure
	- Surcharge physique
	- Fatigue mentale
Burn-out

	• A qui s'adresse ce review paper SOA analysis
		○ On s'adresse aux professionnels du milieu sportif (managers, coachs, analystes, statisticiens)
		○ Aux scientifiques des données intéressés par le SOA et le milieu
	• Qui sont les concernés par ces recherches
		○ Professionnels sportifs
		○ Recherche en Data Science
	• Objectifs des analyses :
		○ Stratégies de confrontations :
		○ Analyses personnelles :
	• Gestion des données
		○ Récolte des données : quels signaux (features)
		○ Données temporelles (séries temporelles des données physiologiques)
		
	• Modèles d'analyse
		○ ML
			§ Modèles utilisés et leurs performances
		○ Statistiques
			§ Modèles utilisés avant et maintenant?
	• Problèmes sur le sujet :
		○ Hyper-spécialisation des modèles pour chaque sport --> Manque de généralisation
		○ Manque de maturité sur le sujet : choix des données, choix des algorithmes
		○ Normalement, on devrait pouvoir obtenir 90% d'accuracy sur les modèle de prédiction non?
			§ Check ressources qui parlent de ça
	
	• Problème du ML et la DS : on oublie comment faire les choses bien [Critique de l'état de l'art]
		○ Quels sont les modèles utilisés dans d'autres domaines et qu'on n'utilise pas?
		○ Qu'est-ce qu'on sait faire de bien mais qu'on n'applique plus
Manque du côté "explainable" dans les visualisations des données

Our goal is to explain what the SOA is : using simplified (ML ; psyphysio ; sports/esports planification/strategy/performance) concepts, give sports people and DS people an insight of the situation in ocmbining both fields and emitting my own critical pov to them and give them room for reflexion 

## Refs
### 1 
https://scholar.google.com/scholar_lookup?title=Machine%20learning%20and%20deep%20learning%20methods%20for%20intrusion%20detection%20systems%3A%20a%20survey&journal=Appl%20Sci&volume=9&issue=20&publication_year=2019&author=Liu%2CH&author=Lang%2CB
Consequently, this work contributes to an explainable win prediction classification solution in streaming in which input data is controlled over several sliding windows to reflect relevant game changes.
### 2
À partir de l’adresse <https://www.sciencedirect.com/science/article/pii/S1875952125001077> 
### 3
Martens et al. [45] have proposed to predict a winning team analyzing the toxicity of
in-game chat.
Märtens M, Shen S, Iosup A, Kuipers F (2015) Toxicity detection in multiplayer online games. In: 2015
International workshop on network and systems support for games (netgames). IEEE, pp 1–6
