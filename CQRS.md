# Architecture logicielle - Command Query Responsibility Segregation (CQRS)


Pourquoi existe-t-il des patrons d'architecture logicielle ?

Ne pouvons-nous simplement écrire du code et voir comment il évolue ? L'utilisation de patrons connus présente des avantages significatifs. 

Nous pouvons le comparer aux plans d'une maison. Vous pourriez construire une maison sans plan et vous pourriez vous retrouver avec quelque chose d'assez bien. 

Que va-t-il se passé si vous voulez construire quelque chose de plus grand et du plus complexe ?

L'objectif est de s'appuyer sur la sagesse collective, afin de rendre vos application plus faciles à maintenir et a étendre.

Les patrons figurent dans de nombreux ouvrages et documents. Si vous avez des questions à leur sujet, il est donc facile de trouver des informations. 

Ainsi connaitre plusieurs patrons d'architecture de devenir un membre plus productif de l'equipe.




Voici une liste non exhausitive de différent patron d'architecture logicielle regroupé par thème personnel : 
- Paysage
	- Monolith
	- N-tier
	- Architecture orientée services (SOA)
	- Microservices
	- Serverless
	- Peer-to-Peer
- Structure
	- Couches
	- Micronoyau (microkernel)
	- Command Query Responsibility Segregation (CQRS)
	- Event sourcing
	- CQRS + Event Sourcing
- Interface
	- MVC
	- MVP (presenter)
	- MVVM

Aujourd'hui nous allons étudier le patron d'architecture appellé Command Query Responsibility Segregation (CQRS).

## Command Query Responsibility Segregation (CQRS)

