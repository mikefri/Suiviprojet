# 🚀 Guide d'Utilisation - Pilotage de Projet

Ce guide explique comment utiliser votre outil de gestion de projet avec camouflage des données.

---

## 1. Gestion de l'Équipe (À faire en premier)
Avant de créer des projets, vous devez enregistrer vos collaborateurs pour qu'ils apparaissent dans les options.

* **Accès** : Rends-toi sur la page **👥 Gestion Équipe**.
* **Action** : Saisis le nom du responsable dans le champ texte et clique sur **Ajouter**.
* **Sécurité** : Le nom est automatiquement encodé en Base64. 
* **Vérification** : Si vous ouvrez le fichier `responsables.json` directement sur GitHub, le nom doit apparaître "codé" (ex: `RnJpc2NoaGVyeiBN`).

---

## 2. Création d'un Projet
Une fois l'équipe prête, vous pouvez planifier vos tâches sur la page principale.

1.  **Ouverture** : Sur le planning, clique sur le bouton **+ Nouveau Projet**.
2.  **Saisie des informations** :
    * **Nom** : Saisis le nom du projet (celui-ci reste lisible en clair sur GitHub).
    * **Responsable** : Choisis dans la liste déroulante. *Note : Le menu affiche le vrai nom pour vous, mais le système enregistre le code caché.*
    * **Dates** : Sélectionne les dates de début et de fin via le calendrier.
3.  **Validation** : Clique sur **Enregistrer**. 
4.  **Confirmation** : La pastille **✅ ENREGISTRÉ** doit apparaître brièvement en haut à droite.

---

## 3. Pilotage au Quotidien
L'outil est interactif. Vous pouvez mettre à jour vos projets directement sur le graphique :

* **Décalage** : Cliquez et faites glisser une barre horizontalement pour changer les dates sans changer la durée.
* **Durée** : Étirez ou réduisez le bord droit d'une barre pour modifier la date de fin.
* **Progression** : Faites glisser la petite flèche foncée à l'intérieur de la barre pour ajuster le pourcentage d'avancement (%).
* **Modification précise** : Cliquez simplement au centre d'une barre pour ouvrir le formulaire complet et modifier le statut ou le responsable.
