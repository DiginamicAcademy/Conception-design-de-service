[← Chapitre précédent](03-J2-Cours-Du-blueprint-a-l-application.md) · [Sommaire](Readme.md) · [Chapitre suivant →](A-Briefs-projets.md)

# Jour 2 · Atelier — Concevoir et soutenir

> **Jour 2, fin de matinée et après-midi — 3 h 35 d'atelier, 1 h 10 de soutenance et de bilan.** Vous appliquez au blueprint de votre équipe la démarche du [cours de ce matin](03-J2-Cours-Du-blueprint-a-l-application.md) : passer du service à l'application, assembler le dossier de conception, puis défendre l'ensemble devant le groupe.

## 🎯 Objectifs de l'atelier

À la fin de la journée, votre équipe aura :

1. Tenu compte des retours de la veille et éprouvé son blueprint par une marche à blanc.
2. Tiré du blueprint les acteurs, les cas d'utilisation et les modules de l'application.
3. Identifié les objets du domaine et le cycle de vie de l'objet central.
4. Détaillé un moment de vérité en diagramme de séquence, chemins d'erreur compris.
5. Traduit ses engagements en niveaux de service, et ses contraintes en exigences non fonctionnelles.
6. Assemblé un dossier de conception traçable, du blueprint aux niveaux de service.
7. Soutenu sa démarche complète, du brief à l'architecture.

## Livrables attendus

Tout est rangé dans la page `J2 – Conception` de l'espace d'équipe. Les diagrammes peuvent être dessinés à la main et photographiés, ou écrits en Mermaid ou en PlantUML.

| # | Livrable | Format | Critère de réussite |
|---|---|---|---|
| 9 | Blueprint révisé | le blueprint d'hier, corrigé | les retours d'hier intégrés ; les trous trouvés par la marche à blanc, listés et traités |
| 10 | Cas d'utilisation et modules | diagramme de cas d'utilisation, tableau [B.8](B-Modeles-et-canevas.md) | chaque cas d'utilisation vient d'un couloir du blueprint ; un module par capacité ; un adaptateur par système existant |
| 11 | Domaine et cycle de vie | diagramme de classes simplifié, diagramme d'états | cinq à huit objets ; données personnelles repérées ; états visibles par l'usager, états finaux compris |
| 12 | Séquence d'un moment de vérité | diagramme de séquence | au moins deux branches d'erreur, tirées des ruptures du blueprint |
| 13 | Niveaux de service et exigences | gabarit B.9 | trois engagements traduits en indicateur, objectif et conséquence ; trois exigences non fonctionnelles avec leur origine |
| 14 | Matrice de traçabilité | gabarit B.7 | chaque étape du scénario principal, de l'étape du blueprint au niveau de service |
| 15 | Ce que le service ne fera pas, et plan de pilote | gabarit B.9, une demi-page | chaque renoncement justifié ; un pilote avec un lieu, une durée, des participants et les indicateurs mesurés |
| 16 | Entrée du journal de conception | gabarit B.12 | les décisions du jour, et ce que la marche à blanc a changé |
| 17 | Soutenance | 8 min de présentation, 4 min de questions | voir plus bas |

## Organisation

### Nouveaux rôles

Les rôles changent de main : le ou la porte-parole d'hier devient scribe, et ainsi de suite. À la soutenance, **chaque membre de l'équipe prend la parole**.

### Le travail en binômes

Pour les étapes 8 et 9, l'équipe se partage en deux binômes, qui travaillent en parallèle et se resynchronisent entre deux étapes. Les étapes 7 et 10 se font à toute l'équipe.

| | Étape 8 — 1 h 05 | Étape 9 — 50 min |
|---|---|---|
| **Binôme A** | acteurs, cas d'utilisation, modules | séquence d'un moment de vérité |
| **Binôme B** | objets du domaine, cycle de vie de l'objet central | niveaux de service, exigences non fonctionnelles |

Dans une équipe de trois, le binôme B est une seule personne, et le diagramme de classes se limite aux objets qui portent des données personnelles et à l'objet central.

## Déroulé

| Horaire | Étape | Durée |
|---|---|---|
| 10:45 | Lancement : nouveaux rôles, binômes | 10 min |
| 10:55 | Étape 7 — Retours d'hier et marche à blanc | 30 min |
| 11:25 | Étape 8 — En binômes : cas d'utilisation et modules, domaine et cycle de vie | 1 h 05 |
| 12:30 | Déjeuner | 1 h |
| 13:30 | Mise en commun des deux binômes | 10 min |
| 13:40 | Étape 9 — En binômes : séquence d'un moment de vérité, niveaux de service | 50 min |
| 14:30 | Étape 10 — Ensemble : le dossier de conception | 40 min |
| 15:10 | Pause | 10 min |
| 15:20 | Préparation de la soutenance, avec une répétition | 30 min |
| 15:50 | Soutenance et bilan | 1 h 10 |

---

## Étape 7 — Retours d'hier et marche à blanc (30 min)

1. **Relisez les retours** reçus hier à la restitution. Pour chacun, décidez : on en tient compte, ou non, et pourquoi. Notez-le dans le journal. (8 min)
2. **Faites une marche à blanc** de votre blueprint, puis rejouez au moins une rupture : le système ne répond pas, l'usager se trompe, la personne attendue est absente. (22 min)
   - Une personne joue l'usager ; les autres jouent le personnel et les systèmes. On peut jouer un système : « Je suis le logiciel de gestion, je ne connais que le stock d'hier soir. »
   - Déroulez le scénario à voix haute, étape par étape, en suivant le blueprint.
   - À chaque étape, trois questions : **« Qui fait ça ? Comment le sait-il ? Et si ça ne marche pas ? »**
   - Chaque trou trouvé va sur un post-it rouge, à l'endroit du blueprint où il se trouve. Corrigez le blueprint au fur et à mesure.

## Étape 8 — En binômes (1 h 05)

### Binôme A — Acteurs, cas d'utilisation, modules

1. **Des parties prenantes aux acteurs.** Reprenez la carte de l'écosystème : qui interagit directement avec le système ? Distinguez acteurs principaux et acteurs systèmes, et notez qui n'est pas un acteur. (10 min)
2. **Lisez les cas d'utilisation couloir par couloir** : les actions de l'usager, le frontstage humain, le backstage, les processus support. N'oubliez ni les cas du **personnel**, ni ceux que déclenche **le temps** — une échéance, une synchronisation, une relance. (20 min)
3. **Dessinez le diagramme de cas d'utilisation.** (15 min)
4. **Regroupez les cas d'utilisation par capacité** et déduisez-en les modules, avec le gabarit B.8. Prévoyez un **adaptateur** pour chaque système existant. (20 min)

### Binôme B — Domaine et cycle de vie

1. **Relevez les objets du domaine** dans les annotations **D** du blueprint et dans les noms qui reviennent d'un couloir à l'autre. (15 min)
2. **Dessinez le diagramme de classes simplifié** : les objets, quelques attributs, les relations et leurs multiplicités. Signalez les données personnelles, et parmi elles les données sensibles. (25 min)
3. **Choisissez l'objet central** — celui qui traverse tout le blueprint — et dessinez son **diagramme d'états** : des états que l'usager peut voir, des transitions avec leur auteur, les minuteries, les états finaux. (25 min)

## Mise en commun des deux binômes (10 min)

Chaque binôme présente son travail à l'autre en cinq minutes. Les deux emploient-ils les mêmes mots ? Si le binôme A parle de « demande » et le binôme B de « dossier » pour la même chose, choisissez un seul terme, maintenant. Chaque module de l'un doit être responsable d'objets de l'autre.

## Étape 9 — En binômes (50 min)

### Binôme A — Séquence d'un moment de vérité

1. Choisissez le moment de vérité qui comporte **le plus de passages de relais**. (5 min)
2. Prenez pour participants les acteurs et les modules de l'étape 8, et dessinez le chemin nominal. (15 min)
3. Ajoutez **au moins deux branches d'erreur**, tirées des ruptures **F** du blueprint. (20 min)
4. Marquez les échanges asynchrones et les minuteries, et vérifiez que chaque message entre deux modules correspond à un échange prévu à l'étape 8. (10 min)

### Binôme B — Niveaux de service et exigences

Avec le gabarit B.9 :

1. Pour trois engagements : un **indicateur**, un **objectif**, une **conséquence** pour la conception. Repérez l'engagement qui se mesure par observation plutôt que par le logiciel, s'il y en a un. (25 min)
2. Trois **exigences non fonctionnelles** — sécurité et droits d'accès, données personnelles, accessibilité, robustesse, sobriété — et pour chacune, son **origine** dans le blueprint. (25 min)

## Étape 10 — Ensemble : le dossier de conception (40 min)

Toute l'équipe se retrouve pour assembler ce qui a été produit en binômes.

1. **La matrice de traçabilité** [B.7](B-Modeles-et-canevas.md) : une ligne par étape du scénario principal, de l'étape du blueprint au niveau de service. Une case vide est un trou de conception : comblez-le, ou notez-le comme question ouverte. (20 min)
2. **Ce que le service ne fera pas**, avec la raison : c'est souvent ce que le commanditaire avait demandé. (10 min)
3. **Un plan de pilote**, en quelques lignes : où, combien de temps, avec qui, et quels indicateurs de l'étape 9 vous mesurerez. (10 min)

## Préparer la soutenance (30 min)

Une présentation de **huit minutes**, sans diaporama : on montre le mur ou l'espace partagé. **Chaque membre de l'équipe prend la parole.**

| Temps | Contenu |
|---|---|
| 1 min | Le service en une phrase, et la rupture du parcours actuel qui justifie le projet |
| 2 min | Le blueprint cible, parcouru sur le moment de vérité principal ; ce que la marche à blanc a changé |
| 2 min | Du blueprint à l'application : acteurs, modules, objet central et son cycle de vie |
| 1 min 30 | Le moment de vérité en séquence, branche d'erreur comprise, et ses niveaux de service |
| 1 min | Une ligne de la matrice de traçabilité, lue de bout en bout |
| 30 s | Ce que le service ne fera pas, et le plan de pilote |

Gardez les dix dernières minutes pour **une répétition complète**, chronomètre en main.

## Soutenance et bilan (1 h 10)

Chaque équipe dispose de **huit minutes de présentation et quatre minutes de questions**. Le formateur évalue avec la grille [B.11](B-Modeles-et-canevas.md) ; le groupe note ses retours avec la grille B.10.

Le genre de questions auxquelles vous préparer — ce sont aussi celles d'un jury :

- « Montrez-moi où ce module apparaît dans le blueprint. »
- « Que se passe-t-il pour l'usager si ce système externe ne répond pas ? »
- « Qui voit cette donnée personnelle, et pourquoi ? »
- « Comment saurez-vous, dans trois mois, que cet engagement est tenu ? »
- « Pourquoi ne pas avoir fait ce que demandait le commanditaire ? »
- « Que fait votre service pour quelqu'un qui n'a pas de smartphone ? »

Le bilan, dix minutes : un tour de table, une phrase chacun·e — « Dans mon prochain projet, je ferai différemment… ».

---

## Critères de réussite

- [ ] Les retours d'hier ont été traités, et la marche à blanc a modifié le blueprint.
- [ ] Chaque cas d'utilisation se rattache à un couloir du blueprint ; les cas du personnel et ceux déclenchés par le temps sont présents.
- [ ] Les modules correspondent à des capacités, et les systèmes existants sont isolés derrière des adaptateurs.
- [ ] Le diagramme d'états a des états finaux, et dit ce que deviennent les données personnelles.
- [ ] La séquence comporte au moins deux branches d'erreur, issues des ruptures du blueprint.
- [ ] Chaque niveau de service a un indicateur, un objectif atteignable et une conséquence pour la conception.
- [ ] Chaque exigence non fonctionnelle pointe vers une case du blueprint.
- [ ] La matrice de traçabilité couvre tout le scénario principal, sans case vide inexpliquée.
- [ ] Ce que le service ne fera pas est dit, et justifié ; le plan de pilote dit quels indicateurs seront mesurés.
- [ ] Toute l'équipe a pris la parole.

## Pièges fréquents

| Piège | Comment l'éviter |
|---|---|
| Des cas d'utilisation qui sont des écrans | « Page d'accueil » n'est pas un cas d'utilisation ; « Réserver un titre » en est un |
| Oublier le personnel et le temps | relisez le backstage et le support, couloir par couloir |
| Un module par écran, ou par acteur | regroupez par capacité : un acteur se sert de plusieurs modules |
| Des microservices par réflexe | un monolithe modulaire, des adaptateurs pour l'existant |
| Un diagramme d'états sans fin | qu'advient-il de l'objet, et des données personnelles, quand tout est terminé ? |
| Une séquence sans branche d'erreur | les ruptures **F** du blueprint sont vos branches `alt` |
| Des objectifs à 100 % | un objectif atteignable, un budget d'erreur, une procédure de correction |
| Des exigences sans origine | « sécurisé » ne veut rien dire ; « un agent ne voit que les dossiers de son secteur, parce que… » veut dire quelque chose |

## Si vous avez fini en avance

- Rédigez **trois user stories** du moment de vérité principal, avec leurs critères d'acceptation au format Gherkin.
- Esquissez le **modèle conceptuel de données** de l'objet central et de ce qui l'entoure.
- Déroulez en séquence le **blueprint d'incident**, si vous l'avez dessiné hier.

---

[← Chapitre précédent](03-J2-Cours-Du-blueprint-a-l-application.md) · [Sommaire](Readme.md) · [Chapitre suivant →](A-Briefs-projets.md)
