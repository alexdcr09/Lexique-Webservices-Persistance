# Lexique pour Webservices & Persistance

## Questions :
### REST - Quelles sont les 6 contraintes ?
Client-Server - Stateless Server - Cache - Uniform interface – Layered System
### Expliquer le rôle de chacune des contraintes 
- Client-Server : Un mode de communication avec séparation de rôles entre client et serveur.
- Stateless Server : Les requêtes doivent contenir toutes les informations nécessaires au traitement.
- Cache : La réponse du serveur doit être cacheable côté client.
- Uniform interface : La méthode de communication entre client et serveur doit être uniforme avec des ressources identifiables
- Layered System : Le système doit permettre le rajout de couches intermédiaires (proxy server, firewall, CDN, etc …).
### API - 5 principaux éléments composant une requête Http :
Method, Path, Version of the protocol, Headers, Body
### 5 principaux verbes HTTP :
GET, POST, PUT, CREATE, DELETE
### JAVA - Rôle d'une annotation java :
le rôle des annotations sont d'intégrer au langage Java des métadonnées.
### Rôle du try catch :
Try catch regroupe des instructions à exécuter et définit une réponse si l'une de ces instructions provoque une exception.
#### Cache
Fichiers temporaires qui permet de sauvegarder des données
### Pourquoi faut il fermer ses ressources en informatique (ie: fichiers, connexions ...)
Il faut fermer ses ressources aux maximum pour éviter toutes failles informatique ou bien le risque de perdre ses données.
### Rôle du try with ressources :
Il permet de définir une ressource qui sera automatiquement fermée à la fin de l'exécution du bloc de code de l'instruction.
### A quoi sert Lombok ?
C'est un outil qui fournit un ensemble d'annotations utiles pour éliminer une grande quantité de code standard de vos classes Java.
### Quelles sont les annotations Lombok 
- @FieldDefaults(level=AccessLevel.PRIVATE) : passe tous les champs en private
- @NoArgsConstructor : génère le constructeur sans argument et public
- @AllArgsConstructor : génère le constructeur avec tous les arguments et public (pour l'exemple)
- @Getter : génère tous les getters sur les champs
- @Setter : génère tous les setters sur les champs
- @EqualsAndHashCode(of=...) : génère equals et hashCode (et d'autres méthodes) sur les champs donnés
- @ToString(of=...) : génère toString sur les champs donnés.
## Lexique :
#### Interropérabilité
Des systèmes qui peuvent s'adapter et communiquer avec d'autres systèmes
#### Scalabilité
La possibilité de s'adapter à la demande tout en gardant ses propriétées 
#### Scalabilité horizontale
Permet d'augmenter la puissance d'un serveur via l'ajout de nouveaux serveurs
#### Scalabilité verticale
Permet d'augmenter la puissance sur un unique serveur (RAM, CPU)
#### Stateless
C'est un système indépendant qui ne stocke pas de données
#### URI
Un uri permet de localiser un fichier et/ou d'accéder à des ressources 
#### URL
C'est l'adresse web d'un site internet 
#### Représentation d'une ressource	
C'est un style d'architecture logicielle définissant un ensemble de contraintes à utiliser pour créer des services web.
#### Proxy
C'est un intermédiaire entre un réseau local privé et le réseau internet
#### Gateway
C'est une passerelle pour relier deux réseaux distincts
#### Http Header
Ce sont les messages/valeurs qui s'affichent en haut de la requête 
#### Http version
C'est un protocole de communication entre un client et un serveur
#### Http body
La partie body du message est facultative pour un message HTTP, mais si elle est disponible, elle est utilisée pour transporter le corps de l'entité associé à la demande ou à la réponse. 
#### Content-type
Il indique au client le type de contenu réellement renvoyé
#### Http méthode (verb)
La méthode HTTP définit un ensemble de méthodes de requête qui indiquent l'action que l'on souhaite réaliser sur la ressource indiquée.
#### GET
La méthode GET est un moyen de passer des paramètres d'une requête HTTP depuis le navigateur au serveur
#### PUT
La méthode PUT crée une nouvelle ressource ou remplace une représentation de la ressource ciblée par le contenu de la requête.
#### DELETE
La méthode DELETE demande que le serveur d'origine supprime la ressource identifiée
#### POST
La méthode POST est habituellement envoyée via un formulaire HTML et a pour résultat un changement sur le serveur.
#### OPTIONS
La méthode OPTIONS représente une demande d'informations sur les options de communication disponibles sur la chaîne demandé.
#### Code dé réponse HTTP + principaux
Le code de réponse indique si une requête HTTP a été exécutée avec succès ou non.
#### Spring
C'est un framework java qui permet de construire l’infrastructure du projet et de faciliter le développement 
#### JDBC	
Java DataBase Connectivity permet de se connecter à une base de données 
#### JPA
Java Persistence API est une interface pour organiser des données relationnelles via Java
#### ORM
Object-Relational Mapping permet de faire une connexion entre un modèle objet une base de données
#### Maven
Outil de construction pour build qui permet de faciliter et automatiser certaines tâches 
#### Gestionnaire de projet
Ce sont toutes les activités visant à organiser le bon déroulement d'un projet
#### Intégration continue
C'est une pratique qui consiste à vérifier en permanence les modifications apportées et de tester de manière automatisées les modifications
#### Principes SOLID
le principe SOLID est l'acronyme de cinq principes de base (Single Responsibility Principle, Open/Closed Principle, Liskov Substitution Principle, Interface Segregation Principle et Dependency Inversion Principle) que l'on peut appliquer au développement objet.
#### Proprités ACID	
La propriété ACID est un acronyme résumant les quatre propriétés élémentaires d’une transaction au sein d’une base de données : Atomicité, Cohérence, Isolation, Durabilité. 
#### Base de donnée relationnelle
C'est une base de données ou il y a une ou des relations entre les tables 
#### Base de donnée non relationnelle
C'est une base de données ou il y n'a pas de relations entre les tables 
#### IDE	
C'est un outil qui aide la mise en œuvre d'un projet
#### VCS	
Logiciel de versionning qui permet de stocker des fichiers 
#### Lombok	
Lombok est une API dont le but est de générer à la compilation, du code Java à notre place.
#### Annotation	
Permet d'ajouter des éléments meta-données dans un code source. Il est accessible uniquement lors de la compilation
#### Port informatique	
Un port informatique c'est un système permettant aux ordinateurs de recevoir ou d'émettre des informations
#### Endpoint	
Permet d'accéder à un service en particulier
#### Connection Pool
Le pool de connexions va pré-initialiser un nombre donné de connexions, lorsque l'application démarre. Le pool de connexions va se charger de distribuer ses objets Connection aux méthodes de l'application qui en ont besoin.
#### JVM	
C'est une machine virtuelle Java qui permet d'interpréter du ByteCode
#### ByteCode	
Permet de regrouper des instructions exécutables par une machine virtuelle java.
#### Code source
Le code source est un texte regroupant tous le code lisible.
#### Compilation	
La compilation c'est le fait de traduire un programme écrit et lisible par un humain, en un programme exécutable par un ordinateur.
#### Fichier jar	
Un fichier Jar permet de distribuer un ensemble de classes Java. Permet de stocker des classes, des meta données etc
#### API
Permet d’établir des connexions entre plusieurs logiciels pour échanger des données.
#### Statement	
Les statements Java sont des instructions qui indiquent au langage de programmation ce qu'il doit faire. 
#### Chaîne de connexion à une base de donnée	
Ce sont les informations nécessaires pour que votre application puisse accéder à votre base de données. Par exemple : le nom de la BDD, le mot de passe, le nom d'utilisateur, le port etc
#### Connexion
Lien fort entre deux systèmes
#### Commit (transaction)	
Permet d'archiver / valider les modifications effectuées
#### Mapper	
C'est un type de programme pour simuler une base de données orientée objet
