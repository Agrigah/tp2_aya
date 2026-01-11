📚 Collections & Generics Lab – Java Project
📋 Présentation du projet

Ce projet illustre l’utilisation des Collections Java (List, Map, Set) et des Génériques à travers des exemples pratiques.
Il couvre la manipulation de données, les opérations CRUD, et la programmation type-safe avec des classes génériques.

Auteur : Aya Agrigah
GitHub : tp2_aya

Cours : Programmation Orientée Objet en Java
Année académique : 2025/2026

📦 Partie I : Collections & Streams
1️⃣ Listes – Gestion de produits (collections)

Product.java : Modèle représentant un produit (id, name, price).
Contient constructeur, getters, setters et toString() pour l’affichage.
ProductManagementApp.java : Démonstration des opérations avec ArrayList :
Ajouter des produits

<img width="398" height="169" alt="image" src="https://github.com/user-attachments/assets/35c71804-c98a-4b95-bb5e-2135bdd347fe" />

Supprimer par index

<img width="398" height="174" alt="image" src="https://github.com/user-attachments/assets/6ad10cbc-42e7-4f38-a120-cb59fd3e0125" />

Modifier un produit
Afficher tous les produits
Rechercher par nom

<img width="401" height="298" alt="image" src="https://github.com/user-attachments/assets/7310c285-a26f-4ce8-a03a-eac4c0c4c3b0" />

📌 Montre la manipulation de listes dynamiques en Java.

2️⃣ Maps – Gestion des notes d’étudiants

StudentGradesApp.java : Utilisation d’un HashMap<String, Double> pour gérer les notes :

Ajouter / mettre à jour des notes

Augmenter une note

<img width="401" height="413" alt="image" src="https://github.com/user-attachments/assets/0d2ade9e-50c0-4bb6-9f23-087198754101" />

Supprimer des entrées

<img width="378" height="219" alt="image" src="https://github.com/user-attachments/assets/cbcf48cf-9377-43fb-b728-df88d0625a3e" />

Calculer statistiques (moyenne, max, min)

<img width="382" height="185" alt="image" src="https://github.com/user-attachments/assets/816696be-479c-41ac-9a31-d6a790b22f94" />

Vérifier la présence de certaines notes

<img width="396" height="81" alt="image" src="https://github.com/user-attachments/assets/f14aa879-f7e5-43d3-8cb2-cf6acf413fe3" />

Parcourir toutes les entrées avec forEach et lambda

<img width="363" height="223" alt="image" src="https://github.com/user-attachments/assets/ea36e221-6dc5-4291-906e-3197cee42ac0" />

📌 Exemple de gestion clé-valeur et de programmation fonctionnelle.

3️⃣ Sets – Opérations sur groupes d’étudiants

StudentGroupsApp.java : Utilisation de deux HashSet pour :

<img width="380" height="78" alt="image" src="https://github.com/user-attachments/assets/17026769-5527-4a6f-84bf-d61a7d1e702a" />

Intersection (étudiants communs)

<img width="396" height="61" alt="image" src="https://github.com/user-attachments/assets/ae0660c9-0fe0-4701-891b-92a3f1690d00" />

Union (tous les étudiants uniques)

<img width="386" height="52" alt="image" src="https://github.com/user-attachments/assets/0c88bc9d-b471-42d8-acab-2d063753df6c" />

Différence (étudiants présents dans un seul groupe)

<img width="403" height="76" alt="image" src="https://github.com/user-attachments/assets/db557bd2-27c1-4a84-8462-8c86f1f427c7" />

📌 Démontre les opérations sur les ensembles et la contrainte d’unicité.

🔧 Partie II : Génériques
1️⃣ Système de stockage générique (generics)

GenericStorage.java : Classe générique pour stocker n’importe quel type de données :

Ajouter, supprimer, récupérer par index

Obtenir la taille

Afficher tous les éléments

Type-safe sans cast

Application.java : Test de GenericStorage avec Integer, String et Double.

<img width="281" height="749" alt="image" src="https://github.com/user-attachments/assets/64720f88-d0e3-4bab-baf0-b7d1d74a601d" />

<img width="296" height="346" alt="image" src="https://github.com/user-attachments/assets/14a0d8dc-638d-47fb-9d7e-40db33d7a6a7" />

📌 Illustration de la flexibilité et de la réutilisabilité des génériques.

2️⃣ Gestion de produits avancée (products)

Product.java : Modèle produit avec id, name, brand, price, description, stockQuantity.

IMetier.java : Interface générique définissant les opérations CRUD : add, getAll, findById, delete.

MetierProduitImpl.java : Implémentation CRUD utilisant ArrayList.

Application.java : Application console avec menu :

Afficher tous les produits

Rechercher par ID

Ajouter un produit

Supprimer par ID

Quitter
<img width="417" height="707" alt="image" src="https://github.com/user-attachments/assets/b2982673-3879-47d1-896a-77e3ebc27cac" />

<img width="417" height="473" alt="image" src="https://github.com/user-attachments/assets/d0a4e9f9-1cf6-473f-9471-e1bd82a744ad" />


📌 Fournit une expérience interactive CRUD.

🎯 Compétences acquises
✅ Collections

ArrayList, HashMap, HashSet

Expressions lambda et boucles forEach

✅ Génériques

Classes et interfaces génériques

Programmation type-safe et réutilisable

✅ Principes de conception

Encapsulation

Design basé sur interfaces

Applications console CRUD

Réutilisabilité et maintenabilité du code

🚀 Exécution du projet

Chaque classe contient une méthode main().

Dans IntelliJ IDEA :

Clic droit sur le fichier Java

Sélectionner Run [ClassName].main()

Suivre les instructions dans la console
