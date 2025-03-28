# documentation des bibliothèques 2025

## bibliothèque bno055

### fonction initialisation
Intialisation du bus I2C. 
Paramétrage du capteur.

### fonction calibration
Récupère les données de calibration du capteur, et attend d'être à une valeur maximale et stable de celle ci;
### fonction read euler
Récupération des données binaire signé, converti en degré.
On récupère après convertission les données de pitch, roll et headingx

## bibliothèque TF-Luna

### Fonction initialisation
Intialisation du bus I2C. 
### Fonction read_distance 
Envoie des distances en 2 octets. Ensuite converti en cm. 


