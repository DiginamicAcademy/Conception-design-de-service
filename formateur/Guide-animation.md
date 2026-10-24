# Guide d'animation — formateur

Ce guide accompagne les deux jours du module **Conception et design de service**. Il complète le support : déroulé minuté, consignes d'animation, points de vigilance, ce que le commanditaire révèle de chaque brief, repères de correction. Il n'est pas repris dans le PDF.

> Ce dossier vit dans le dépôt public du cours : les apprenant·e·s peuvent le lire. Pour préserver l'effet des révélations du commanditaire, on peut le déplacer dans la partie pédagogique privée du cours.

## En bref

| | |
|---|---|
| Public | apprenant·e·s CDA |
| Effectif conseillé | 12 à 16 personnes, en 4 équipes de 3 ou 4 ; jusqu'à 5 équipes, voir *Adaptations* |
| Rythme | J1 : cours le matin (3 h 15), atelier l'après-midi (2 h 45) et restitution (45 min) ; J2 : cours le matin (1 h 30), atelier en fin de matinée et l'après-midi (3 h 35), soutenance et bilan (1 h 10) |
| Fil rouge | un brief par équipe, gardé jusqu'à la soutenance ([annexe A](../A-Briefs-projets.md)) ; les exemples du cours portent sur **Lucioles**, les exercices sur **la cantine** |
| Évaluation | formative le J1 ; soutenance évaluée le J2 ([grille B.11](../B-Modeles-et-canevas.md)) |

## Préparer

### Une semaine avant

- Envoyer aux apprenant·e·s le lien du dépôt, avec une consigne : lire le Readme.
- Vérifier que le réseau de la salle laisse passer Excalidraw, Miro ou FigJam, et GitHub pour le rendu des diagrammes Mermaid.

### La veille

| Matériel | Quantité |
|---|---|
| Post-its de cinq couleurs, format carré | un bloc de chaque couleur par équipe |
| Post-its rouges, pour la marche à blanc | un bloc par équipe |
| Feutres noirs pointe moyenne | un par personne |
| Grandes feuilles A1 ou A2, ou un mur par équipe | trois par équipe pour le J1, deux pour le J2 |
| Ruban adhésif de couleur, pour les lignes du blueprint | un rouleau par équipe |
| Gabarits imprimés en A3 : B.1 écosystème, B.3 parcours, B.4 blueprint | deux de chaque par équipe |
| Gabarits imprimés en A4 : B.6 marche à blanc, B.9 niveaux de service, B.10 retours | une liasse |
| Grilles d'évaluation B.11 | une par équipe |
| Fiches commanditaire de ce guide, imprimées | une par brief choisi |
| Quelques figurines ou pions, pour les marches à blanc | une poignée par équipe |
| Un minuteur projeté | — |

Disposer la salle en **îlots**, un par équipe, chacun près d'un mur ou d'un tableau.

### Composer les équipes

Composez les équipes **dès l'ouverture** du J1 : l'exercice 3 du matin se fait déjà en équipe, et sert d'échauffement à l'après-midi.

- Trois ou quatre personnes ; pas de binôme, pas d'équipe de cinq.
- Mélangez les niveaux d'aisance en UML et en prise de parole.
- Évitez de réunir des personnes qui travaillent déjà ensemble au quotidien : les retours croisés en seront plus francs.

## Principes d'animation

**Le cours, un cours qui fait travailler.** Jamais plus de vingt minutes d'exposé sans une question au groupe, un exemple à commenter ou un exercice. Projetez les diapositives, mais renvoyez au support pour le détail : il est écrit pour être relu.

**L'atelier, un coach, pas un professeur.** Passez dans chaque équipe toutes les quinze minutes environ. Posez des questions plutôt que de donner des réponses : « Qui fait ça ? », « Comment le sait-il ? », « Et si ça ne marche pas ? », « Où est-ce dans le blueprint ? ». Laissez les équipes se tromper sur ce qui n'est pas grave ; intervenez sur ce qui compromettrait la suite.

**Le temps est un matériau pédagogique.** Projetez le minuteur. Annoncez chaque fin d'étape cinq minutes avant. Une étape inachevée n'est pas grave ; une étape sautée l'est, parce que la suivante en dépend. Le J2 est serré : tenez les horaires à la minute.

**La restitution, une habitude.** Minutage strict, toujours le même format. Les équipes parlent d'abord, le groupe ensuite, le formateur en dernier. Terminez par **trois enseignements** de la séance, en deux minutes : ce que les équipes ont bien fait, ce qui a souvent coincé, ce qui servira ensuite.

## Jour 1

### Matin — Penser et cartographier un service

| Horaire | Séquence | Notes d'animation |
|---|---|---|
| 09:00 | Ouverture | Tour de table en une phrase : « Un service qui vous a fait perdre du temps, et à quel moment ? » Notez les réponses au tableau : presque toutes se situent en coulisses ou à un changement de canal. Vous y reviendrez à la partie 6. Puis présentez le module, Lucioles, la cantine et les briefs, et composez les équipes. |
| 09:20 | Parties 1 et 2 | Faites citer au groupe un service dont l'application est réussie et le service raté. Pour la partie 2.4, demandez à quelle échelle se situait le dernier bug qu'ils ont corrigé, ou subi. |
| 10:00 | Partie 3, exercice 1 | Exercice en binômes ; correction collective au tableau, cercle par cercle. Insistez sur la question 3 : celui qui fait un effort sans bénéfice. |
| 10:45 | Parties 4 et 5, exercice 2 | Avant de montrer les engagements de Lucioles, faites critiquer les trois « mauvais » engagements de la partie 4.3. L'exercice 2 se fait en binômes ; la question 3 a deux bonnes réponses : faites-les défendre l'une contre l'autre. |
| 11:30 | Partie 6, exercice 3 | Lisez le blueprint de Lucioles avec le groupe, dans les quatre sens de la partie 6.4. L'exercice 3 se fait en équipes ; corrigez la subtilité de la règle de gestion devant tout le groupe. |
| 12:25 | Clôture | Revenez au tour de table de l'ouverture : où se situaient les problèmes cités, sur un blueprint ? |

**Messages à faire passer :** l'application n'est qu'un point de contact ; les services cassent aux passages de relais ; un engagement est bon s'il tranche un débat ; un blueprint, un scénario.

### Après-midi — Cartographier le service

**Le choix des briefs.** Pas plus de deux équipes sur le même brief. Si le groupe hésite :

- **A.1 Premier jour** parle immédiatement à des alternant·e·s. Rappelez-leur que leur propre expérience est **une** observation, pas la vérité du service.
- **A.2 Ma rue en clair** est le plus « design de service public » : plusieurs organisations, une boucle de retour à concevoir.
- **A.3 VéloLongue** est le plus riche pour la partie technique du J2 : deux organisations, un contrat, un niveau de service à mesurer.
- **A.4 À table chez soi** est le plus exigeant : données de santé, sûreté, mode hors ligne, public vulnérable. Proposez-le à une équipe solide.

**Votre rôle de commanditaire.** Pendant les étapes 1 et 2, passez cinq minutes dans chaque équipe avec la fiche commanditaire de son brief (voir plus bas). Ne révélez que ce qu'on vous demande. Une équipe qui ne pose que des questions de solution — « Vous voulez une appli ou un site ? » — repart avec peu : c'est voulu, et vous en parlerez à la restitution. Défendez votre demande initiale avec conviction ; cédez quand on vous oppose une observation du brief.

**Points de vigilance.**

- À l'étape 3, le parcours actuel décrit déjà l'application : « Est-ce que cela existe aujourd'hui ? »
- L'écosystème ne contient que les futurs utilisateurs de l'application : « Qui fait le travail ? Qui paie ? Qui peut tout faire échouer ? »
- Les engagements sont des fonctionnalités : « Comment l'usager saura-t-il que c'est tenu ? »
- Les colonnes du blueprint sont des écrans, ou les coulisses disent « le système » : « Quel système ? Quelle donnée ? Qui déclenche ? »
- À 15:45, une équipe n'a pas commencé son blueprint : imposez-le, quitte à bâcler le parcours cible.

**À la restitution, cherchez :** une rupture étayée par un chiffre du brief ; une promesse qui s'écarte de la demande du commanditaire ; des coulisses où l'on reconnaît des personnes et des outils réels ; au moins une rupture avec une réponse prévue.

## Jour 2

### Cours — Du blueprint à l'application

| Horaire | Séquence | Notes d'animation |
|---|---|---|
| 09:00 | Rappel de la veille | Les cinq questions à main levée, puis deux minutes sur les retours marquants de la restitution. |
| 09:10 | Parties 1 et 2, exercice 1 | Projetez le schéma « Ce que le blueprint dit au concepteur » et faites compléter oralement la colonne Lucioles avant de la montrer. Exercice 1 à l'oral, collectivement. |
| 09:35 | Parties 3 et 4 | Débat éclair : « Monolithe ou microservices pour Lucioles ? » Laissez une minute aux défenseurs des microservices, puis faites chiffrer ce qu'ils coûtent. Construisez le diagramme d'états au tableau avec le groupe. |
| 09:55 | Partie 5 | Faites trouver les branches `alt` avant de les montrer : ce sont les ruptures F1 à F5 du blueprint. |
| 10:05 | Parties 6 et 7, exercice 2 | Insistez sur « jamais 100 % » et sur E3, mesuré par observation. Terminez par deux minutes de marche à blanc de Lucioles avec quatre volontaires — lecteur, libraire, tablette, logiciel de stock : c'est la démonstration de l'étape 7 de l'atelier. |

**Messages à faire passer :** le frontstage humain est un livrable ; on découpe par capacités ; les chemins d'erreur d'abord ; un engagement devient un niveau de service.

### Atelier — Concevoir et soutenir

L'atelier occupe la fin de matinée et tout l'après-midi. Il n'apporte aucune notion nouvelle : le temps sert à approfondir, à relier et à répéter.

| Horaire | Séquence | Notes d'animation |
|---|---|---|
| 10:45 | Lancement, étape 7 | Annoncez l'ordre de passage de la soutenance et la règle : chaque membre parle. Pendant la marche à blanc, jouez un système récalcitrant. |
| 11:25 | Étape 8 | Passez d'abord voir les binômes B : le diagramme de classes dérive vite vers un schéma de base de données exhaustif. |
| 13:30 | Mise en commun | Imposez-la : sans vocabulaire commun, la séquence et la matrice ne tiendront pas. |
| 13:40 | Étape 9 | Vérifiez que chaque branche `alt` renvoie à une rupture F du blueprint. |
| 14:30 | Étape 10 | La matrice de traçabilité révèle les trous : c'est voulu. Faites combler les plus graves, noter les autres. |
| 15:20 | Préparation | Exigez la répétition complète, chronomètre en main : elle évite les soutenances qui débordent. |
| 15:50 | Soutenance et bilan | Huit minutes, quatre de questions, puis dix minutes de bilan. |

**Les binômes.** Si l'équipe hésite, composez-les vous-même : la personne la plus à l'aise en UML dans le binôme A.

**La marche à blanc.** Passez dans chaque équipe pendant l'étape 7 et jouez vous-même un système récalcitrant : « Je suis l'API de la GMAO, je ne réponds pas. » L'effet est immédiat.

**Points de vigilance.**

- Des cas d'utilisation qui sont des écrans, ou des modules qui sont des acteurs.
- Des microservices par réflexe.
- Un diagramme d'états sans états finaux, ou des états que l'usager ne comprendrait pas.
- Des objectifs à 100 %.
- Une matrice de traçabilité remplie après coup, pour faire joli : demandez à l'équipe de lire une ligne de bout en bout, à voix haute.

**La soutenance.** Huit minutes de présentation, quatre de questions, chronomètre visible. Notez avec la grille B.11 pendant la présentation, et posez au moins une question parmi celles du support. Le groupe remplit une grille de retours B.10 par équipe. Remettez grilles et retours à la fin.

**Le bilan.** Dix minutes : le tour de table, puis le questionnaire d'évaluation de la formation. Rappelez que tous les livrables — écosystème, blueprint, cas d'utilisation, séquence, niveaux de service, journal — servent au dossier de projet.

## Les fiches commanditaire

À imprimer, une par brief choisi. Le commanditaire ne révèle ces informations **que si une question y mène**. Il défend sa demande initiale, et ne cède que devant une observation du brief.

### A.1 — Nadia, Campus de l'Estuaire

- **Sa vraie inquiétude :** les neuf ruptures de contrat dans les quarante-cinq jours, et l'audit Qualiopi du printemps. L'an dernier, l'auditeur a relevé que l'accueil des alternant·e·s n'était pas tracé.
- **Pourquoi les comptes arrivent si tard :** le service informatique ne crée de comptes que pour les contrats complets, parce que l'année précédente, il avait créé — et payé — des licences pour des personnes qui ne sont jamais venues.
- **Les entreprises :** les maîtres d'apprentissage ne reçoivent rien du Campus avant la visite du référent, à deux mois. Plusieurs ont dit qu'« un e-mail par mois, pas une application » leur suffirait.
- **Le chatbot** vient d'un salon professionnel. Elle se contenterait d'une foire aux questions tenue à jour et d'un·e interlocuteur·rice nommé·e.
- **Le référent handicap** du Campus n'apprend qu'à la rentrée les besoins d'aménagement des alternant·e·s : quatre étaient concerné·e·s en septembre.

### A.2 — Karim, adjoint à la proximité

- **La carte publique a déjà été essayée**, en 2021 : elle affichait l'adresse des dépôts sauvages, des voisins se sont accusés mutuellement, et la carte a été retirée.
- **Les élu·e·s** reçoivent des signalements par SMS sur leur téléphone personnel. Ils les transfèrent… ou les oublient.
- **Ce qu'il veut vraiment mesurer :** le délai de **réponse** à l'habitant, pas le délai d'intervention. « Je ne peux pas boucher tous les trous en deux jours. Mais je peux dire aux gens ce qu'on fait. »
- **La métropole** publie en données ouvertes la carte des voies et de leur gestionnaire : on pourrait orienter les signalements automatiquement.
- **L'API de la GMAO** coûte 4 000 € par an : le budget le permet, si l'on renonce à une application mobile publiée sur les magasins.

### A.3 — Laure, agglomération

- **Le marché sera renégocié l'an prochain.** Sa priorité : pouvoir mesurer le délai de prise en charge des pannes, puisque c'est sur lui que portent les pénalités.
- **L'exploitant a une API**, mais ne l'ouvrira que si le prochain marché l'y oblige. D'ici là : l'export hebdomadaire.
- **La liste d'attente :** beaucoup d'inscrit·e·s accepteraient un vélo d'occasion ou un contrat plus court. Environ un sur cinq a déjà trouvé une autre solution, sans prévenir.
- **La géolocalisation :** l'assureur de la flotte ne l'exige pas. Une géolocalisation activée seulement après déclaration de vol lui suffirait. Suivre en permanence les déplacements des abonné·e·s serait de toute façon difficile à justifier : en 2022, la CNIL a sanctionné de 175 000 € un loueur de véhicules qui géolocalisait ses clients presque en continu.
- **L'atelier :** les mécaniciens ne savent pas à l'avance de quelle panne il s'agit. Une photo et un symptôme leur permettraient de commander la pièce avant le rendez-vous.

### A.4 — Sylvie, CCAS

- **La cuisine centrale** a besoin des quantités définitives le mercredi midi pour la semaine suivante, et la veille avant 9 h pour le lendemain.
- **Les régimes :** l'incident du dessert vient des abréviations. La diététicienne réclame depuis longtemps une liste fermée de régimes, sans saisie libre.
- **Les proches :** la plupart accepteraient un SMS. Certain·e·s bénéficiaires ont plusieurs proches, d'autres aucun.
- **L'incident de l'an dernier :** une bénéficiaire a été retrouvée deux heures après le passage du livreur, après une chute ; le numéro de son proche n'était plus le bon. Tenir les contacts à jour est vital.
- **Les smartphones des livreurs** ont été achetés l'an dernier, mais personne ne leur a donné d'outil. Ils sont prêts à s'en servir « si ça marche dans les hameaux ».

## Repères de correction par brief

Les briefs n'ont pas de « bonne réponse ». Ces repères disent ce que le brief et la fiche commanditaire permettent de découvrir, et ce qu'une équipe solide devrait en faire.

### A.1 — Premier jour

| Étape | Ce qu'on attend |
|---|---|
| Ruptures du parcours actuel | la création des comptes bloquée par la règle du « contrat complet » ; le tableur transmis à la main le jeudi soir ; l'emploi du temps envoyé à une adresse inaccessible ; l'entreprise et le maître d'apprentissage hors de la boucle |
| Promesse plausible | « Pour les nouveaux alternant·e·s et leurs maîtres d'apprentissage, le Campus garantit que tout est prêt le premier jour — identifiants, badge, calendrier — et qu'ils savent à qui s'adresser, là où aujourd'hui un·e sur cinq attend son mot de passe dans un couloir. » |
| Engagements | « Vos identifiants vous attendent deux jours avant la rentrée » ; « Votre maître d'apprentissage connaît votre calendrier avant votre premier jour en entreprise » ; « Une seule personne à contacter, nommée » ; pour le personnel : « Le service informatique ne ressaisit jamais une liste » |
| Moments de vérité | le premier matin ; le premier jour en entreprise ; la première difficulté |
| Coulisses clés du blueprint | création des comptes dès « admis et entreprise trouvée », désactivation sans contrat à J + 15 ; envoi automatique du calendrier au maître d'apprentissage ; information du référent handicap |
| Modules plausibles | Dossiers d'alternance ; Comptes, avec un adaptateur vers l'annuaire ; Calendriers, à partir du flux iCal ; Communication avec les entreprises ; Pilotage ; adaptateur vers l'outil de candidatures |
| Objet central | le **dossier d'alternance** : admis → entreprise trouvée → contrat signé → financement accordé → intégré → terminé, ou rompu |
| Niveaux de service | 98 % des alternant·e·s ont des identifiants actifs à J − 2 ; 95 % des maîtres d'apprentissage reçoivent le calendrier à J − 7. Les ruptures dans les 45 jours sont un **indicateur de pilotage**, pas un niveau de service du système. |
| Exigences | données de mineur·e·s ; un maître d'apprentissage ne voit que son alternant·e ; accessibilité ; dépendance à l'éditeur de l'outil de candidatures |
| *Won't* attendus | le chatbot, l'application mobile, le tableau de bord en temps réel — un rapport hebdomadaire suffit |
| Piège principal | concevoir pour les alternant·e·s en oubliant les entreprises, alors que la rupture est dans le passage de relais entre l'administration et l'informatique |

### A.2 — Ma rue en clair

| Étape | Ce qu'on attend |
|---|---|
| Ruptures du parcours actuel | doublons ; signalements hors compétence mal orientés ; aucun retour à l'habitant ; photos perdues ; relances qui arrivent chez les élu·e·s |
| Promesse plausible | « Pour les habitant·e·s qui signalent un problème, la ville garantit que chaque signalement est reçu, confié au bon gestionnaire et suivi jusqu'à sa résolution, avec des nouvelles à chaque étape, quel que soit le canal — là où aujourd'hui la plupart des messages restent sans réponse. » |
| Engagements | « Un accusé de réception dans la journée » ; « Si ce n'est pas à nous, nous vous disons à qui nous l'avons transmis » ; « Vous êtes prévenu·e quand c'est réglé » ; pour le personnel : « L'agent d'accueil n'a jamais à deviner qui est compétent » |
| Moments de vérité | l'accusé de réception ; le « ce n'est pas à nous », qui ne doit pas sonner comme un abandon ; la clôture, photo à l'appui |
| Coulisses clés du blueprint | qualification par l'accueil ; orientation par les données de la métropole ; rattachement des doublons au signalement existant, en prévenant aussi le nouvel auteur ; création de l'intervention dans la GMAO ; retour de clôture depuis la GMAO |
| Modules plausibles | Signalements, avec la détection des doublons ; Orientation, avec les règles de compétence ; Interventions, avec un adaptateur vers la GMAO ; Information des habitants ; Pilotage |
| Objet central | le **signalement** : reçu → qualifié → orienté en interne, transmis à un partenaire, rattaché à un doublon ou rejeté → planifié → résolu → clos, auteur informé |
| Niveaux de service | 95 % des signalements accusés en moins d'un jour ouvré ; 90 % qualifiés et orientés en moins de deux jours ouvrés ; 95 % des résolutions notifiées à l'auteur dans la journée |
| Exigences | RGAA ; photos non publiées, ou floutées, et conservées pour une durée limitée ; coordonnées de l'auteur invisibles des autres habitants ; signalements téléphoniques saisis dans le même outil |
| *Won't* attendus | la carte publique, le classement des quartiers, le tri des photos par IA, les tablettes des agents — des bons d'intervention imprimés depuis la GMAO suffisent pour commencer |
| Piège principal | la carte publique — vie privée, conflits de voisinage —, et oublier l'agent d'accueil et les autres collectivités |

### A.3 — VéloLongue

| Étape | Ce qu'on attend |
|---|---|
| Ruptures du parcours actuel | liste d'attente opaque ; rendez-vous imposés et non honorés ; dossiers incomplets ; pannes non tracées côté agglomération ; un vol qui continue d'être facturé |
| Promesse plausible | « Pour les habitant·e·s qui veulent passer au vélo électrique, VéloLongue dit à chacun où il en est et quand son vélo sera prêt, puis le garde en état de rouler — là où l'on attend aujourd'hui quatre mois sans nouvelles et neuf jours pour une réparation. » |
| Engagements | « Vous connaissez votre position sur la liste d'attente » ; « Vous choisissez votre créneau de remise » ; « Une panne est prise en charge en moins de cinq jours ouvrés » ; « Un vol déclaré suspend le prélèvement » ; pour le personnel : « L'agent instructeur ne reçoit plus de justificatifs par e-mail » |
| Moments de vérité | la convocation à la remise ; la panne ; le vol |
| Coulisses clés du blueprint | confirmation périodique de l'intérêt des inscrit·e·s ; créneaux de remise en ligne ; dépôt des justificatifs dans un espace sécurisé ; ticket de panne horodaté visible de l'agglomération ; suspension du prélèvement transmise à la régie |
| Modules plausibles | Inscriptions et liste d'attente ; Instruction des justificatifs ; Rendez-vous ; Abonnements, avec un adaptateur vers la régie ; Incidents, pannes et vols, avec un adaptateur vers l'outil de l'exploitant ; Pilotage du contrat |
| Objet central | l'**abonnement** : inscrit → en attente → convoqué → actif → suspendu après un vol → actif ou clos. Un second cycle de vie compte : le **ticket de panne**, déclaré → pris en charge → réparé → clos, c'est lui qui porte le niveau de service. |
| Niveaux de service | la bonne distinction : le marché fixe un **SLA** — cinq jours ouvrés, des pénalités — ; l'agglomération se fixe des **SLO** : 95 % des pannes prises en charge en cinq jours ouvrés, 90 % des rendez-vous de remise honorés |
| Exigences | propriété et réversibilité des données, en cas de changement d'exploitant ; justificatifs à accès restreint et à durée de conservation limitée ; géolocalisation seulement après un vol ; RGAA |
| *Won't* attendus | la géolocalisation permanente, le programme de fidélité aux kilomètres, la réservation en temps réel façon libre-service |
| Piège principal | copier le modèle du vélo en libre-service, et oublier que l'exploitant est une organisation distincte, qui détient les données des pannes |

### A.4 — À table chez soi

| Étape | Ce qu'on attend |
|---|---|
| Ruptures du parcours actuel | saisie manuelle des menus ; régimes ambigus ; absences non signalées ; protocole « personne ne répond » trop lent ; familles sans nouvelles |
| Promesse plausible | « Pour les personnes fragiles qui vivent chez elles, et pour leurs proches, le CCAS garantit chaque jour le bon repas et une visite attentive, et prévient aussitôt quand quelque chose ne va pas — sans demander aux bénéficiaires de se servir d'un écran. » |
| Engagements | « Votre régime est toujours respecté » ; « Votre proche est prévenu dans le quart d'heure qui suit le passage » ; « Si personne ne répond, un proche est joint en moins de quinze minutes » ; « Un seul appel suffit pour signaler une absence » ; pour le personnel : « La secrétaire ne ressaisit plus les menus » |
| Moments de vérité | le passage du livreur ; le protocole « personne ne répond » ; le repas conforme au régime |
| Coulisses clés du blueprint | liste de tournée consultable hors ligne, avec des régimes codifiés ; statut de passage saisi par le livreur ; déclenchement du protocole avec des contacts à jour ; transmission des quantités à la cuisine avant le mercredi midi ; absences saisies par la secrétaire |
| Modules plausibles | Bénéficiaires et régimes, avec une liste fermée ; Menus et commandes ; Production, avec un export vers la cuisine ; Tournées, hors ligne ; Alertes et protocole ; Information des proches ; Facturation, avec un adaptateur vers le logiciel financier |
| Objet central | la **livraison du jour** : prévue → en tournée → livrée, absence constatée, ou personne ne répond → protocole en cours → résolu, avec son issue |
| Niveaux de service | 95 % des proches prévenus dans les quinze minutes ; 95 % des protocoles avec un proche joint en moins de quinze minutes. Le respect du régime n'est **pas** un SLO : c'est une exigence de sûreté — liste fermée, double contrôle à la préparation —, et chaque protocole est tracé jusqu'à son issue. |
| Exigences | données de santé : accès restreint, journalisation des accès, hébergement certifié si nécessaire ; mode hors ligne ; téléphone et papier maintenus ; aucune surveillance continue des agents |
| *Won't* attendus | les tablettes pour les bénéficiaires, les capteurs dans les réfrigérateurs, le suivi GPS du livreur en temps réel |
| Piège principal | concevoir pour les bénéficiaires une interface qu'ils n'utiliseront pas, et traiter le régime comme une préférence alors que c'est une question de santé |

## Adaptations

### Selon l'effectif

- **Deux équipes :** restitution en 8 + 5 minutes ; soutenance en 12 + 6 minutes. Jouez vous-même des rôles supplémentaires pendant les marches à blanc.
- **Cinq équipes :** restitution en 4 + 2 minutes ; soutenance en 8 + 3 minutes, bilan de cinq minutes.

### Selon le public

- **Un groupe qui a déjà suivi un module d'UX** : passez vite sur la partie 5.1 du J1 et sur le canevas de proposition de valeur ; consacrez le temps gagné au blueprint.
- **Un groupe peu à l'aise en UML** : au J2, autorisez des diagrammes à la main, et faites dessiner au tableau, avec le groupe, le diagramme d'états de Lucioles avant de lancer l'atelier.

### À distance

- Tableaux blancs partagés — Excalidraw, Miro ou FigJam — à la place des murs ; une salle de sous-groupe par équipe.
- Le commanditaire passe de salle en salle.
- La marche à blanc se fait en partage d'écran, chaque rôle caméra allumée.
- Restitutions et soutenances en partage d'écran ; minuteur visible dans la visioconférence.

### En cas de retard

Ce qui peut se raccourcir sans casser la suite, par ordre de préférence :

| Moment | À raccourcir | À préserver absolument |
|---|---|---|
| J1, cours | partie 1.2, partie 2.1 ; exercice 2 corrigé collectivement | la partie 6 et l'exercice 3 |
| J1, atelier | le détail du parcours actuel, le canevas de valeur | l'écosystème avec ses systèmes existants, les engagements, le blueprint |
| J2, cours | parties 3.3 et 7, en démonstration seulement | parties 1, 4.2 et 6.2 |
| J2, atelier | le plan de pilote ; le diagramme de classes, réduit à l'objet central ; la répétition | la marche à blanc, la séquence d'un moment de vérité, la soutenance |

## Après la formation

- Récupérez les grilles B.11 remplies : elles alimentent le suivi des apprenant·e·s.
- Gardez les photos des murs : ce sont d'excellents exemples, anonymisés, pour les sessions suivantes.
- Notez dans ce guide ce qui a fonctionné ou non : durée des étapes, briefs les plus et les moins choisis, questions du commanditaire qui ont le mieux marché.
- Si le module est suivi d'un projet de développement, les livrables de l'équipe — blueprint, cas d'utilisation, modules, niveaux de service — en font un excellent cahier des charges.
