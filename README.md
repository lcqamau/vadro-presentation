<div align="center">
  <img src="https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?auto=format&fit=crop&w=1200&q=80" alt="Vadro Banner" width="100%" style="border-radius: 10px;" />

  <h1>🌍 Vadro — L'App de Voyage Nouvelle Génération</h1>

  <p>
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  </p>

  <p><i>Note : Le code source de cette application est privé pour des raisons de propriété intellectuelle. Ce dépôt sert de présentation de l'architecture et du produit.</i></p>
</div>

---

## ✨ Concept & Vision

La plupart des applications de voyage se contentent de lister des lieux. **Vadro** va plus loin en proposant une plateforme mobile **B2B2C** conçue pour les voyageurs, les créateurs de contenu et les hôtes Airbnb.

1. **Inspiration structurée :** Les voyages sont découpés jour par jour avec des étapes ultra-précises (Dormir, Manger, Activités, Spots secrets).
2. **Le concept de "Remix" 🪄 :** Un utilisateur trouve un voyage parfait mais veut changer l'hôtel du Jour 2 ? Il le "Remixe". L'itinéraire est cloné dans son espace personnel, prêt à être adapté à ses dates.
3. **Business Model (Le cheval de Troie) :** Les hôtes Airbnb utilisent Vadro pour créer leur guide d'accueil interactif. Les voyageurs scannent un QR code, récupèrent l'itinéraire local, le remixent, et réservent via les liens d'affiliation générés par Vadro.

---

## 🚀 Fonctionnalités Clés

* 🗺️ **Itinéraires Jour par Jour :** Cartes interactives dynamiques et timeline détaillée.
* 🪄 **Moteur de Remix :** Clonage d'itinéraires complexes en base de données en un seul clic.
* ❤️ **Système Social :** Favoris synchronisés avec *Optimistic UI* et retours haptiques natifs (façon Instagram).
* 🔗 **Smart Booking :** Transformation algorithmique des étapes (GPS + Dates) en liens d'affiliation ciblés (Booking.com, Viator, etc.).
* 🛡️ **Système de TrustScore :** Évaluation algorithmique de la fiabilité des créateurs de voyages.

---

## 📱 Aperçu de l'Application

| 🏠 Accueil (Explorer) | 📍 Détails du Voyage | 🗺️ Itinéraire & Carte | ✍️ Création | 👤 Profil |
| :---: | :---: | :---: | :---: | :---: |
| ![Accueil](lien_image_1.png) | ![Détails](lien_image_2.png) | ![Carte](lien_image_3.png) | ![Création](lien_image_4.png) | ![Profil](lien_image_5.png) |

> *(Remplace les `lien_image_X.png` par les vraies URLs de tes captures d'écran).*

---

## 🛠️ Stack Technique & Architecture

### Mobile (Frontend)
* **Framework :** React Native (avec Expo)
* **Navigation :** React Navigation (Stack & Tabs)
* **UI/UX :** Expo Blur, Linear Gradient, Ionicons, Haptics natifs
* **Réseau :** Axios avec Intercepteurs JWT pour des requêtes sécurisées

### Serveur & Data (Backend)
* **API REST :** Node.js & Express.js
* **Base de données :** PostgreSQL (Modélisation relationnelle complexe des itinéraires et étapes)
* **ORM :** Prisma (Typage fort et migrations sécurisées)
* **Sécurité :** Auth JWT, Bcrypt, gestion fine des rôles (Créateurs, Voyageurs, Hôtes).

---

## 🧠 Défis Techniques Relevés

En tant que Lead Developer Fullstack sur ce projet, j'ai architecturé des solutions pour plusieurs défis majeurs :

1. **Performances Data (Le Remix) :** Concevoir une requête backend capable de dupliquer un arbre de données complet (Un voyage > Plusieurs Jours > Plusieurs Étapes) de manière transactionnelle et instantanée.
2. **Synchronisation d'État (Optimistic UI) :** Implémentation d'une interface réactive qui met à jour le visuel immédiatement lors des interactions (ex: "J'aime" un voyage) tout en gérant la persistance en arrière-plan.
3. **Cartographie Interactive :** Gestion fluide de multiples marqueurs GPS sur la carte avec React Native Maps sans saturer la mémoire du téléphone.

---

<div align="center">
  <p>💡 <i>Conçu et développé avec passion et rigueur par Amaury Lecoq.</i></p>
  <p><a href="mailto:ton_adresse_mail@email.com">Me contacter</a> • <a href="lien_vers_ton_linkedin">LinkedIn</a></p>
</div>
