<tldr>
<p>TL;DR</p>
<ul>
<li>Identifiez besoins fonctionnels et non fonctionnels ; choisissez technologies adéquates.</li>
<li>Concevez avec UML ; anticipez scalabilité et évolutions.</li>
<li>Assurez connectivité, redondance ; préparez pour pannes.</li>
<li>Justifiez langages/infrastructures ; priorisez adéquation aux besoins.</li>
<li>Environnements clairs (dev, test, prod) ; tests automatiques essentiels.</li>
<li>Documentez, monitorisez, loggez pour faciliter la maintenance et l'évolution.</li>
</ul>
</tldr>

# Guide : Création d'un Dossier d'Architecture Technique

Ce guide est conçu pour vous aider à naviguer dans le processus de création de votre dossier d'architecture technique
pour une application de partage de photos et de vidéos éphémères. L'objectif est de vous fournir des conseils et des
pistes de réflexion pour chaque section de votre projet, sans pour autant vous donner les solutions directement.
Utilisez ce guide comme un compagnon pour stimuler votre créativité et affiner votre approche technique.

## Analyse des Besoins

- **Fonctionnels :** Listez toutes les fonctionnalités clés que l'application doit offrir. Pensez à l'expérience
  utilisateur, à la facilité d'utilisation et aux fonctionnalités innovantes qui pourraient différencier votre
  application sur le marché.
- **Non Fonctionnels :** Ne négligez pas les aspects tels que la performance, la sécurité, la scalabilité et la
  disponibilité. Ces critères sont essentiels pour assurer la satisfaction des utilisateurs finaux.

> Pour chaque besoin non fonctionnel, envisagez des scénarios réels d'utilisation qui pourraient mettre à
> l'épreuve votre architecture.

## Architecture du Système

- **Sélection des Technologies :** La justification de chaque technologie choisie doit être claire. Reliez vos choix à
  des besoins spécifiques identifiés dans votre analyse.
- **Modélisation :** Les diagrammes UML peuvent être d'une grande aide pour visualiser l'architecture de votre système.
  Ne sous-estimez pas le pouvoir d'un bon diagramme pour clarifier vos idées.

> Gardez à l'esprit que votre architecture doit être évolutive. Comment votre système peut-il grandir ?
> Anticipez les évolutions technologiques et les augmentations de charge.

## Architecture Réseau

- **Défis de la Connectivité :** Réfléchissez à la manière dont votre application gérera les connexions dans différentes
  conditions réseau.
- **Stratégies de Redondance et de Répartition de Charge :** Assurez-vous que votre application reste disponible même en
  cas de panne d'un composant.

> Utilisez des exemples de la vie réelle pour illustrer comment votre architecture peut résister à des scénarios
> de panne.

## Choix Technologiques

- **Langages de Programmation :** Discutez des avantages et inconvénients des langages que vous avez choisis.
- **Infrastructure Cloud vs On-Premise :** Pesez les pour et contre de chaque approche en fonction des besoins
  spécifiques de votre application.

> La popularité d'une technologie n'est pas toujours le meilleur critère de sélection. Concentrez-vous sur
> l'adéquation avec vos besoins spécifiques.

## Plan de Déploiement

- **Environnements :** Définissez clairement les différents environnements (développement, test, production) et comment
  le code migre entre eux.
- **Gestion des Versions :** Avoir une stratégie solide pour la gestion des versions de votre application peut éviter de
  nombreux problèmes.

> N'oubliez pas l'importance des tests automatiques dans votre pipeline de CI/CD pour assurer la qualité de
> votre application.

## Maintenance et Évolutivité

- **Monitoring et Logging :** Avoir un bon système en place vous aidera à détecter et résoudre rapidement les problèmes.
- **Stratégie d'Évolution :** Comment intégrerez-vous de nouvelles fonctionnalités ? Comment gérerez-vous les
  changements dans les technologies sous-jacentes ?

> La documentation est clé. Assurez-vous que chaque décision et chaque architecture soit bien documentée pour
> faciliter la maintenance et les évolutions futures.

## Conclusion

N'oubliez pas que ce TP est une opportunité pour vous de démontrer votre compréhension des principes d'architecture
logicielle et réseau, ainsi que votre capacité à appliquer ces principes dans un contexte pratique.
