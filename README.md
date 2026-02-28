Projet académique mettant en œuvre JDBC pour interagir avec une base de données MySQL depuis Java avec deux lab 

Lab 1 :Suivi des Scripts des Développeurs
Lab 2 : Gestion des Machines et Employés (JDBC en Couches) 

-pour lab 1 : 
   Le script SQL crée automatiquement la base atelier

   
   <img width="368" height="226" alt="Capture d&#39;écran 2026-02-11 102202" src="https://github.com/user-attachments/assets/36d07cbc-0967-4324-b924-04057dcefc11" />
   Importater   le driver JDBC (sans Maven)

   
   <img width="296" height="165" alt="image" src="https://github.com/user-attachments/assets/9f9e75e0-a95d-424a-9f3d-d8aba7558837" />
   
   la Créeation  d'une classe ExoJDBC.java  
   le résultat esl le suivant :
   
   
   <img width="747" height="447" alt="image" src="https://github.com/user-attachments/assets/6e115eee-1331-4ae3-8a35-126e14445e2f" />
   
-pour lab 2 :
   Base utilisée : atelier
   Deux tables :
   Table employe :id (AUTO_INCREMENT) ,nom ,poste
   Table machine :id (AUTO_INCREMENT) ,nom ,type ,employe_id (clé étrangère)
   Relation :
   Un employé peut avoir plusieurs machines.
   la structure du projet est la suivante :

   
   <img width="357" height="441" alt="image" src="https://github.com/user-attachments/assets/df130396-394e-44da-a1e5-8fc87e3d09d1" />
   le résultat esl le suivant :
   
   Test Employé :
   <img width="447" height="242" alt="image" src="https://github.com/user-attachments/assets/863d362a-e277-473e-8fd4-b3ffccb032fd" />
   
   Test Machine :<img width="528" height="298" alt="image" src="https://github.com/user-attachments/assets/2a1d5a8b-1085-4105-92e8-5a610e79d3bd" />

   

   

