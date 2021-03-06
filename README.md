* *Environment : #!/bin/bash*
* *Requirement : **gdal exiftool awk bc***
* Toises vers mètres EPSG:27561 --> EPSG:3857 (ou Google 900913)

# Atlas du Plan général de la Ville de Paris, levé géométriquement par le Citoyen Verniquet
# République Française - An IV
## Rapporté sur une échelle d'une demie ligne pour toise, divisée en 72 planches, compris les cartouches et plan des opérations trigonométriques.


![Screenshot](img/Front.jpg)

Usage: Verniquet2metters/Start.sh

Conventions / noms de fichiers : Planche-[numèro_de_Planche]_Edme_Verniquet.tif

exemple: Planche-35_Edme_Verniquet.tif

Georeferencement unité source : toises

Origine : pilier géodésique de l'Observatoire de Paris.

1 toise = 1.949036310 mètre

Pied de roi (Charlemagne) utilisé entre 1668 et 1799 d'une longueur de = 0.32483938500000000000 mètre

Charlemagne dit fils de Bert aux grands pieds. 

Position théorique du pilier géodésique en Lamber Nord EPSG:27561:

Soit 2 toises et 5 pieds au sud du centre du puits. Ou: 17 pieds

Soit 5.84710893000000000000 toises (décimales) au sud du centre du puits

Soit encore en (mètres) : 16.566808635 m au sud du centre du puits

Centre du puits Lambert Nord EPSG:27561 : Est 600000 Nord 126224 unité / mètres

![Screenshot](img/Observatoire.jpg)

Pilier géodésique Lambert Nord EPSG:27561 : Est 600000 Nord 126207.433191365 unité / mètres

Destination depuis Nouvelle Triangulation Francaise (Paris) EPSG:27561 vers (mètres) EPSG:3857

![Screenshot](img/Babinet_btv1b53065387c_f1.jpg)

Petit clin d'oeil à mon ancètre Jacques Babinet, ici photographié par Nadar vers 1860 :
[Jacques Babinet](https://fr.wikipedia.org/wiki/Jacques_Babinet)

![Screenshot](img/Shell.jpg)

Toises / Echele

![Screenshot](img/echele.jpg)


