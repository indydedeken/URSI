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


###2.1.2. Acteurs
Présente les acteurs qui peuvent se retrouver dans le diagramme.
- Client
- Fournisseur (Voiture)
- Chauffeurs (_Souhait de recruter des indépendants donc non-salariés_)
- Compagnies/employés
	- Service financier
	- Service RH
	- Service marketing
	- Hotline de réservation
	- Service des achats
	- Installateurs de voiture


##2.2. Applications
### 2.2.1 Liste des applications
Présente les acteurs qui doivent se retrouver dans le diagramme.
- SRM (Supplier Relationship Management)
- Gestion des véhicules
- Référentiels (? intégré à Gestion des véhicules ?)
- Système d’archivage électronique pour la conservation des contrats
- Application de réservation de course

### 2.2.2 Matrice des applications

| Application | Type d'ut. | Interne/Externe | Localisation de l'ut. | Unité  |
|-------------|------------|----------------|-----------------------|--------|
| SRM         | Admin, Super-utilisateur, Développeurs | Interne | Europe (siège) | Service des achats |
| Gestion des véhicules | Compagnies | Interne | Compagnies des pays | Service des achats, Compagnies |
| Référentiels | Administrateur BDD | Interne | Datacenter des pays | Service achat, Service marketing, service financier |
| Système archivage contrats | Service juridique | Interne | Europe (siège) | Service financier |
| Application de réservation | Developpeurs | Externe | Global | Service marketing |


* Précision sur le tableau : 
	- SRM : l'application est utilisée en interne même si elle permet de communiquer avec les frs.


---

#3. Source : 

- [http://forge.modelio.org/](http://forge.modelio.org/projects/togaf-user-manual-english/wiki/Modeling_Application_modeling)
- [http://www.togaf.info/](http://www.togaf.info/togaf9/togafSlides9/TOGAF-V9-Sample-Catalogs-Matrics-Diagrams-v2.pdf)
- [http://www.togaf-modeling.org](http://www.togaf-modeling.org/models/application-architecture-menu/application-and-user-location-diagrams-menu.html)