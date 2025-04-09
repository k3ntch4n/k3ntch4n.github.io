# 🔐 Secure Note

Un outil simple, sécurisé et 100% frontend pour transmettre des **mots de passe** ou **messages sensibles** à des utilisateurs, sans risquer une interception.

## 💡 Contexte

En tant que technicien support, on a parfois besoin de réinitialiser un mot de passe pour un utilisateur...  
Mais la personne ne répond pas par télephone ou a des horaires décalés, et on veut **éviter que le mot de passe circule en clair**.  
Secure Note permet de :

- Chiffrer un message avec une **clé connue uniquement de l'utilisateur** (ex : email, info perso)
- Générer un **lien contenant le message chiffré**
- Permettre à l'utilisateur de **le déchiffrer côté client** avec la clé

## 🔧 Stack
- HTML + CSS (dark mode)
- JavaScript avec [CryptoJS](https://github.com/brix/crypto-js)
- Aucune base de données, aucune trace serveur
- GitHub Pages pour l’hébergement

## 🚀 Démo
👉 [Voir la version en ligne](https://tamstile.github.io/)

## 🛠️ Utilisation

1. Va sur la page de chiffrement
2. Écris ton message
3. Entres une clé secrète (connue uniquement par l'utilisateur)
4. Génère le lien → copie-le
5. L'utilisateur utilise la clé pour lire le message sur la page de déchiffrement


