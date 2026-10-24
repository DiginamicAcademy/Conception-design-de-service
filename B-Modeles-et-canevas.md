[← Chapitre précédent](A-Briefs-projets.md) · [Sommaire](Readme.md) · [Chapitre suivant →](C-Glossaire-et-ressources.md)

# Annexe B — Modèles et canevas

Les gabarits de tous les livrables, à recopier sur une grande feuille, dans un tableau blanc partagé ou dans le dépôt de l'équipe. Ce sont des points de départ : adaptez-les à votre service, mais gardez-en les rubriques.

| Quand | Gabarits |
|---|---|
| Jour 1, atelier | B.1 écosystème · B.2 promesse et engagements · B.3 carte de parcours · B.4 service blueprint · B.5 relecture du blueprint · B.12 journal de conception |
| Jour 1, restitution | B.10 grille de retours |
| Jour 2, atelier | B.6 marche à blanc · B.7 matrice de traçabilité · B.8 capacités et modules · B.9 niveaux de service et exigences · B.12 journal de conception |
| Jour 2, soutenance | B.10 grille de retours · B.11 grille d'évaluation |

---

## B.1 — Carte de l'écosystème

**Les parties prenantes.** Une ligne par partie prenante ; placez-les ensuite dans les cinq cercles, de l'usager vers l'environnement.

| Cercle | Partie prenante | Ce qu'elle gagne au service | Ce qu'elle doit faire pour lui | Peut-elle le faire échouer ? |
|---|---|---|---|---|
| Au centre | | | | |
| Au contact | | | | |
| En coulisses | | | | |
| Partenaires | | | | |
| Environnement | | | | |

Marquez d'un ⚠ celles qui doivent faire un effort **sans en tirer de bénéfice**.

**Les flux.** Au moins cinq.

| De | Vers | Ce qui circule | Nature | Canal |
|---|---|---|---|---|
| | | | information · donnée personnelle · argent · objet · décision | |

**Les systèmes existants.**

| Système | Propriétaire | Ce qu'il sait | Comment on lui parle | Contraintes : licence, contrat, réversibilité |
|---|---|---|---|---|
| | | | API · export · saisie · rien | |

Avant de passer à la suite :

- [ ] Ceux qui reçoivent, rendent, paient, financent et contrôlent le service sont présents.
- [ ] Les usagers multiples sont distingués : celui qui demande n'est pas toujours celui qui bénéficie.
- [ ] Chaque flux de données personnelles est identifié comme tel.
- [ ] Chaque système existant dit comment on lui parle.

---

## B.2 — Promesse et engagements

**Le côté usager**, pour l'usager principal. Classez chaque élément par importance, de 1 à 3.

| Tâches : ce qu'il cherche à accomplir | Problèmes : ce qui le gêne, ce qu'il redoute | Bénéfices : ce qu'il espère |
|---|---|---|
| | | |

**Le côté service.**

| Ce que propose le service | Ce qui soulage les problèmes | Ce qui crée les bénéfices |
|---|---|---|
| | | |

**La promesse, en une phrase.**

> Pour **[usager]** qui **[besoin]**, **[service]** permet de **[bénéfice principal]**, contrairement à **[solution actuelle]**.

**Les engagements**, trois à cinq.

| # | Engagement, du point de vue de l'usager | Pour qui | Comment on saura qu'il est tenu | Le débat de conception qu'il tranche |
|---|---|---|---|---|
| E1 | « … » | | | |
| E2 | « … » | | | |
| E3 | « … » | personnel ou partenaire | | |

- [ ] Chaque engagement est vérifiable, et formulé du point de vue de celui qui reçoit le service.
- [ ] Aucun engagement n'est une fonctionnalité déguisée.
- [ ] Au moins un engagement concerne les personnes qui rendent le service.

---

## B.3 — Carte de parcours

À utiliser deux fois : pour le parcours **actuel**, puis pour le parcours **cible**.

**Usager :** … · **Objectif :** … · **Parcours :** actuel / cible

| | Étape 1 | Étape 2 | Étape 3 | Étape 4 | Étape 5 | Étape 6 |
|---|---|---|---|---|---|---|
| **Phase** | avant | | pendant | | | après |
| **Actions** | | | | | | |
| **Canaux** | | | | | | |
| **Points de contact** | | | | | | |
| **Pensées, émotions** | + / = / − | | | | | |
| **Ruptures** *(actuel)* | | | | | | |
| **Moments de vérité** *(cible)* | | | | | | |
| **Opportunités** | | | | | | |

Une rupture, c'est : un changement de canal qui oblige à répéter, une information perdue, une attente sans nouvelles, un passage de relais raté en coulisses.

- [ ] Le parcours actuel ne fait apparaître aucun élément de la solution future.
- [ ] L'après est présent : clôture, relance, effacement, réclamation.
- [ ] Le parcours cible fonctionne pour un usager **sans smartphone**, sans qu'il ait à recommencer.

---

## B.4 — Service blueprint

**Scénario :** usager … · objectif … · chemin nominal / incident … · déclencheur … · fin …

| | Étape 1 | Étape 2 | Étape 3 | Étape 4 | Étape 5 |
|---|---|---|---|---|---|
| **Preuves physiques** | | | | | |
| **Actions de l'usager** | | | | | |
| *ligne d'interaction* | | | | | |
| **Frontstage numérique** | | | | | |
| **Frontstage humain** | | | | | |
| *ligne de visibilité* | | | | | |
| **Backstage** | | | | | |
| *ligne d'interaction interne* | | | | | |
| **Processus support** | | | | | |

**Les repères**, posés directement sur les cases :

| Repère | Signification |
|---|---|
| ⚠ F1, F2… | point de rupture |
| ⌛ A1, A2… | attente de l'usager |
| ★ MV1, MV2… | moment de vérité |
| D | données manipulées |
| RG | règle de gestion |

**Les ruptures et ce que le service en fait.**

| Rupture | Ce qui se passe | Ce que prévoit le service | Question ouverte |
|---|---|---|---|
| F1 | | | |

Sur un mur : une couleur de post-it par couloir, les lignes au ruban adhésif, des flèches entre les cases qui dépendent l'une de l'autre.

---

## B.5 — Relecture d'un blueprint

À faire par l'équipe, puis par une autre équipe si le temps le permet.

- [ ] Le blueprint suit **un seul** scénario, énoncé en tête.
- [ ] Les colonnes sont des étapes vécues par l'usager, pas des écrans.
- [ ] Chaque action de l'usager a quelque chose en dessous pour la rendre possible.
- [ ] Chaque étape a une preuve physique, ou l'absence de preuve est voulue.
- [ ] Le frontstage humain et le frontstage numérique sont distingués.
- [ ] Les coulisses nomment des personnes et des systèmes réels : aucune case « le système ».
- [ ] Les systèmes existants de la carte de l'écosystème apparaissent dans les processus support.
- [ ] Chaque flèche qui traverse une ligne dit qui transmet quoi.
- [ ] Au moins trois ruptures et une attente sont annotées, et chacune a une réponse ou une question ouverte.
- [ ] L'après est présent.

---

## B.6 — Marche à blanc

**Distribution des rôles.** Une personne joue l'usager ; les autres jouent le personnel et les systèmes. Une même personne peut tenir plusieurs rôles qui n'interviennent jamais en même temps.

| Rôle | Joué par | Ce qu'il sait au départ |
|---|---|---|
| Usager | | |
| | | |
| Système : … | | « Je ne connais que… » |

**Consignes.**

1. Déroulez le scénario du blueprint à voix haute, étape par étape. Chacun ne dit et ne fait que ce que son rôle sait et peut faire.
2. À chaque étape, trois questions : **« Qui fait ça ? Comment le sait-il ? Et si ça ne marche pas ? »**
3. Chaque trou trouvé va sur un post-it rouge, posé à l'endroit du blueprint où il se trouve.
4. Rejouez au moins une rupture : le système ne répond pas, l'usager se trompe, la personne attendue est absente.

**Les trous trouvés.**

| Étape | Le trou | Correction apportée au blueprint |
|---|---|---|
| | | |

---

## B.7 — Matrice de traçabilité

Une ligne par étape importante du blueprint, en commençant par le moment de vérité principal.

| Étape du blueprint | Moment de vérité | Cas d'utilisation | Module | Objets du domaine | Rupture traitée | Niveau de service |
|---|---|---|---|---|---|---|
| *Lucioles* — 3. Être prévenu | MV2 | Confirmer ou décliner une réservation | Réservations, Notifications | Reservation, Message | F2 : demande non vue | E1 : 90 % traitées en moins de 30 min |
| | | | | | | |

---

## B.8 — Capacités et modules

| Capacité | Cas d'utilisation regroupés | Module | Données dont il est responsable | Échange avec | Adaptateur vers |
|---|---|---|---|---|---|
| | | | | | |

Les interfaces — site public, outil du personnel, tableau de pilotage — ne sont pas des modules métier : elles **utilisent** les modules.

- [ ] Chaque module correspond à une capacité, pas à un écran, à un acteur ou à un service de l'organigramme.
- [ ] Chaque donnée a **un seul** module responsable.
- [ ] Chaque système existant est isolé derrière un adaptateur.
- [ ] Les cas d'utilisation déclenchés par le temps ont trouvé leur module.

---

## B.9 — Niveaux de service et exigences

**Les niveaux de service.**

| Engagement | Indicateur (SLI) | Objectif (SLO) | Période | Mesuré par | Conséquence pour la conception |
|---|---|---|---|---|---|
| E1 | | | | le logiciel · une observation · une enquête | |
| E2 | | | | | |
| E3 | | | | | |

**Les exigences non fonctionnelles.**

| Exigence | Son origine dans le blueprint | Formulation vérifiable | Comment on la vérifiera |
|---|---|---|---|
| Sécurité, droits d'accès | | | |
| Données personnelles | | | |
| Accessibilité | | | |
| Robustesse, mode dégradé | | | |
| Sobriété | | | |

**Ce que le service ne fera pas.**

| Ce que le service ne fera pas | Pourquoi | Peut-être plus tard ? |
|---|---|---|
| | | |

- [ ] Aucun objectif à 100 % ; un écart qui touche l'usager s'accompagne d'une procédure de correction.
- [ ] Chaque exigence se vérifie par un test, une mesure ou un audit.

---

## B.10 — Grille de retours

Une grille par équipe qui présente. Les retours portent sur le travail, jamais sur les personnes.

| Équipe | J'ai aimé… | Je me demande… | Je propose… |
|---|---|---|---|
| | ce qui est clair, convaincant, bien fondé | ce qui n'est pas étayé, ce qui reste flou | une piste concrète pour la suite |

---

## B.11 — Grille d'évaluation de la soutenance

Chaque critère est noté de 0 à 3 : **0** non abordé · **1** abordé, insuffisant · **2** satisfaisant · **3** remarquable.

| # | Critère | Ce qu'on attend | Note |
|---|---|---|---|
| 1 | Compréhension du besoin | les hypothèses du brief sont distinguées des faits ; les ruptures du parcours actuel sont étayées par les observations | /3 |
| 2 | Écosystème | toutes les parties prenantes, y compris celles qui font le travail ; les systèmes existants et les flux de données personnelles | /3 |
| 3 | Promesse et engagements | une promesse claire ; des engagements vérifiables, dont un pour le personnel | /3 |
| 4 | Parcours cible | omnicanal, praticable sans smartphone ; moments de vérité identifiés, avec un plan de secours | /3 |
| 5 | Blueprint | un seul scénario ; des coulisses nommées ; des ruptures annotées et traitées ; modifié par la marche à blanc | /3 |
| 6 | Du blueprint à l'application | acteurs et cas d'utilisation tirés du blueprint ; modules par capacité ; adaptateurs pour l'existant ; traçabilité | /3 |
| 7 | Domaine et cycle de vie | des objets cohérents ; des états visibles par l'usager ; la fin de vie des données personnelles | /3 |
| 8 | Moment de vérité en séquence | des chemins d'erreur issus des ruptures ; des interfaces et des minuteries identifiées | /3 |
| 9 | Niveaux de service et exigences | des indicateurs et des objectifs réalistes ; des exigences de sécurité, de protection des données et d'accessibilité, avec leur origine | /3 |
| 10 | Soutenance | claire, dans le temps ; toute l'équipe parle ; des réponses argumentées, qui s'appuient sur le blueprint | /3 |
| | **Total** | | **/30** |

Les critères 1 à 5 relèvent de la compétence *Analyser les besoins et maquetter une application* ; les critères 6 à 9, de *Définir l'architecture logicielle d'une application* ; le critère 10 et le travail d'équipe, de *Contribuer à la gestion d'un projet informatique*.

**Points forts :** …

**À travailler :** …

---

## B.12 — Journal de conception

Un fichier Markdown dans le dépôt de l'équipe, ou un document partagé. Une entrée par jour, écrite par le ou la scribe et relue par l'équipe. C'est la matière première de votre dossier de projet.

```markdown
# Journal de conception — [service], équipe [nom]

## Jour 1 — [date]

### Décisions
- [décision] — parce que [raison]

### Hypothèses du brief confirmées ou infirmées
- [hypothèse] — [confirmée / infirmée] par [observation, commanditaire]

### Retours reçus à la restitution, et ce que nous en ferons
- [retour] — [ce que nous en faisons]

### Questions ouvertes
- [question]

## Jour 2 — [date]

### Ce que la marche à blanc a changé
- [trou trouvé] — [correction]

### Décisions de conception
- [décision] — parce que, dans le blueprint, [case ou rupture]

### Ce que le service ne fera pas
- [fonctionnalité demandée] — parce que [raison]
```

---

[← Chapitre précédent](A-Briefs-projets.md) · [Sommaire](Readme.md) · [Chapitre suivant →](C-Glossaire-et-ressources.md)
