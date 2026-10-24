[← Chapitre précédent](04-J2-Atelier-Concevoir-et-soutenir.md) · [Sommaire](Readme.md) · [Chapitre suivant →](B-Modeles-et-canevas.md)

# Annexe A — Briefs projets

Quatre services pour le fil rouge. Chaque équipe en choisit un le premier jour et le garde jusqu'à la soutenance.

## Comment lire un brief

Un brief est écrit par un **commanditaire** : il dit ce qu'il croit savoir de son service et ce qu'il croit vouloir. C'est un point de départ, pas un cahier des charges.

- Ce que le commanditaire affirme est une **hypothèse**, à confronter aux observations.
- Ce qu'il demande est une **solution**. Votre travail est de retrouver le **problème** qu'elle est censée résoudre.
- La section « Ce qu'on a observé » est votre matière première : ce sont des faits, relevés sur le terrain. C'est d'elle que vous tirerez le parcours actuel et ses ruptures.
- La section « Le système d'information existant » est votre contrainte principale de conception : on ne conçoit jamais sur une page blanche.
- Les briefs contiennent, comme dans la vraie vie, des **contradictions** et des **demandes déraisonnables**. Les repérer fait partie du travail.

Le formateur joue le commanditaire. Chaque équipe dispose d'un entretien de cinq minutes avec lui, le premier jour : préparez vos questions.

## Ce que le commanditaire attend de vous

| Jour | Ce que vous lui remettez |
|---|---|
| 1 | l'écosystème du service, le parcours actuel et ses ruptures, la promesse et ses engagements, le parcours cible, le blueprint |
| 2 | les cas d'utilisation, les modules, le domaine, la séquence d'un moment de vérité, les niveaux de service, et la présentation de votre démarche |

Il ne vous demande **pas** de développer : ce sera, peut-être, le projet suivant.

## Les quatre briefs en un coup d'œil

| Brief | Commanditaire | Usagers et acteurs pressentis | Ce qui le rend intéressant |
|---|---|---|---|
| A.1 Premier jour | un centre de formation | alternant·e·s, entreprises, services internes | des passages de relais entre services, et une partie prenante oubliée |
| A.2 Ma rue en clair | une ville | habitant·e·s, agents, élu·e·s, autres collectivités | plusieurs organisations, et une boucle de retour absente |
| A.3 VéloLongue | une agglomération et son exploitant | habitant·e·s, exploitant, régie | deux organisations, un contrat, un niveau de service que personne ne mesure |
| A.4 À table chez soi | un centre communal d'action sociale | bénéficiaires, proches, livreurs, cuisine | un public vulnérable, des données de santé, un moment de vérité vital |

---

## A.1 — « Premier jour » : l'intégration des alternant·e·s

**Commanditaire :** Nadia, directrice des opérations du Campus de l'Estuaire, centre de formation aux métiers du numérique.
**En une phrase :** que chaque alternant·e soit attendu·e, équipé·e et accompagné·e dès son premier jour, au centre comme en entreprise.

### Le contexte

Le Campus forme 650 alternant·e·s dans quatorze formations — développement, réseaux, design —, avec trois rentrées par an : septembre, janvier et avril. Environ un·e alternant·e sur dix est mineur·e.

Pour devenir alternant·e, il faut passer par une longue suite d'étapes : candidature en ligne, test et entretien, admission « sous réserve de trouver une entreprise », recherche d'entreprise — accompagnée par trois chargées de relations entreprises —, signature du contrat d'apprentissage par l'entreprise et l'alternant·e, convention de formation entre le Campus et l'entreprise, transmission du contrat par l'entreprise à son opérateur de compétences (OPCO), qui finance la formation.

Vient ensuite l'intégration : comptes informatiques (messagerie, plateforme pédagogique, wifi), badge d'accès, emploi du temps, livret d'apprentissage, désignation d'un·e maître d'apprentissage dans l'entreprise, réunion de rentrée. Un·e formateur·rice référent·e suit chaque alternant·e et rend visite à l'entreprise au cours des deux premiers mois.

### Ce que dit le commanditaire

> « Il nous faut une application mobile pour les alternants, avec un chatbot d'intelligence artificielle qui réponde à toutes leurs questions, vingt-quatre heures sur vingt-quatre. Et un tableau de bord en temps réel pour la direction. Il faudrait qu'elle soit branchée sur tous nos outils. Les entreprises, elles, n'ont pas le temps : on ne va rien leur demander de plus. Et il faut que ce soit prêt pour la rentrée de janvier. »

### Ce qu'on a observé

À la dernière rentrée de septembre, 212 nouveaux alternant·e·s étaient attendu·e·s.

| Quand | Ce qui s'est passé |
|---|---|
| J − 7 | 168 contrats signés sur 212 (79 %). Pour obtenir une signature ou une pièce manquante, les chargées de relations entreprises passent en moyenne quatre appels par contrat. |
| J − 3, jeudi soir | L'administration envoie au service informatique un tableur des alternant·e·s « au contrat complet ». Les comptes sont créés le vendredi. |
| J, 9 h | 41 alternant·e·s sur 212 (19 %) n'ont pas d'identifiants. File d'attente d'une heure dix devant le bureau du service informatique. Trente badges provisoires en papier. |
| J | L'emploi du temps est envoyé par e-mail… à l'adresse du Campus, que les nouveaux n'ont pas encore. |
| J + 15 | Une enquête auprès des maîtres d'apprentissage : 38 % ne connaissent pas le calendrier d'alternance. |
| J + 45 | Neuf contrats rompus pendant la période où chaque partie peut y mettre fin librement : les quarante-cinq premiers jours de formation pratique en entreprise. |

### Quelques verbatims

> — une alternante : « Le premier jour, j'ai passé la matinée dans le couloir à attendre mon mot de passe. »
>
> — un maître d'apprentissage : « Je ne savais même pas quels jours il était censé être chez nous. »
>
> — un technicien du service informatique : « On reçoit le tableur le jeudi soir, avec des noms mal orthographiés et des formations qui n'existent plus. »

### Les acteurs pressentis

Les alternant·e·s ; les maîtres d'apprentissage ; les chargées de relations entreprises ; le service administratif ; le service informatique ; les formateur·rice·s référent·e·s ; la direction.

### Le système d'information existant

| Système | Propriétaire | Ce qu'il sait | Comment on lui parle |
|---|---|---|---|
| Outil de gestion des candidatures | éditeur, sous abonnement | candidatures, admissions | export CSV ; API en option payante |
| Tableur des contrats | service administratif | contrats, conventions, statut du financement | fichier partagé |
| Annuaire des comptes | service informatique | comptes, messagerie, wifi | scripts internes, à partir d'un fichier |
| Plateforme pédagogique | service informatique | cours, livrets d'apprentissage | API ; comptes issus de l'annuaire |
| Logiciel d'emploi du temps | pôle pédagogique | calendriers d'alternance, plannings | flux d'agenda (iCal) |

### Les contraintes

- Deux développeurs en interne, pendant six mois.
- Des données personnelles d'alternant·e·s, dont certain·e·s sont mineur·e·s.
- Le Campus est certifié Qualiopi : l'accueil, l'accompagnement et le suivi des alternant·e·s font partie de ce qui est audité.
- Les entreprises sont des clientes : on ne peut pas leur imposer un outil.

---

## A.2 — « Ma rue en clair » : signaler un problème dans l'espace public

**Commanditaire :** Karim, adjoint au maire chargé de la proximité, dans une ville de 48 000 habitants membre d'une métropole.
**En une phrase :** que chaque signalement d'un habitant arrive au bon service, soit traité, et que l'habitant le sache.

### Le contexte

La ville reçoit 4 200 signalements par an : voirie (nids-de-poule, trottoirs), éclairage public, propreté (dépôts sauvages, tags), espaces verts, mobilier urbain. Ils arrivent par téléphone à l'accueil de la mairie (45 %), par e-mail (25 %), par le formulaire du site de la ville (15 %), par les réseaux sociaux (10 %), ou directement auprès d'un·e élu·e (5 %).

L'accueil saisit chaque signalement dans un tableur partagé et le transmet par e-mail au service concerné. Les services techniques — soixante agents — planifient leurs interventions dans un logiciel de gestion de maintenance assistée par ordinateur (GMAO).

Tout ne relève pas de la commune : les grands axes sont gérés par la métropole, les routes départementales par le département, les abords des résidences par des bailleurs sociaux.

### Ce que dit le commanditaire

> « Je veux une application comme dans les grandes villes : une carte publique de tous les signalements en temps réel, un classement des quartiers les plus propres, et une intelligence artificielle qui trie les photos automatiquement. Nos agents de terrain clôtureront leurs interventions sur tablette. Les habitants doivent voir que la mairie agit ! »

### Ce qu'on a observé

Sur l'année écoulée :

- **31 %** des signalements sont des doublons : jusqu'à sept pour un même nid-de-poule.
- **27 %** concernent un équipement qui ne relève pas de la commune. Ils sont transférés par e-mail… quand l'agent d'accueil sait à qui.
- Délai médian entre le signalement et l'intervention : **12 jours** pour la voirie, **3 jours** pour la propreté.
- **Aucun retour** n'est fait systématiquement à l'habitant. 18 % des signalements sont relancés par leur auteur, et une relance sur quatre arrive directement chez un·e élu·e.
- Les agents de terrain reçoivent chaque matin des bons d'intervention imprimés. Ils ont un téléphone professionnel simple ; la GMAO n'est utilisée qu'au bureau.
- Les photos jointes aux e-mails ne sont pas reportées dans la GMAO.

### Quelques verbatims

> — une habitante : « J'ai signalé le lampadaire trois fois. Je ne sais même pas si quelqu'un a lu mes messages. »
>
> — un agent d'accueil : « Pour savoir si c'est à nous ou à la métropole, je demande à mon collègue. Quand il est en congé, je devine. »
>
> — un chef d'équipe de la voirie : « On bouche le trou, mais personne ne dit à la dame que c'est fait. »

### Les acteurs pressentis

Les habitant·e·s ; les agents d'accueil ; les élu·e·s ; le bureau des services techniques ; les agents de terrain ; la métropole, le département, les bailleurs sociaux.

### Le système d'information existant

| Système | Propriétaire | Ce qu'il sait | Comment on lui parle |
|---|---|---|---|
| Tableur des signalements | accueil | signalements, service destinataire | fichier partagé |
| GMAO | services techniques | interventions, équipes, matériels | API proposée par l'éditeur, en option payante |
| Système d'information géographique | métropole | les voies et leur gestionnaire | données ouvertes, mises à jour chaque mois |
| Site de la ville | service communication | formulaire de contact | outil de gestion de contenu |
| Messagerie, téléphone, réseaux sociaux | divers | — | — |

### Les contraintes

- Un service public : l'accessibilité selon le RGAA est obligatoire.
- Le conseil municipal a voté que « le numérique ne doit pas devenir le seul guichet » : le téléphone et l'accueil physique restent.
- Les photos peuvent montrer des visages, des plaques d'immatriculation, des façades reconnaissables.
- Un budget limité : pas de développement d'application mobile à publier sur les magasins d'applications.

---

## A.3 — « VéloLongue » : la location longue durée de vélos électriques

**Commanditaire :** Laure, chargée de mission mobilité d'une communauté d'agglomération de 180 000 habitants.
**En une phrase :** mettre plus d'habitant·e·s en selle, plus vite, et les garder roulant·e·s.

### Le contexte

L'agglomération propose 1 200 vélos à assistance électrique en location de six à douze mois : 40 € par mois, 20 € pour les étudiant·e·s et les demandeur·se·s d'emploi, entretien compris. Le service est exploité, dans le cadre d'un marché public, par une entreprise, **La Roue Libre**, qui tient la Maison du vélo : accueil, remise des vélos, atelier de réparation.

Le parcours d'aujourd'hui : inscription sur un formulaire du site de l'agglomération ; justificatifs — domicile, et pour le tarif réduit, statut — envoyés par e-mail à l'agglomération, qui instruit les dossiers ; inscription sur une liste d'attente ; quand un vélo se libère, appel de la Maison du vélo pour fixer un rendez-vous ; remise du vélo avec contrat, prise en main de trente minutes et dépôt de garantie de 150 € ; prélèvement mensuel par la régie de l'agglomération. Pour une panne, on téléphone à la Maison du vélo pour obtenir un rendez-vous à l'atelier. Pour un vol, on porte plainte, puis on remplit une déclaration papier à la Maison du vélo.

### Ce que dit le commanditaire

> « Je veux une application comme celles des vélos en libre-service : réservation en temps réel, géolocalisation antivol de tous les vélos, et un programme de fidélité avec des points pour les kilomètres parcourus. Et que les gens arrêtent d'appeler l'exploitant pour tout et n'importe quoi. »

### Ce qu'on a observé

- **900 personnes** en liste d'attente ; attente moyenne : **quatre mois**, sans aucune information sur sa position.
- **22 %** des rendez-vous de remise ne sont pas honorés.
- **Un dossier sur trois** arrive incomplet ; trois allers-retours d'e-mails en moyenne.
- **60 %** des appels reçus par la Maison du vélo portent sur une seule question : « Où en est mon dossier ? »
- Panne : délai médian entre l'appel et la réparation, **9 jours**. Le marché prévoit des pénalités au-delà de **5 jours ouvrés**… que l'agglomération n'a aucun moyen de mesurer.
- **35 vols** par an. La procédure dure en moyenne trois semaines, pendant lesquelles l'abonné·e continue d'être prélevé·e.

### Quelques verbatims

> — une inscrite : « Quatre mois sans nouvelles, puis un appel un mardi à 10 h pour un rendez-vous le jeudi. Je travaille, moi. »
>
> — un mécanicien : « Les gens arrivent sans rendez-vous avec un pneu crevé ; d'autres prennent rendez-vous pour une batterie qu'on n'a pas en stock. »
>
> — un agent instructeur de l'agglomération : « Je reçois cinquante justificatifs par semaine dans ma boîte mail. »

### Les acteurs pressentis

Les habitant·e·s inscrit·e·s puis abonné·e·s ; l'agent instructeur de l'agglomération ; les conseiller·e·s et les mécanicien·ne·s de la Maison du vélo ; la régie de recettes ; l'assureur de la flotte.

### Le système d'information existant

| Système | Propriétaire | Ce qu'il sait | Comment on lui parle |
|---|---|---|---|
| Formulaire d'inscription | agglomération | demandes | notification par e-mail |
| Boîte e-mail de l'instruction | agglomération | justificatifs | — |
| Logiciel de facturation de la régie | agglomération | contrats, prélèvements | import de fichier |
| Outil de gestion de flotte | La Roue Libre | vélos, pannes, réparations | export CSV hebdomadaire ; une API existe, non ouverte |
| Agenda de l'atelier | La Roue Libre | rendez-vous | agenda partagé |

### Les contraintes

- Deux organisations : l'agglomération est responsable du service, l'exploitant le fait fonctionner. Le marché arrive à échéance dans trois ans, et l'exploitant pourrait changer.
- Les justificatifs de ressources sont des données personnelles à protéger.
- L'agglomération est soumise au RGAA.

---

## A.4 — « À table chez soi » : le portage de repas à domicile

**Commanditaire :** Sylvie, directrice du centre communal d'action sociale (CCAS) d'une ville de 30 000 habitants.
**En une phrase :** que chaque bénéficiaire reçoive le bon repas, chaque jour, et que quelqu'un s'assure qu'il va bien.

### Le contexte

Le CCAS livre 180 bénéficiaires : des personnes âgées, des personnes en situation de handicap, des personnes qui sortent d'hospitalisation. Les repas sont préparés par la cuisine centrale de la ville, qui assure aussi la restauration scolaire, et livrés en liaison froide du lundi au vendredi — le vendredi, avec ceux du week-end — par trois agents livreurs, chacun avec une tournée de soixante bénéficiaires.

Chaque plat est proposé en deux choix. Les régimes sont nombreux : sans sel, diabétique, texture mixée, sans porc… Les menus de la semaine suivante sont distribués sur papier le lundi ; les choix sont récupérés par les livreurs le jeudi, ou par téléphone ; la secrétaire du CCAS les saisit dans le tableur de la cuisine.

La livraison est aussi un **passage** : le livreur s'assure que la personne va bien. Si personne ne répond, un protocole s'applique : appeler la personne, puis son proche référent, puis un voisin, puis les secours. La facturation est mensuelle, à un tarif qui dépend des ressources.

### Ce que dit le commanditaire

> « Il faut que nos bénéficiaires commandent sur une tablette que nous leur prêterions, avec des capteurs dans le réfrigérateur pour savoir s'ils ont mangé, et que les familles suivent la position du livreur en temps réel. Et qu'on n'ait plus de papier. »

### Ce qu'on a observé

Sur les trois derniers mois :

- La secrétaire passe **deux jours par semaine** à saisir les menus et à appeler les bénéficiaires.
- **Six erreurs de régime**, dont un dessert sucré livré à un bénéficiaire diabétique.
- **9 %** des repas préparés ne sont pas consommés : hospitalisation non signalée, séjour chez un proche…
- L'information « hospitalisé·e » arrive par le livreur, qui trouve porte close, ou par la famille au téléphone, souvent plusieurs jours après.
- Le protocole « personne ne répond » se déclenche **une à deux fois par mois**. Il faut en moyenne **25 minutes** pour joindre un proche, et la tournée prend du retard.
- Les familles appellent le CCAS pour savoir « si maman a bien été livrée » : une quinzaine d'appels par semaine.
- 70 % des bénéficiaires ont plus de 80 ans ; un sur quatre se sert d'un téléphone portable.

### Quelques verbatims

> — un livreur : « Ma tournée, c'est une feuille A3 avec des flèches. Quand quelqu'un est hospitalisé, je le barre au stylo. »
>
> — la fille d'une bénéficiaire : « Je vis à 300 km. Un simple message, "votre mère a été livrée à 10 h 40", ça me changerait la vie. »
>
> — la diététicienne : « Les régimes sont notés en abrégé. "S/S", c'est sans sel ; mais certains lisent sans sucre. »

### Les acteurs pressentis

Les bénéficiaires ; leurs proches aidants ; les agents livreurs ; la secrétaire du CCAS ; la cuisine centrale ; la diététicienne ; les travailleur·se·s sociaux, qui évaluent les demandes ; la comptabilité.

### Le système d'information existant

| Système | Propriétaire | Ce qu'il sait | Comment on lui parle |
|---|---|---|---|
| Tableur des commandes | cuisine centrale | choix de menus, régimes, quantités | fichier partagé |
| Logiciel de l'action sociale | CCAS | dossiers des bénéficiaires, aides, contacts | export de fichiers |
| Logiciel financier de la ville | service des finances | facturation | import de fichier |
| Téléphones des livreurs | CCAS | smartphones depuis l'an dernier, utilisés pour les appels | — |

### Les contraintes

- Les régimes prescrits sont des **données de santé** : leur traitement est strictement encadré (RGPD, article 9), et leur hébergement peut relever de la certification d'hébergeur de données de santé (HDS).
- Un public très vulnérable : le téléphone et le papier doivent rester possibles.
- Certains hameaux de la commune n'ont pas de réseau mobile.
- Une erreur de régime peut avoir des conséquences graves pour la santé d'un bénéficiaire.

---

[← Chapitre précédent](04-J2-Atelier-Concevoir-et-soutenir.md) · [Sommaire](Readme.md) · [Chapitre suivant →](B-Modeles-et-canevas.md)
