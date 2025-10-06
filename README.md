# Genius Mama OS

**Plateforme bilingue (FR/EN)** pour mamans modernes : bien-être post-partum, suivi du bébé, organisation familiale, couple, budget et marketplace.  
Design haut de gamme (noir, beige, doré, bleu foncé) et expérience zen.

---

## 🎯 Objectif
Créer une application web (PWA) intelligente et simple qui aide les mamans à :
- Se recentrer sur leur bien-être (**Zen Mama**)
- Suivre leur bébé (sommeil, alimentation, couches) (**Mon Bébé**)
- Gérer les tâches familiales (**Planning**)
- Simplifier la gestion financière (**Budget**)
- Entretenir la complicité de couple (**Mon Couple**)
- Découvrir des produits utiles et responsables (**Marketplace**)

---

## ⚙️ Stack technique
- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS + shadcn/ui**
- **next-intl (FR/EN)**
- **Firebase Auth + Firestore**
- **Déploiement : Vercel**

---

## 📁 Structure

/docs → Vision produit, user stories, roadmap  
/app-spec → Spécifications fonctionnelles et design  
/models → Schéma Firestore (base de données)  
/dev → Config & règles de sécurité  
/prompts → Instructions IA de développement (ex.: Devin)  
/web → (créé lors du bootstrap Next.js) code de l’app  

---

## 🚀 Démarrage (local)
```bash
# À la racine du repo
npx create-next-app@latest web --typescript --eslint --tailwind --app --src-dir --import-alias "@/*" --use-npm
cd web
npm install
npm run dev


🔐 Sécurité Firestore (à venir)
Les règles (ex.: dev/firebase.rules) empêcheront tout accès croisé entre utilisateurs :
chaque compte lit/écrit uniquement ses propres données (users/{uid}/...).

🌎 Internationalisation
Toutes les chaînes seront gérées via next-intl, avec support complet FR/EN.

🗺️ Roadmap (extrait)
Semaine 1 → Auth + i18n + Dashboard
Semaine 2 → Zen Mama + Mon Bébé
Semaine 3 → Planning + Budget
Semaine 4 → UI finale + Déploiement Vercel

👩‍💻 Auteure
Cynthia Després — Fondatrice de Genius Mama OS
📧 cynthiadespres@hotmail.com — 📍 Québec, Canada
“Créer un univers où chaque maman retrouve équilibre, clarté et puissance intérieure.” 💫

Notes
Ce dépôt contient la vision et les spécifications.
Le code applicatif vit dans /web (Next.js).
Les modules principaux : Zen Mama, Mon Bébé, Planning, Mon Couple, Budget, Marketplace.

(Option) Mettre en place l’UI premium
Depuis /web :npx shadcn-ui@latest init -y
npm i class-variance-authority tailwind-merge lucide-react zustand zod date-fns next-intl

(Option) Déploiement Vercel
Connecter le repo à Vercel
Ajouter les variables d’env (Firebase, i18n)
Déployer la branche main

---

### ✅ En résumé
✔️ Ton texte est juste  
✔️ Ton contenu est complet  
✔️ Et ta structure est déjà au niveau d’un **projet tech bien monté**

---

Souhaites-tu que je t’aide maintenant à :
> créer la base Next.js (`/web`) et le **menu principal avec les 6 modules** dans ton app Genius Mama OS ?  
(on peut tout générer automatiquement en 1 commande)


