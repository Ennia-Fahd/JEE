# Gestion Patient
Architecture :
![architecture](https://user-images.githubusercontent.com/92646945/233733151-a0dfbb86-820e-412c-bb5e-8b6f8a184008.png)

L'architecture JEE (Java Enterprise Edition) pour les applications Web se compose de trois couches principales : la couche présentation, la couche métier et la couche d'accès aux données. La couche présentation est la partie visible de l'application, qui est généralement composée de pages JSP (JavaServer Pages) et de contrôleurs (Servlets) qui communiquent avec le client HTTP.

Le modèle de conception MVC (Modèle-Vue-Contrôleur) est généralement utilisé pour structurer la couche présentation d'une application JEE. Dans ce modèle, les pages JSP agissent comme la vue, qui est responsable de la présentation des données à l'utilisateur final. Les contrôleurs, qui sont des Servlets, agissent comme le contrôleur, qui reçoit les demandes du client HTTP, traite les données et retourne une réponse appropriée.

La couche métier est la partie de l'application qui contient la logique métier et est généralement composée de classes Java. Cette couche est responsable de la validation des données, de l'exécution de la logique métier et de la communication avec la couche d'accès aux données.

Enfin, la couche d'accès aux données est responsable de l'interaction avec les sources de données, telles que les bases de données, les fichiers ou les services Web. Cette couche est généralement composée de classes DAO (Data Access Object) qui fournissent une interface pour interagir avec les sources de données.

Dans l'ensemble, les composants JSP, Servlet, couche métier et couche d'accès aux données travaillent ensemble pour créer des applications Web JEE dynamiques et robustes. Les Servlets agissent comme un contrôleur pour les demandes HTTP, communiquent avec la couche métier pour traiter les données et utilisent les pages JSP pour présenter les résultats au client HTTP.


Interface Login
![login](https://user-images.githubusercontent.com/92646945/233733176-35400734-5f86-43b1-8c05-99a42fba2b03.png)
Interface User 
![interface_user](https://user-images.githubusercontent.com/92646945/233733192-cf5c72f0-f345-4498-910a-75614fb91d3b.png)
Barre de recher :
![recherche](https://user-images.githubusercontent.com/92646945/233733207-fad7bea6-4218-49e4-809e-2c27b35888aa.png)
Interface Admin :
![interface_admin](https://user-images.githubusercontent.com/92646945/233733228-9d082d82-73aa-4c39-8ba3-804a4f00a1aa.png)
Ajouter :
![ajout](https://user-images.githubusercontent.com/92646945/233733264-5e31408c-4cf9-48ec-8a5f-102f6f8f5f40.png)
Editer :
![edit](https://user-images.githubusercontent.com/92646945/233733271-f4fb4b81-c7fb-4018-b135-ef57f92bdef9.png)
Supprimer :
![delete 1](https://user-images.githubusercontent.com/92646945/233733285-404854da-2a88-4e0b-b5cf-82ccf5618a7d.png)
![delete2](https://user-images.githubusercontent.com/92646945/233733293-ed5d839a-ca2f-452c-b55b-e737b9f92786.png)
