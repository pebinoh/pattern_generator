# Générateur de Patron MYOG - Portefeuille Technique 🧵

Ce projet est un outil web interactif conçu pour les passionnés de **MYOG (Make Your Own Gear)**. Il permet de générer des patrons sur-mesure pour réaliser des **portefeuilles techniques**, pochettes ou trousses zippées ultra-légères (UL).

🔗 **[Voir la démo en ligne](https://ton-pseudo.github.io/generateur-pattern/)** *(Remplace ce lien une fois ta page active dans les réglages GitHub)*

## ✨ Fonctionnalités

* **Visualisation 3D Temps Réel** : Aperçu du volume final en fil de fer (wireframe) avec Three.js.
* **Curseur Zip Intelligent** : Un seul contrôle pour gérer l'extension de la fermeture éclaire (du centre du haut jusqu'à la descente sur les côtés).
* **Calcul de Volume** : Estimation automatique de la contenance en Litres.
* **Options de Construction** :
    * *1 Panneau* : Tissu plié au fond (moins de couture).
    * *2 Panneaux* : Couture au fond (pour assembler deux tissus différents).
* **Export Facile** : Génération d'un patron 2D annoté (avec marges de couture) téléchargeable en **PNG**.

## 🛠 Comment l'utiliser

1.  Ouvrez la page dans votre navigateur.
2.  Entrez vos dimensions souhaitées en **cm** (Longueur, Largeur/Profondeur, Hauteur).
3.  Ajustez le curseur **"Extension Zip"** pour définir le style d'ouverture.
4.  Cliquez sur **"Générer le patron !"**.
5.  Téléchargez l'image PNG, imprimez-la ou reportez les mesures directement sur votre tissu technique (X-Pac, Cordura, Dyneema, etc.).

## 🚀 Installation (Pour les développeurs)

Ce projet est conçu comme un fichier unique ("Single File Component") pour une simplicité maximale.

1.  Clonez ce dépôt.
2.  Ouvrez le fichier `index.html` dans votre navigateur.
3.  C'est tout ! Aucune dépendance Node.js ou installation complexe requise (les librairies sont chargées via CDN).

## 📦 Technologies

* **HTML5 / CSS3** (Design responsive et moderne type "Clean UI").
* **JavaScript (Vanilla)**.
* **Three.js** : Pour le rendu 3D.
* **Canvas API** : Pour le dessin et l'export du patron 2D.

---
*Projet Open Source - N'hésitez pas à forker pour ajouter vos propres types de poches ou fonctionnalités !*
