<tldr>
<p>TL;DR</p>
<ul>
<li>Identifiez les besoins fonctionnels et non fonctionnels ; choisissez les technologies adéquates.</li>
<li>Concevez avec UML ; anticipez la scalabilité et l'évolution.</li>
<li>Assurez la connectivité et la redondance ; préparez-vous pour les pannes.</li>
<li>Justifiez les langages et infrastructures choisis ; priorisez les actions en adéquation aux besoins.</li>
<li>Environnements clairs (dev, test, prod) ; tests automatiques essentiels.</li>
<li>Documentez, monitorez, loggez pour faciliter la maintenance et l'évolution.</li>
</ul>
</tldr>

# Guide : Création d'un Dossier d'Architecture Technique

Ce guide est conçu pour vous aider à naviguer dans le processus de création de votre dossier d'architecture technique
pour un projet informatique.
L'objectif est de vous fournir des conseils et des pistes de réflexion pour chaque section de votre projet, sans pour
autant vous donner les solutions directement.

> Utilisez ce guide comme un compagnon pour stimuler votre créativité et affiner votre approche technique.
{style="note"}

La première étape consiste à articuler de manière explicite la synthèse des idées de chaque partie prenante concernant
l'architecture souhaitée. Cette démarche est souvent illustrée à travers des schémas représentant les différentes
couches de l'architecture. En d'autres termes, le DAT s'efforce de clarifier et de communiquer la vision globale de
l'architecture future de l'entreprise.

> Les diagrammes UML peuvent être d'une grande aide pour visualiser l'architecture de votre système.
> Ne sous-estimez pas le pouvoir d'un bon diagramme pour clarifier vos idées.

## Des besoins, une architecture

Le deuxième objectif consiste à détailler les mécanismes mis en œuvre pour assurer la disponibilité, la performance, la
résilience, le chiffrement, la sauvegarde, et d'autres aspects cruciaux.
En d'autres termes, il s'agit d'expliquer comment l'architecture prévue répond aux défis et aux exigences
opérationnelles.

### Définitions

- **Fonctionnels :** Listez toutes les fonctionnalités clés que l'application doit offrir. Pensez à l'expérience
  utilisateur, à la facilité d'utilisation et aux fonctionnalités innovantes qui pourraient différencier votre
  application sur le marché.
- **Non Fonctionnels :** Ne négligez pas les aspects tels que la performance, la sécurité, la scalabilité et la
  disponibilité. Ces critères sont essentiels pour assurer la satisfaction des utilisateurs finaux.

> Pour chaque besoin non fonctionnel, envisagez des scénarios réels d'utilisation qui pourraient mettre à
> l'épreuve votre architecture.

> Utilisez des exemples de la vie réelle pour illustrer comment votre architecture peut résister à des scénarios
> de panne.

## Architecture du Système

- **Sélection des Technologies :** La justification de chaque technologie choisie doit être claire. Reliez vos choix à
  des besoins spécifiques identifiés dans votre analyse.
- **Langages de Programmation :** Discutez des avantages et inconvénients des langages que vous avez choisis.
- **Infrastructure Cloud vs On-Premise :** Pesez les pour et contre de chaque approche en fonction des besoins
  spécifiques de votre application.

> La popularité d'une technologie n'est pas toujours le meilleur critère de sélection. Concentrez-vous sur
> l'adéquation avec vos besoins spécifiques.

> Gardez à l'esprit que votre architecture doit être évolutive. Comment votre système peut-il grandir ?
> Anticipez les évolutions technologiques et les augmentations de charge.

## Établir les engagements de service

Ce troisième objectif implique la formalisation des engagements de service attendus, notamment à travers des documents
tels que la définition des Indicateurs de Mesure d'Activité (DIMA), le Plan Directeur des Moyens d'Action (PDMA), et
autres aspects mentionnés précédemment. Cette étape vise à définir clairement les niveaux de performance et de qualité
que l'architecture doit respecter.

- **Défis de la Connectivité :** Réfléchissez à la manière dont votre application gérera les connexions dans différentes
  conditions réseau.
- **Stratégies de Redondance et de Répartition de Charge :** Assurez-vous que votre application reste disponible même en
  cas de panne d'un composant.

> Utilisez des exemples de la vie réelle pour illustrer comment votre architecture peut résister à des scénarios
> de panne.

## Planifier les actions à entreprendre

L'objectif suivant est de fournir une vue d'ensemble des tâches à accomplir, servant ainsi de référence essentielle pour
le chef de projet. Cette vue macro permet de définir les grandes étapes du projet et d'orienter les efforts de l'équipe
de réalisation.

- **Environnements :** Définissez clairement les différents environnements (développement, test, production) et comment
  le code migre entre eux.
- **Gestion des Versions :** Avoir une stratégie solide pour la gestion des versions de votre application peut éviter de
  nombreux problèmes.
- **Monitoring et Logging :** Avoir un bon système en place vous aidera à détecter et résoudre rapidement les problèmes.
- **Stratégie d'Évolution :** Comment intégrerez-vous de nouvelles fonctionnalités ? Comment gérerez-vous les
  changements dans les technologies sous-jacentes ?

> La documentation est clé. Assurez-vous que chaque décision et chaque architecture soit bien documentée pour
> faciliter la maintenance et les évolutions futures.

> N'oubliez pas l'importance des tests automatiques dans votre pipeline de CI/CD pour assurer la qualité de
> votre application.

## Communiquer efficacement sur le projet

Enfin, le DAT joue un rôle crucial dans la communication du projet aux différentes parties prenantes de l'entreprise, y
compris la direction générale, les autres architectes et les équipes chargées de la mise en œuvre.
Son rôle est de présenter efficacement le projet, en mettant en avant ses bénéfices et en répondant aux éventuelles
questions ou préoccupations. En somme, le DAT est le porte-parole de l'architecture technique auprès des différentes
parties prenantes de l'entreprise.

## Conclusion

N'oubliez pas que ce TP est une opportunité pour vous de démontrer votre compréhension des principes d'architecture
logicielle et réseau, ainsi que votre capacité à appliquer ces principes dans un contexte pratique.
