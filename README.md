# 🛒 Ma Liste de Courses

Application web progressive (PWA) pour gérer sa liste de courses et l'envoyer via WhatsApp.

## ✨ Fonctionnalités

- 📋 **16 catégories** de produits (fruits, légumes, laitier, viandes casher, épicerie, etc.)
- ⭐ **Favoris** — marque tes produits habituels pour les retrouver vite
- 🔢 **Quantités** — ajuste le nombre d'unités par article
- ✏️ **Articles personnalisés** — ajoute n'importe quel article non listé
- 🔍 **Recherche** — filtre les produits en temps réel
- 💾 **Sauvegarde automatique** (localStorage — fonctionne hors ligne)
- 📲 **Envoi WhatsApp** en un clic, formaté proprement
- 📱 **PWA-ready** — ajoutable sur l'écran d'accueil iOS/Android

## ⚙️ Configuration

Édite les deux variables au début du fichier `index.html` :

```js
const CONFIG = {
  WHATSAPP_NUMBER: "972500000000",  // ← ton vrai numéro (sans +)
  PRENOM: "Lionel"                  // ← prénom affiché sur le bouton
};
```

## 🚀 Utilisation

Ouvre simplement `index.html` dans un navigateur — aucun serveur requis.

Pour l'héberger en ligne : GitHub Pages, Netlify, Vercel, ou n'importe quel hébergeur statique.

## 📸 Aperçu

| Écran principal | Favoris | Recherche |
|---|---|---|
| Catégories dépliables | Produits favoris regroupés | Filtre en temps réel avec surbrillance |
