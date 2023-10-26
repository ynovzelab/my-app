## SQL create table in DB
CREATE TABLE articles (
    id INT AUTO_INCREMENT PRIMARY KEY,
    titre VARCHAR(255) NOT NULL,
    description TEXT,
    date DATE
)

## insert data in DB
INSERT INTO articles (titre, description, date) VALUES ?

## À FAIRE

    - L'application actuelle est en monolythe.
    - Fractionner l'application en plusieurs composants applicatifs : 
        - Un backend qui délivre du contenu en RESTFULL (protocole http)
        - Un frontend qui intéragit avec l'application backend (l'API) pour récupérer le contenu et l'afficher sur une page
        - Dans ce repo : enlever les vues et les intégrer dans un framework frontend de votre choix (Angular, vue, React, Svelte etc...)
            - Pour le frontend, penser à bien modulariser l'application en composants réutilisables 
        - Le choix du backend est libre (Python, Go, Node js etc ....)
            - Penser à bien structurer le code en Couche (controller, models, routes)
        - Le chois de la base de données est libre (Sql, Nosql)

