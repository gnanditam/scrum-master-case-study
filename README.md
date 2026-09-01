# Cas pratique – Scrum Master

## Contexte

## ## 1. Diagnostic des dysfonctionnements

L'analyse de la situation met en évidence plusieurs dysfonctionnements qui affectent la prévisibilité, la qualité, l'auto-management de l'équipe et la capacité à livrer de la valeur.

### 1.1 Prévisibilité insuffisante

L'historique montre un écart important entre les engagements et les éléments réellement terminés :

| Sprint | Engagement | Terminé | Écart |
|---|---:|---:|---:|
| S21 | 48 | 31 | 17 |
| S22 | 51 | 29 | 22 |
| S23 | 47 | 27 | 20 |
| S24 | 52 | 28 | 24 |

La moyenne est de **49,5 points engagés contre 28,75 points terminés**.

Cette situation traduit une capacité de prévision insuffisante et une tendance à planifier au-delà de la capacité réellement observée de l'équipe.

### 1.2 Perturbation du Sprint

Le Product Owner ajoute des tâches en cours de Sprint.

L'évolution du Product Backlog est normale dans Scrum. Cependant, l'ajout fréquent de travail pendant le Sprint peut perturber le focus des Developers et compromettre l'atteinte du Sprint Goal si son impact n'est pas discuté.

### 1.3 Product Backlog insuffisamment préparé

Les tickets sont souvent mal définis.

Cela peut entraîner :

- des incompréhensions ;
- des estimations peu fiables ;
- des blocages ;
- du rework ;
- des retards ;
- une faible prévisibilité.

### 1.4 Qualité prise en charge trop tardivement

Les QA interviennent principalement en fin de Sprint.

Cette organisation augmente le risque de découvrir les défauts tardivement et de concentrer les activités de validation en fin de Sprint.

Les **3 incidents de production du mois dernier** constituent un signal important concernant la qualité du produit et du processus de livraison.

### 1.5 Auto-management limité

Le Tech Lead distribue directement les tâches aux Developers.

Cette pratique limite l'auto-management de l'équipe et crée une dépendance vis-à-vis du Tech Lead.

Les Developers doivent pouvoir décider eux-mêmes de la meilleure manière d'organiser leur travail pour atteindre le Sprint Goal.

### 1.6 Daily Scrum trop long

Le Daily dure environ **45 minutes**, alors que le Daily Scrum est limité à **15 minutes**.

Les discussions détaillées doivent être poursuivies après le Daily avec les personnes concernées.

### 1.7 Rétrospectives peu efficaces

La faible participation aux rétrospectives limite la capacité de l'équipe à inspecter régulièrement sa manière de travailler et à identifier des améliorations concrètes.

### 1.8 Pression sur la vélocité

Le management demande une augmentation de **30 % de la vélocité dès le prochain Sprint**.

La vélocité ne devrait pas être utilisée comme objectif de performance. Une pression sur cet indicateur peut entraîner des comportements contre-productifs, comme la sur-estimation, la prise de travail excessive ou la dégradation de la qualité.

### 1.9 Synthèse

Les principaux dysfonctionnements sont donc liés à :

- une prévisibilité insuffisante ;
- une perturbation du Sprint ;
- un Product Backlog insuffisamment préparé ;
- une prise en charge tardive de la qualité ;
- un auto-management limité ;
- des événements Scrum inefficaces ;
- une pression managériale excessive sur la vélocité ;
- des problèmes de qualité matérialisés par des incidents en production.

## ## 2. Top 5 des problèmes critiques

Après analyse de l'ensemble des dysfonctionnements, les cinq problèmes suivants sont considérés comme prioritaires selon leur impact sur la valeur, la qualité, la prévisibilité et la capacité de l'équipe à fonctionner efficacement.

| Priorité | Problème critique | Impact |
|---|---|---|
| **1** | Qualité insuffisante et incidents de production | Risque direct pour les utilisateurs et le produit |
| **2** | Engagements supérieurs à la capacité réelle | Faible prévisibilité et nombreux reports |
| **3** | Perturbations du Sprint | Risque sur le Sprint Goal et perte de focus |
| **4** | Tickets mal définis | Blocages, rework et estimations peu fiables |
| **5** | Auto-management insuffisant | Dépendance au Tech Lead et responsabilités mal réparties |

### Justification du classement

**1. Qualité et incidents de production**

Les trois incidents de production du mois dernier constituent le problème le plus critique. Ils peuvent affecter directement les utilisateurs, la confiance dans le produit et la capacité de l'équipe à livrer de la valeur.

**2. Engagements supérieurs à la capacité réelle**

L'équipe termine en moyenne 28,75 points alors qu'elle en planifie 49,5. Cet écart important explique en partie les nombreux reports et révèle un problème de prévisibilité.

**3. Perturbations du Sprint**

L'ajout de tâches en cours de Sprint par le Product Owner peut perturber le travail des Developers et compromettre le Sprint Goal lorsque l'impact n'est pas maîtrisé.

**4. Tickets mal définis**

Des éléments insuffisamment clarifiés entraînent des incompréhensions, des blocages, du rework et des estimations moins fiables.

**5. Auto-management insuffisant**

La distribution directe des tâches par le Tech Lead limite l'autonomie des Developers et crée une dépendance dans l'organisation du travail.

### Problèmes importants mais secondaires

Le Daily de 45 minutes et la faible participation aux rétrospectives restent des problèmes à traiter. Ils sont cependant considérés comme secondaires par rapport aux problèmes ayant un impact direct sur la qualité, la prévisibilité et la livraison de valeur.

## ## 3. Gestion de l'urgence du CEO

### Situation

Au jour 5 du Sprint, le CEO demande une fonctionnalité urgente estimée à 13 points, avec une livraison souhaitée pour vendredi.

Le Product Owner souhaite accepter immédiatement la demande tandis que le Tech Lead s'y oppose.

La demande doit être traitée en respectant les responsabilités Scrum et en protégeant autant que possible le Sprint Goal.

### 3.1 Clarifier la valeur et l'urgence

Le Product Owner doit clarifier :

- la valeur business de la fonctionnalité ;
- la raison de l'urgence ;
- les conséquences d'une livraison plus tardive ;
- les parties prenantes concernées ;
- le niveau de priorité par rapport aux autres éléments du Product Backlog.

Le fait que la demande provienne du CEO ne signifie pas automatiquement qu'elle doit être ajoutée au Sprint.

### 3.2 Évaluer l'impact sur le Sprint

Les Developers doivent analyser la faisabilité de la demande et son impact sur :

- le Sprint Goal ;
- les éléments déjà sélectionnés ;
- la capacité restante ;
- les dépendances ;
- les risques techniques ;
- la qualité et la Definition of Done.

Le Scrum Master facilite cette discussion mais ne décide pas à la place des Developers ou du Product Owner.

### 3.3 Arbitrer le périmètre

Si la fonctionnalité est réellement prioritaire, le Product Owner et les Developers peuvent discuter de l'adaptation du périmètre du Sprint.

L'objectif est de préserver le Sprint Goal tout en intégrant la demande si cela reste réaliste.

Il ne faut pas simplement ajouter 13 points au Sprint sans retirer ou réorganiser du travail.

### 3.4 Préserver la qualité

Compte tenu des trois incidents de production récents, l'équipe ne doit pas sacrifier la qualité pour respecter une date imposée.

La fonctionnalité doit respecter la Definition of Done avant d'être considérée comme terminée.

### 3.5 Si le Sprint Goal devient obsolète

Si la nouvelle demande rend le Sprint Goal obsolète, le Product Owner peut décider d'annuler le Sprint.

Dans ce cas, un nouveau Sprint peut être planifié autour du nouvel objectif.

### Décision recommandée

La recommandation est de **ne pas accepter automatiquement les 13 points**.

Il faut d'abord :

1. clarifier la valeur et l'urgence ;
2. analyser l'impact sur le Sprint Goal ;
3. laisser les Developers évaluer la faisabilité ;
4. négocier éventuellement le périmètre du Sprint ;
5. préserver la qualité et la Definition of Done ;
6. annuler le Sprint uniquement si le Sprint Goal devient obsolète.

Le Scrum Master joue ici un rôle de facilitation, de coaching et de protection du cadre Scrum, sans imposer lui-même la décision.

## ## 4. Plan d'amélioration à 30 jours

L'objectif du plan est de stabiliser le fonctionnement de l'équipe, améliorer la qualité, réduire les reports et les perturbations du Sprint, puis mettre en place une démarche d'amélioration continue.

### Objectifs à 30 jours

- Améliorer la prévisibilité des Sprints.
- Réduire le taux de tickets reportés.
- Réduire les incidents de production.
- Améliorer la qualité du Product Backlog.
- Renforcer l'auto-management des Developers.
- Améliorer l'efficacité des événements Scrum.

---

### Jours 1 à 7 – Stabiliser

**Priorité : réduire les perturbations et traiter les problèmes les plus critiques.**

Actions :

- Clarifier les rôles et responsabilités Scrum avec toute l'équipe.
- Rappeler que les Developers s'organisent eux-mêmes pour réaliser le travail.
- Clarifier le rôle du Tech Lead afin qu'il n'attribue pas directement les tâches.
- Identifier les principaux impediments qui ralentissent l'équipe.
- Analyser les trois incidents de production récents afin d'identifier leurs causes.
- Vérifier la Definition of Done et identifier les éventuels écarts.
- Ramener le Daily Scrum à 15 minutes maximum.

**Résultat attendu :** une équipe plus autonome, moins perturbée et consciente de ses principaux obstacles.

---

### Jours 8 à 15 – Améliorer le Product Backlog

**Priorité : améliorer la qualité et la compréhension des éléments avant leur sélection dans un Sprint.**

Actions :

- Mettre en place des sessions régulières de Product Backlog Refinement.
- Clarifier les besoins et la valeur des éléments.
- Améliorer les critères d'acceptation.
- Découper les éléments trop volumineux.
- Identifier les dépendances et les risques.
- Impliquer les Developers et les QA dans la clarification des éléments.
- Vérifier régulièrement que les éléments prioritaires sont suffisamment compris pour être sélectionnés.

**Résultat attendu :** des éléments de Product Backlog mieux compris, mieux découpés et

## 5. Amélioration des événements Scrum

### Sprint Planning
### Daily Scrum
### Product Backlog Refinement
### Sprint Review
### Sprint Retrospective

## 6. Métriques de suivi

## 7. Gestion de la demande de +30 % de vélocité

## Conclusion

## Outils utilisés
