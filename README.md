# AP3-Eureka-Discovery
## 1. Création du service Eureka 
![Capture d’écran (114)](https://user-images.githubusercontent.com/101125181/181224026-bab1fec3-5054-4023-a6af-35bf0eb951ce.png)

![Capture d’écran (115)](https://user-images.githubusercontent.com/101125181/181224041-f7183bf7-b0e7-48ea-8fd7-bd2c44684d5b.png)
Les deux proptiétés au dessus sont à false pour indiquer a eureka que ce n'est pas la peine d'enregistrer dans l'annuaire 

## 2. Lier les services déja créer a Eureka 
Pour cela on doit mettre la valeur de la propriété spring.cloud.discovery.enbabled a true au niveau du fichier application.properties des services 
![Capture d’écran (116)](https://user-images.githubusercontent.com/101125181/181224822-a47bdd51-b99f-4068-a6d7-862dd8e071af.png)

### 3. Tester le proxy en utilisant une configuration dynamique de gestion des routes vers les microservices enregistrés dans l'annuaire Eureka Server 
![Capture d’écran (119)](https://user-images.githubusercontent.com/101125181/181226269-a1d6d773-11ca-4ec0-9da7-a0a9463dad1c.png)

![Capture d’écran (120)](https://user-images.githubusercontent.com/101125181/181227490-e8beeabc-1874-4dec-badc-fa4349670999.png)
