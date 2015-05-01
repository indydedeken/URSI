#1. Application & User Location Diagram
The purpose of this diagram is to clearly depict the business locations from which business users typically interact with the applications, but also the hosting location of the application infrastructure.

The diagram enables :

- Identification of the number of package instances needed
- Estimation of the number and the type of user licenses
- Estimation of the level of support needed
- Selection of system management tools, structure, and management
system
- Appropriate planning for the technological components of the
business
- Performance considerations while implementing solutions 

---

#2. Schema

##2.1. Éléments

###2.1.1. Zone géographiques
L'entreprise est globalement organisée par continent :

- Europe (_Siège de la société_)
- Asie
- Amérique du Nord
- Amérique du Sud

Cependant les compagnies/agences (indépendantes) sont présentes dans les grandes villes.


###2.1.2. Acteurs et entités
Présente les acteurs qui peuvent se retrouver dans le diagramme.

- Siège monde (Europe)
	- Direction Monde (DM)
	- Direction de l'Organisation (DO)
	- Direction des finances (DF)
	- Direction du contrôle de gestion (DCG)
	- Direction Informatique (DI)
	- Direction Marketing & Reclation Client (SMRC)

- Siège pays
	- Service Financier (SFI)
	- Service RH (SRH)
	- Service des achats (SAC)
	- Service de réservation (SRE)
	- Service des équipements (SEQ)	

- Agence villes
	- Conseillers (CON)
	- Chauffeurs (_Souhait de recruter des indépendants donc non-salariés_)


##2.2. Activités
###2.2.1. Liste des activités
####2.2.1.1. Management
- Prendre les nouvelles orientations stratégiques (DM)
- Préconiser des évolutions, contrôler la mise en application (DO)
- Accompagnement des compagnies/uniformisation (DO)
- Déployement de solutions techniques informatiques (DI)
- Consolidation et synthèse des informations comptables (DF)
- Réalisation d'études (DCG)
- Gérer les offres particuliers/business (SMRC)
- Gestion de la relation client & marketing (SMRC)

####2.2.1.2. Métier
- Accueil en agence (CON)
- Suivi du service de transport (SMRC)
- Assurer le service de transport (Chauffeur)
- Gérer les réservations clients (SRE)

####2.2.1.3. Support
- Gestion RH (chauffeurs indé) (SRH)
- Équiper les véhicules (SEQ)
- Achat, maintenance et revente des véhicules (SAC)
- Gestion de la trésorerie des compagnies (SFI)