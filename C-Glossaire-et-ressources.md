[← Chapitre précédent](B-Modeles-et-canevas.md) · [Sommaire](Readme.md)

# Annexe C — Glossaire et ressources

## Glossaire français — anglais

L'épreuve du titre comporte un questionnaire sur une documentation technique **en anglais**, et la littérature du design de service est en grande partie anglophone. Ce glossaire donne l'équivalent anglais de chaque terme du cours.

| Français | Anglais | Définition courte | Jour |
|---|---|---|---|
| Accord de niveau de service | *service level agreement* (SLA) | contrat entre deux organisations sur un niveau de service, avec des conséquences s'il n'est pas tenu | 2 |
| Acteur | *actor* | rôle, humain ou système, qui interagit directement avec le système à construire | 2 |
| Adaptateur | *adapter* | composant qui isole le métier d'un système externe | 2 |
| Attente | *wait* | moment où l'usager attend quelque chose du service | 1 |
| Backstage, coulisses | *backstage* | ce que le personnel fait hors de la vue de l'usager | 1 |
| Budget d'erreur | *error budget* | écart toléré entre l'objectif de niveau de service et la perfection | 2 |
| Canal | *channel* | moyen par lequel l'usager et le service communiquent | 1 |
| Canevas de proposition de valeur | *value proposition canvas* | met face à face les besoins de l'usager et ce que propose le service | 1 |
| Capacité | *capability* | ce que le service doit être capable de faire, indépendamment de qui et de comment | 2 |
| Carte de parcours | *customer journey map*, *user journey map* | les étapes vécues par un usager pour atteindre un objectif | 1 |
| Carte des parties prenantes | *stakeholder map*, *ecosystem map* | les acteurs d'un service rangés en cercles, et leurs échanges | 1 |
| Cas d'utilisation | *use case* | interaction entre un acteur et le système pour atteindre un but | 2 |
| Contexte délimité | *bounded context* | périmètre à l'intérieur duquel un modèle et son vocabulaire ont un sens unique | 2 |
| Cycle de vie, diagramme d'états | *lifecycle*, *state diagram*, *state machine* | les états successifs d'un objet et les événements qui les font changer | 2 |
| Design de service | *service design* | conception de tout ce qui permet à un service d'être rendu, devant et en coulisses | 1 |
| Diagramme de séquence | *sequence diagram* | les messages échangés entre participants, dans l'ordre | 2 |
| Double diamant | *Double Diamond* | modèle en quatre phases : découvrir, définir, développer, livrer | 1 |
| Engagement, principe de service | *service principle*, *service standard* | promesse vérifiable faite à l'usager ou au personnel | 1 |
| Exigence non fonctionnelle | *non-functional requirement* (NFR), *quality attribute* | ce que le système doit garantir, au-delà de ce qu'il fait : sécurité, performance, accessibilité… | 2 |
| Frontstage | *frontstage* | ce que le service fait sous les yeux de l'usager | 1 |
| Idempotence | *idempotency* | propriété d'une opération qui, répétée, produit le même effet qu'une seule fois | 2 |
| Indicateur de niveau de service | *service level indicator* (SLI) | mesure de la qualité d'un service, souvent un ratio | 2 |
| Ligne d'interaction | *line of interaction* | sépare l'usager du service, dans un blueprint | 1 |
| Ligne d'interaction interne | *line of internal interaction* | sépare le personnel au contact des fonctions et systèmes support | 1 |
| Ligne de visibilité | *line of visibility* | sépare ce que voit l'usager de ce qu'il ne voit pas | 1 |
| Loi de Conway | *Conway's law* | les systèmes reproduisent la structure de communication des organisations qui les conçoivent | 2 |
| Magicien d'Oz | *Wizard of Oz* | prototype dont la partie « automatique » est réalisée en secret par un humain | 2 |
| Marche à blanc | *desktop walkthrough* | simulation d'un service sur une table, rôle par rôle | 2 |
| Mode dégradé | *degraded mode*, *graceful degradation* | fonctionnement réduit mais acceptable quand une partie du système tombe | 2 |
| Moment de vérité | *moment of truth* | moment du parcours où le service se gagne ou se perd | 1 |
| Monolithe modulaire | *modular monolith* | application déployée d'un seul tenant, mais découpée en modules indépendants | 2 |
| Objectif de niveau de service | *service level objective* (SLO) | cible fixée pour un indicateur, sur une période | 2 |
| Omnicanal | *omnichannel* | où l'usager peut changer de canal sans recommencer | 1 |
| Partie prenante | *stakeholder* | personne, groupe ou organisation qui agit sur le service, en est affecté, ou peut le faire échouer | 1 |
| Passage de relais | *handoff* | transmission d'une tâche ou d'une information entre deux acteurs | 1 |
| Pilote | *pilot* | mise en service réelle, à petite échelle et pour une durée limitée | 2 |
| Point de contact | *touchpoint* | occasion concrète d'interaction entre l'usager et le service | 1 |
| Point de rupture | *fail point* | endroit où le service peut échouer | 1 |
| Preuve physique | *physical evidence* | ce que l'usager voit, touche ou reçoit à une étape | 1 |
| Processus support | *support processes* | systèmes, services internes et partenaires qui soutiennent le service | 1 |
| Promesse | *value proposition*, *service promise* | ce que le service apporte, à qui, et en quoi il diffère de l'existant | 1 |
| Règle de gestion | *business rule* | règle métier que le service applique, et que le logiciel devra coder | 1, 2 |
| Règle du pic et de la fin | *peak-end rule* | on juge une expérience surtout sur son moment le plus intense et sur sa fin | 1 |
| Rupture de canal | *channel break* | changement de canal qui fait perdre ou répéter une information | 1 |
| Service blueprint | *service blueprint* | représentation d'un service en couloirs, du visible aux processus support | 1 |
| Sobriété numérique, écoconception | *digital sobriety*, *eco-design* | réduire l'empreinte environnementale d'un service numérique dès sa conception | 2 |
| Traçabilité | *traceability* | lien explicite entre un besoin et les éléments de conception qui y répondent | 2 |
| Usager | *user*, *customer* | personne qui bénéficie du service ; dans le secteur public, on dit plus volontiers usager que client | 1 |

## Ressources

### Le design de service

- G. Lynn Shostack, [*Designing Services That Deliver*](https://hbr.org/1984/01/designing-services-that-deliver), Harvard Business Review, 1984 — l'article fondateur du blueprint.
- Mary Jo Bitner, Amy Ostrom et Felicia Morgan, *Service Blueprinting: A Practical Technique for Service Innovation*, California Management Review, 2008.
- Marc Stickdorn, Markus Hormess, Adam Lawrence et Jakob Schneider, *This Is Service Design Doing*, O'Reilly, 2018 — et [ses méthodes en accès libre](https://www.thisisservicedesigndoing.com/).
- [Service Design Tools](https://servicedesigntools.org/) — une collection ouverte d'outils et de tutoriels de design de service, à filtrer selon la phase du projet, les participants, l'objet travaillé et la forme de représentation.
- Nielsen Norman Group, [*Service Blueprints: Definition*](https://www.nngroup.com/articles/service-blueprints-definition/) et [*Journey Mapping 101*](https://www.nngroup.com/articles/journey-mapping-101/).
- Design Council, [*The Double Diamond*](https://www.designcouncil.org.uk/our-resources/the-double-diamond/) — la présentation officielle du double diamant.
- Jan Carlzon, *Renversons la pyramide ! Pour une nouvelle répartition des rôles dans l'entreprise*, InterÉditions, 1986 — les moments de vérité.

### Le design de service dans le secteur public

- [DesignGouv](https://design.numerique.gouv.fr/) — les ressources de la direction interministérielle du numérique (DINUM) pour concevoir des services publics numériques simples et inclusifs.
- [La 27e Région](https://www.la27eregion.fr/) — un laboratoire de transformation publique, pionnier du design des politiques publiques en France.

### Du service au logiciel

- Google, *Site Reliability Engineering*, chapitre [*Service Level Objectives*](https://sre.google/sre-book/service-level-objectives/).
- Martin Fowler, [*Bounded Context*](https://martinfowler.com/bliki/BoundedContext.html) et [*Conway's Law*](https://martinfowler.com/bliki/ConwaysLaw.html).
- Eric Evans, *Domain-Driven Design: Tackling Complexity in the Heart of Software*, Addison-Wesley, 2003.
- Mermaid : [diagrammes de séquence](https://mermaid.js.org/syntax/sequenceDiagram.html), [diagrammes d'états](https://mermaid.js.org/syntax/stateDiagram.html), [diagrammes de classes](https://mermaid.js.org/syntax/classDiagram.html).
- PlantUML : [diagrammes de cas d'utilisation](https://plantuml.com/fr/use-case-diagram).

### Les exigences

- [Référentiel général d'amélioration de l'accessibilité](https://accessibilite.numerique.gouv.fr/) (RGAA).
- [Référentiel général d'écoconception de services numériques](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) (RGESN).
- CNIL, [*Guide RGPD du développeur*](https://www.cnil.fr/fr/guide-rgpd-du-developpeur).
- [Directive (UE) 2019/882](https://eur-lex.europa.eu/eli/dir/2019/882/oj) relative aux exigences en matière d'accessibilité applicables aux produits et services, dite *European Accessibility Act*, applicable depuis le 28 juin 2025.

## Outils

| Besoin | Outil | Remarque |
|---|---|---|
| Cartographies collaboratives | [Excalidraw](https://excalidraw.com), Miro, FigJam | Excalidraw fonctionne sans compte |
| Blueprint | un tableur, un tableau blanc, ou un mur et des post-its | un tableau à couloirs suffit ; les outils spécialisés n'ajoutent pas grand-chose à ce niveau |
| Diagrammes UML | [Mermaid](https://mermaid.js.org/), [PlantUML](https://plantuml.com/fr/), [draw.io](https://app.diagrams.net/) | Mermaid est affiché directement par GitHub |
| Dossier de conception | un dépôt Git, en Markdown | les diagrammes Mermaid y vivent à côté du texte |

---

[← Chapitre précédent](B-Modeles-et-canevas.md) · [Sommaire](Readme.md)
