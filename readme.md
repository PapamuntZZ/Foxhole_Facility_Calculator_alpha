# 🛠️ Foxhole Facility Architect (v2.5)

Cet outil est un planificateur de production avancé conçu spécifiquement pour les infrastructures de **Foxhole**. Il permet de simuler une chaîne logistique complexe, de calculer les besoins énergétiques et d'évaluer la production réelle en cas de pénurie de ressources.

## 🚀 Fonctionnalités clés

* **⚡ Gestion Énergétique (Peak Power) :** Le système calcule la charge électrique en prenant le pic de consommation de chaque usine (la recette la plus gourmande parmi les slots actifs), conformément à la logique du jeu.
* **📈 Mode Réel (Simulation de Flux) :** D'un simple clic, basculez de la théorie à la réalité. Si une ressource vient à manquer sur votre réseau, les usines consommatrices ralentissent proportionnellement à la disponibilité.
* **📦 Gestion des Imports :** Définissez pour chaque ressource si elle est produite localement ou importée de l'extérieur. Les ressources importées sont considérées comme infinies pour la simulation.
* **🖱️ Interface Interactive :** Glissez-déposez vos bâtiments, configurez leurs upgrades et slots de production en temps réel.
* **📂 Brain JSON Dynamique :** Toutes les recettes et statistiques proviennent d'un fichier `data.json` externe, facilitant les mises à jour lors des patchs de jeu.

## 📋 Comment utiliser l'outil

1.  **Ajouter des usines :** Utilisez la barre latérale gauche pour poser vos structures sur le canevas.
2.  **Configurer :** Choisissez l'upgrade du bâtiment et assignez des recettes aux différents slots de production.
3.  **Analyser :** Regardez le panneau de droite pour voir votre balance énergétique et vos flux de ressources.
    * **Bleu :** Excédent de production (votre profit net).
    * **Orange :** Besoin non couvert par votre production locale.
4.  **Simuler :** Activez le **"Mode Réel"** pour voir le rendement effectif de vos machines selon l'état actuel de vos stocks.

## 🛠️ Installation Technique

Si vous souhaitez modifier la base de données :
1.  Modifiez le fichier `data.json`.
2.  L'application chargera automatiquement les nouvelles données.

---
*Développé pour l'efficacité logistique du régiment.*