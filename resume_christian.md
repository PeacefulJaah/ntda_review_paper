# Résumés des articles (1 → 17)

---

## 1) Machine learning for human emotion recognition: a comprehensive review  
**Source**: Springer (2024)  
**Résumé synthétique**:
- **Objectif** : Faire le point sur les méthodes ML pour la reconnaissance des émotions humaines.  
- **Données / capteurs** : EEG, ECG, EMG, EDA/GSR, expressions faciales, audio.  
- **Méthodes** : CNN, LSTM/RNN, transformers, hybrid models, feature engineering (HRV, spectres EEG).  
- **Problèmes soulevés** : variabilité inter-sujets, déséquilibre de classes, besoin d’explicabilité et de datasets multimodaux.  
- **Implication sport** : importance pour monitorer stress, arousal et engagement en contexte sportif et e-sport.

---

## 2) Explainable e-sports win prediction through Machine Learning classification in streaming  
**Source**: ScienceDirect (2025)  
**Résumé synthétique**:
- **Objectif** : Prédire la victoire en e-sports en flux et fournir des explications interprétables.  
- **Données** : métriques in-game + signaux contextuels (parfois biométrie).  
- **Méthodes** : Random Forest, XGBoost, méthodes XAI (SHAP, LIME) pour interpréter features importants.  
- **Résultats** : amélioration des diagnostics tactiques et compréhension des facteurs psychophysiologiques impactant la victoire.  
- **Apport** : XAI rend actionable des prédictions pour coaching en live.

---

## 3) An efficient ML approach for extracting eSports players’ distinguishing features and classifying their skill levels  
**Source**: arXiv (2407.11972)  
**Résumé synthétique**:
- **Objectif** : Extraire features discriminantes et classifier le niveau de joueurs e-sport.  
- **Données** : EEG (et potentiellement autres biosignaux).  
- **Méthodes** : Symbolic Transfer Entropy (STE) pour mesurer interactions fonctionnelles + consensus nested cross-validation pour robustesse.  
- **Résultats** : STE identifie connectivité neuronale liée au skill ; la validation emboîtée améliore la confiance des scores de performance.  
- **Pertinence** : met en lumière la connectivité cérébrale comme biomarqueur de compétence.

---

## 4) A Machine Learning based Analysis of e-Sports Player Performances in League of Legends for Winning Prediction  
**Source**: ScitePress (2022)  
**Résumé synthétique**:
- **Objectif** : Prédire la victoire à partir des performances joueurs dans LoL.  
- **Données** : métriques match (actions, timings), propositions d’intégration de biométrie.  
- **Méthodes** : SVM, Decision Trees, XGBoost.  
- **Résultats** : les modèles ML classiques captent bien les patterns in-game ; corrélation probable entre indicateurs physiologiques (fatigue, stress) et variables de performance.  
- **Usage** : suggère d’ajouter HR/EEG pour améliorer prédiction et compréhension cognitive.

---

## 5) Predicting Counter-Strike Matches Using Machine Learning Models  
**Source**: Lund University (thèse/rapport)  
**Résumé synthétique**:
- **Objectif** : Prédire issues de matchs CS:GO via features de jeu.  
- **Données** : statistiques in-game (kills, assists, positions, economy).  
- **Méthodes** : modèles supervisés variés (Random Forest, Logistic Regression, etc.).  
- **Constat** : fortes complexités tactiques ; positionnement des joueurs et décisions stratégiques dominent la prédiction.  
- **Lien physiologie** : travail pose la question d’ajouter biométrie (stress, fatigue) pour expliquer variations de performance individuelle.

---

## 6) eSports Players Professional Level and Tiredness Prediction using EEG and ML  
**Source**: IEEE  
**Résumé synthétique**:
- **Objectif** : Prédire le niveau professionnel et la fatigue via EEG.  
- **Données** : EEG pendant sessions de jeu.  
- **Méthodes** : SVM, KNN (feature extraction : bandes fréquentielles, indices de puissance).  
- **Résultats** : classification de la fatigue et du niveau avec bonne performance ; certains patterns EEG (ex. variations dans les bandes thêta/alpha) corrèlent avec fatiguabilité.  
- **Importance** : montre la faisabilité du monitoring neural pour gérer la charge cognitive en e-sport.

---

## 7) A Machine Learning Based Predictive Analysis Use Case for eSports Games  
**Source**: Dergipark  
**Résumé synthétique**:
- **Objectif** : Cas d’usage d’un pipeline ML pour prédiction en e-sports.  
- **Données** : principalement métriques in-game ; proposition d’ajout de biométrie (HR, eye-tracking).  
- **Méthodes** : classification supervisée (RF, SVM).  
- **Résultats** : bonne performance sur features comportementales ; argument en faveur de la fusion multimodale pour capter aspects cognitifs/affectifs.  
- **Apport pratique** : exemple d’architecture et de prétraitements pour applications realtime.

---

## 8) Machine Learning Applications in Multiplayer Online Battle Arena Esports — A Systematic Review  
**Source**: Pertanika Journals (2025)  
**Résumé synthétique**:
- **Objectif** : Revue systématique sur ML en MOBA.  
- **Contenu** : catégorisation des études : prédiction de match, détection de comportements, personnalisation, intégration de biosignaux.  
- **Observations** : plupart des études reposent sur données in-game ; peu d’études fusionnent robuste­ment avec biosignaux, mais celles qui le font montrent des gains.  
- **Recommandation** : plus d’études multimodales et reproductibles, datasets publics et métriques standards.

---

## 9) Esports Analytics on PUBG Player Placement Prediction using ML  
**Source**: IJHATI  
**Résumé synthétique**:
- **Objectif** : Prédire placement final des joueurs dans PUBG.  
- **Données** : telemetry / métriques in-game (loot, mouvements, combats).  
- **Méthodes** : Random Forest, Logistic Regression, etc.  
- **Résultats** : features de positionnement et survie prédisent bien le classement ; limite : absence de mesures psychophysiologiques.  
- **Suggestion** : coupler avec HR/eye-tracking pour mieux comprendre décisions de risque et attention soutenue.

---

## 10) How Machine Learning in Sports Analytics Unlocks Next-Level Athlete Performance  
**Source**: Catapult (blog)  
**Résumé synthétique**:
- **Objectif** : Vulgarisation sur l’apport du ML en sport.  
- **Points clés** : tracking mouvement, workload, prédiction blessures, personnalisation entraînement, utilisation HRV/accéléromètres.  
- **Insight** : pipelines ML transforment données brutes en recommandations d’entraînement et récupération.  
- **Lien aux psychophysiologiques** : HRV, charge cardiaque, et métriques neuromusculaires sont des entrées cruciales pour modèles prédictifs.

---

## 11) Maximizing eSports (Apex Legends) Players Arena Performance With Big Data Modeling  
**Source**: IEEE  
**Résumé synthétique**:
- **Objectif** : Utiliser big data/ML pour optimiser performance en Apex Legends.  
- **Données** : logs jeu, comportements, biométrie explorée.  
- **Méthodes** : analyses statistiques, clustering, modèles prédictifs.  
- **Résultats** : identification de patterns de performance optimale ; biomarqueurs de stress/fatigue améliorent segmentation des joueurs.  
- **Application** : outils d’analyse pour coaching et optimisation de sessions.

---

## 12) Development of AI-based Model to Predict Esports Players’ Skill Levels  
**Source**: Staffordshire University (eprint)  
**Résumé synthétique**:
- **Objectif** : Modéliser et prédire niveaux de compétence.  
- **Données** : mix métriques de jeu et signaux physiologiques (ex. HR, EEG).  
- **Méthodes** : modèles supervisés, features liés à attention et réactivité.  
- **Résultats** : modèles capables d’estimer skill level ; physiologie améliore sensibilité pour détecter fatigue cognitive.  
- **Conséquence** : utile pour scouting / match-making adaptatif.

---

## 13) Method for Classifying Emotions in Older Adults Playing eSports  
**Source**: IEEE  
**Résumé synthétique**:
- **Objectif** : Classifier émotions chez personnes âgées jouant à des jeux.  
- **Données** : EEG, EDA, potentiellement expressions faciales.  
- **Méthodes** : extraction de features physiologiques + classification ML.  
- **Résultats** : classification fiable d’émotions; démontre transférabilité des méthodes de reconnaissance émotionnelle au contexte gaming inter-âges.  
- **Intérêt** : principes applicables au monitoring émotionnel des athlètes pour adapter charge/feedback.

---

## 14) The competitive esports physiological, affective, and video dataset  
**Source**: Nature (dataset)  
**Résumé synthétique**:
- **Objectif** : Publier un dataset multimodal en contexte compétitif.  
- **Contenu** : mesures ECG, GSR, EEG, annotations affectives, vidéos de sessions compétitives.  
- **Importance** : ressource publique pour entraîner et évaluer modèles ML sur reconnaissance d’émotion, stress, engagement en contexte réel.  
- **Impact** : facilite recherches reproductibles en psychophysiologie du jeu compétitif.

---

## 15) A Comparative Study of CNN, RNN-LSTM, and Transfer Learning Models for Facial Emotion Recognition in context of gaming  
**Source**: NCIRL (thèse/rapport)  
**Résumé synthétique**:
- **Objectif** : Comparer architectures DL pour reconnaissance des émotions faciales durant le jeu.  
- **Données** : séquences vidéo visage extraites de sessions de jeu.  
- **Méthodes** : CNN, LSTM, approches transfer learning (pretrained backbones).  
- **Résultats** : CNN+LSTM ou modèles transfer learning atteignent bonnes performances ; la temporalité du visage est importante pour capturer réactions émotionnelles.  
- **Application** : compléter signaux physiologiques pour un diagnostic affectif multimodal.

---

## 16) A machine learning investigation of factors that contribute to predicting cognitive performance: Difficulty level, reaction time and eye-movements  
**Source**: ScienceDirect  
**Résumé synthétique**:
- **Objectif** : Étudier comment difficulté, temps de réaction et eye-movements prédisent performance cognitive.  
- **Données** : tests cognitifs, eye-tracking, RTs.  
- **Méthodes** : modèles ML pour importance de features, analyses de variance.  
- **Résultats** : eye-tracking et RT sont prédicteurs significatifs de déclin cognitif/charge ; interaction entre difficulté et indicateurs oculaires.  
- **Pertinence sport** : eye-tracking utile pour monitorer attention et anticiper baisse de performance.

---

## 17) Machine learning and combinatorial analysis-based recognition of sports activity: An investigation using SVM and KNN classifiers  
**Source**: Combinatorial Press  
**Résumé synthétique**:
- **Objectif** : Reconnaître activités sportives via capteurs et analyser patterns.  
- **Données** : capteurs inertiels (IMU), potentiellement mesures physiologiques.  
- **Méthodes** : SVM, KNN, analyse combinatoire pour sélection features.  
- **Résultats** : SVM/KNN efficaces pour discriminer activités ; sélection combinatoire de features améliore robustesse.  
- **Application** : monitoring en temps réel des gestes et état physiologique pour feedback d’entraînement.

---

### Courte synthèse (en une phrase)
Les 17 articles montrent la richesse des approches ML appliquées aux signaux psychophysiologiques (EEG, ECG, HRV, GSR, eye-tracking, expressions faciales) pour prédire fatigue, émotions, niveau et performance ; la tendance forte est vers la fusion multimodale, la robustesse de validation et l’explicabilité pour rendre ces systèmes exploitables en coaching sportif et e-sport compétitif.
