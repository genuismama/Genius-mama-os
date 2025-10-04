# Genius Mama OS

**Plateforme bilingue (FR/EN)** pour mamans modernes : bien-être post-partum, suivi du bébé, organisation familiale, couple, budget et marketplace.  
Design haut de gamme (noir, beige, doré, bleu foncé) et expérience zen.

---

## 🎯 Objectif du projet
Créer une application web (PWA) intelligente et simple d’utilisation qui aide les mamans à :
- Se recentrer sur leur bien-être (Zen Mama)
- Suivre leur bébé (sommeil, alimentation, couches)
- Gérer les tâches familiales (Planning)
- Simplifier la gestion financière (Budget)
- Entretenir la complicité de couple (Mon Couple)
- Découvrir des produits utiles et responsables (Marketplace)

---

## ⚙️ Stack technique
- **Next.js** (App Router)  
- **TailwindCSS**  
- **Firebase Auth + Firestore**  
- **next-intl** (bilingue FR/EN)  
- **Vercel** pour le déploiement

---

## 📁 Structure du projet

/docs         → Vision produit, stories, roadmap
/app-spec     → Spécifications fonctionnelles et design
/models       → Schéma Firestore (base de données)
/dev          → Configuration et règles de sécurité
/prompts      → Instructions pour Devin AI

---

## 🚀 Démarrage du projet
```bash
# 1) Cloner le repo
git clone https://github.com/<ton-compte>/Genius-mama-os.git
cd Genius-mama-os

# 2) Créer le fichier .env.local
cp dev/env.example .env.local

# 3) Installer les dépendances
npm install

# 4) Lancer le serveur local
npm run dev


