# Spécifications fonctionnelles (MVP)

## Stack
- Next.js (App Router)
- TailwindCSS
- Firebase Auth + Firestore
- next-intl (bilingue FR/EN)

## Modules
1. **Zen Mama** – humeur (1–5), note, historique  
2. **Mon Bébé** – sommeil, alimentation, couches  
3. **Planning** – tâches familiales  
4. **Budget** – dépenses simples  
5. **Mon Couple** – à venir  
6. **Marketplace** – à venir

## Flux utilisateur
1. Auth → Onboarding (langue) → Dashboard  
2. Sélection d’un module → ajout rapide → sauvegarde Firestore  
3. Retour au dashboard

## Critères d’acceptation
- CRUD fonctionnel (Zen, Bébé, Planning, Budget)  
- i18n complet  
- Auth e-mail + Google  
- Sécurité Firestore conforme
