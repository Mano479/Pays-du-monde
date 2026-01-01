# 🌍 Quiz Carte du Monde

## 📝 Description

Ce projet est un **jeu interactif de géographie** où l'utilisateur doit deviner le plus de pays possible sur une carte du monde en **20 minutes** ⏱️ (comme JetPunk).  

L'objectif est de taper le nom des pays dans l'input, et si le nom est correct :  

- ✅ Le pays sur la carte devient vert.  
- 🏷️ Son nom apparaît dans le tableau en dessous.  
- ✨ Les pays sont reconnus même si l’utilisateur fait des erreurs d’accents ou de majuscules.  
- 🔤 Gestion des alias pour les pays (ex : `"USA"` ou `"États-Unis"`).  

Le jeu propose un **minuteur**, un compteur de pays trouvés, et des popups de fin avec les résultats 🎉.  

---

## 🎮 Fonctionnalités principales

- 🗺️ Carte SVG du monde, zoomable au clic (zoom centré sur la position du clic).  
- 💻 Input moderne et centré pour entrer les noms de pays.  
- 📊 Tableau responsive avec les pays trouvés, organisé en **5 colonnes**.  
- 📐 Les cases du tableau ont une **taille fixe**, elles ne bougent pas lorsque le nom apparaît.  
- 🅰️ Gestion des accents et majuscules pour faciliter la saisie.  
- ⏳ **Minuteur de 20 minutes** avec popup de fin :  
  - 🛑 Si le temps est écoulé : les pays non trouvés sont révélés et colorés en rouge.  
  - 🎉 Si l’utilisateur trouve tous les pays avant la fin : popup “Bravo vous avez trouvé tous les pays !”  
- 🖼️ Popups modernes avec bouton OK toujours en dessous du message.  

---

## 🛠️ Technologies utilisées

- **HTML5 / CSS3 / JavaScript**  
- **SVG** pour la carte du monde  
- Aucune bibliothèque externe nécessaire  

---

## 🔧 Personnalisation

- Vous pouvez modifier la durée du jeu en changeant la valeur du minuteur dans `timeLeft` (l.927).  
- Ajouter ou modifier des alias pour les pays dans `countries` (l. 603).
- Modifier la tolérence d'erreur `threshold` (l.793).

---

## 📜 Remarque
- Le projet a été réalisé uniquement pour le fun, donc certains pays sont en "trop", d'autres ne sont pas présents, et pour certains, il faudrait ajouter des alias.
- Le projet a été réalisé rapidement donc tout est dans un seul et même fichier, les pays sont en clair dans le html mais généralement on essaye pas de tricher quand on joue à ce genre de jeu.
