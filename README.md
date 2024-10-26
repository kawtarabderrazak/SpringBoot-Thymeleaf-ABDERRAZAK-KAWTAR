# SpringBoot-Thymeleaf-ABDERRAZAK-KAWTAR
 TP : Spring Boot et Thymeleaf
Description
Ce TP consiste à développer une application Web CRUD utilisant Spring Boot et Thymeleaf. L'objectif est de comprendre comment créer une application avec une couche DAO qui fournit des fonctionnalités CRUD sur des entités JPA, tout en simplifiant le processus grâce aux outils offerts par Spring Boot.

Objectifs
Comprendre l'architecture d'une application Spring Boot utilisant Thymeleaf.
Implémenter les dépendances Maven nécessaires à la gestion des versions et des plug-ins.
Configurer l'application pour se connecter à une base de données MySQL.
Créer une couche de domaine avec des entités JPA.
Développer une couche de référentiel pour gérer les opérations CRUD.
Mettre en place une couche contrôleur pour gérer les requêtes HTTP.
Concevoir la couche présentation avec des templates Thymeleaf.
Étapes du TP
1. Les dépendances Maven
Utiliser spring-boot-starter-parent pour une gestion simplifiée des dépendances et des versions.

2. Configuration application.properties
Configurer la source de données et les propriétés JPA dans le fichier application.properties.

3. La couche de domaine
Créer les entités qui modélisent les utilisateurs, en utilisant des annotations pour définir les contraintes de validation.

4. La couche de référentiel
Étendre l'interface CrudRepository pour fournir des opérations CRUD sur les entités.

5. La couche contrôleur
Développer les méthodes nécessaires pour gérer les requêtes HTTP, valider les données des formulaires et interagir avec le référentiel.

6. La couche présentation
Créer les templates HTML nécessaires pour afficher les formulaires d'inscription, de mise à jour et la liste des utilisateurs.

7. Exécution de l'application
Définir le point d'entrée de l'application et exécuter l'application pour tester les fonctionnalités CRUD.

Conclusion
À l'issue de ce TP, vous aurez acquis les compétences nécessaires pour développer une application Web CRUD complète avec Spring Boot et Thymeleaf, tout en comprenant les concepts fondamentaux de la gestion des dépendances, de la configuration de la base de données et des interactions entre les différentes couches de l'application.
