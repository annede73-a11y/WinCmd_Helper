# 🛠️ WinCmd Helper

**WinCmd Helper** est un assistant d'administration système intelligent, moderne et 100 % local, conçu pour les techniciens, administrateurs et utilisateurs avancés sous Windows. Développé pour servir de véritable couteau suisse, il permet de rechercher, comprendre, composer et dépanner des commandes CMD, PowerShell et WSL en toute sécurité.

---

## ✨ Fonctionnalités principales

*   📚 **Encyclopédie de commandes :** Un catalogue bilingue structuré (modes *Simple* et *Expert*) classé par catégories (Réseau, Système, Disques, etc.) avec niveaux de risque et badges de privilèges Administrateur.
*   🔍 **Décodeur de commandes (Fonction inverse) :** Collez une ligne de commande complexe : l'application découpe les paramètres et affiche une analyse détaillée des risques et des droits requis (avec alertes sur les analyses incertaines), **sans rien exécuter**.
*   🧙 **Atelier de Scripts & Générateur Interactif (Wizard) :** Formulaires dynamiques pour les commandes complexes (`robocopy`, `netsh`, etc.) avec mise à jour en temps réel et **export propre au format `.bat` ou `.ps1`**.
*   ⭐ **Favoris & Notes personnelles :** Épinglez vos commandes fétiches, ajoutez-leur des notes textuelles et retrouvez-les dans un espace dédié (persistance locale dans `data/favorites.json`).
*   📋 **Traducteur d'Erreurs :** Analyse et traduction des codes d'erreur Windows courants, avec prise en charge du collage manuel ou de l'import de fichiers de logs (`.log`, `.txt`).
*   🛠️ **Dépannage Guidé pas à pas :** Assistants de résolution par scénarios ciblés (réseau/DNS, fichiers système) pour générer des commandes sur-mesure.
*   🧰 **Boîte à Outils & Sélecteur de Shell :** Filtrage par terminal cible (CMD, PowerShell, WSL) et raccourci sécurisé pour ouvrir un terminal vide (`cmd.exe`, `powershell.exe`, `wsl.exe`) directement dans un dossier cible.

---

## 🔒 Philosophie & Sécurité

*   **100 % Local & Portable :** Fonctionne entièrement hors-ligne. Aucun stockage cloud, aucune télémétrie, aucun fichier de configuration intrusif.
*   **Zéro exécution automatique :** L'application ne lance jamais de commande système ou de script en arrière-plan à votre insu. Elle se contente de copier, préparer ou afficher des informations pour vous laisser le contrôle total.

---

## 📄 Licence

Ce projet est distribué sous licence libre. Consultez le fichier `LICENSE` pour plus de détails.
