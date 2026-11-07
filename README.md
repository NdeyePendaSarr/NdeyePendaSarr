# Ndeye Penda SARR

### Data Engineer · Développeuse Full Stack junior

Étudiante en **Master 2 Business Intelligence** (Université Cheikh Anta Diop) et en formation **Développement Data** à l'Orange Digital Center, lauréate du **2e prix du Force-N Innovation Challenge 2026**.

Je construis des chaînes de données, de l'ingestion jusqu'au tableau de bord, et des applications web complètes : interfaces React / Next.js en TypeScript, API, bases PostgreSQL, tests et CI. Je recherche un **stage ou un premier poste en Data Engineering, en BI ou en développement full stack**.

Je construis des chaînes de données, de l'ingestion jusqu'au tableau de bord, et je m'appuie sur mon parcours de développeuse pour concevoir les API et les interfaces qui rendent ces données utiles. Je recherche un **stage en Data Engineering ou en BI**.

📍 Dakar, Sénégal · [LinkedIn](https://www.linkedin.com/in/ndeyependasarr)

---

## 📊 Projets data

### [Nataal Retail](https://github.com/rassoul01-byte/Yakaarou_Diaykaat_BI) — plateforme data pour un e-commerçant
Projet d'équipe, Orange Digital Center · **contributrice principale** (143 commits sur 236, hors fusions)
- Traitements par lots et en flux : Kafka, catalogue MongoDB indexé dans Elasticsearch, DAG Airflow de supervision.
- Qualité des données (taux de rejet, quarantaine) et entrepôt PostgreSQL en étoile avec SCD 2 ; 948 tests, CI.
- Modèle de ré-achat à 180 jours (scikit-learn, 4 algorithmes comparés) et tableau de bord Power BI des ventes.

`Python` `Kafka` `Airflow` `PostgreSQL` `MongoDB` `Elasticsearch` `scikit-learn` `Power BI` `Docker`

### [EduSmart Decision Platform](https://github.com/NdeyePendaSarr/edusmart-decision-platform) — plateforme BI de bout en bout
Projet individuel, Orange Digital Center
- Pipeline ELT depuis 5 sources (PostgreSQL, MySQL, CSV, MongoDB, Redis) vers un entrepôt en constellation : 8 faits, SCD 2.
- Portes de qualité de G0 à G6 : 159 946 anomalies détectées et tracées ; 372 tests Pytest.
- KPI et tableau de bord Power BI (Power Query, DAX), environnement Docker.

`Python` `SQL` `ELT` `Data Warehouse` `Data Quality` `Power BI` `Docker`

### [Student Data Pipeline](https://github.com/NdeyePendaSarr/student-data-pipeline) — ingestion et réconciliation de données
Projet individuel, Orange Digital Center
- Ingestion JSON → PostgreSQL idempotente : validation Pydantic, quarantaine motivée, journal des imports.
- Réconciliation de deux sources sans doublon ; API FastAPI, interface React, 41 tests Pytest.

`Python` `FastAPI` `Pydantic` `PostgreSQL` `Pytest` `React`

---

## 💻 Applications full stack

### [Cotiz](https://github.com/NdeyePendaSarr/cotiz-app-public) — trésorerie de tontines et de collectes
Projet personnel, conçu pour mon propre usage de trésorière (famille, tontines, collectes)
- Application web mobile-first : saisie des paiements Wave, Orange Money et espèces, rapprochement du soir, relances WhatsApp.
- Next.js 16 (Server Actions), React 19, TypeScript, Prisma, PostgreSQL (Supabase) avec RLS.
- 544 tests unitaires et 75 tests d'intégration en CI.

`Next.js` `React` `TypeScript` `Prisma` `PostgreSQL` `Supabase`

### [Teranga Table](https://github.com/NdeyePendaSarr/teranga-table) — réservation de restaurant
Projet personnel, restaurant fictif · [Démo](https://teranga-table.vercel.app)
- API REST sur Node.js (routes Next.js), validation zod partagée, PostgreSQL (Neon, Drizzle).
- Admin protégé par cookie JWT signé (middleware + vérification par route), limitation de débit par IP, honeypot, e-mails Brevo échappés.
- 29 tests Vitest, CI.

`Next.js` `Node.js` `TypeScript` `PostgreSQL` `Drizzle` `zod` `Vitest`

### [FocusDay](https://github.com/NdeyePendaSarr/focus-day) — carnet d'apprentissage
Projet personnel · [Démo](https://focus-day-nps.vercel.app) · en production depuis le 31 août 2026 (116 séances, 271 h sur 10 parcours, sur mon seul compte)
- Supabase / PostgreSQL avec RLS, migrations versionnées.
- Mises à jour optimistes avec restauration en cas d'échec.
- Next.js 16, React 19, TypeScript ; 109 tests Vitest, CI.

`Next.js` `React` `TypeScript` `Supabase` `PostgreSQL` `Vitest`

### [PharmaNPS](https://github.com/NdeyePendaSarr/pharmacy-management) — gestion de pharmacie
Projet personnel · [Démo](https://pharmanps-aloucoding-b8ex.onrender.com/) (compte de démonstration dans le README du dépôt)
- Rôles Pharmacien et Vendeur, prix recalculés côté serveur.
- Ventes concurrentes sans survente : transactions et verrous.
- 83 tests, CI.

`Django` `Python` `PostgreSQL` `GitHub Actions`

### Autres projets web

| Projet | En bref | Stack | Démo |
|---|---|---|---|
| [**Daba Glow**](https://github.com/NdeyePendaSarr/daba-glow) | Site vitrine pour une activité de beauté à domicile (mission freelance) | Next.js · Tailwind | [Ouvrir](https://daba-glow.vercel.app/) |
| [**Bourse Hub**](https://github.com/NdeyePendaSarr/bourse-hub) | Annuaire de bourses d'études pour étudiants sénégalais | JavaScript | [Ouvrir](https://ndeyependasarr.github.io/bourse-hub/) |
| [**AgenceImmo**](https://github.com/NdeyePendaSarr/real-estate-management) | Gestion immobilière, projet de Licence repensé (MVC, rôles, sécurité) | PHP · MySQL | [Ouvrir](https://agence-immo.42web.io/) |

🏆 **CashBrain**, 2e prix du Force-N Innovation Challenge 2026 : application mobile de recouvrement pour commerçants (React Native, SQLite hors ligne, saisie vocale), développée en équipe.

---

## 🛠️ Compétences

| Domaine | Outils |
|---|---|
| Data Engineering | Python · SQL · ETL / ELT · Kafka · Airflow · Docker · qualité des données |
| Bases de données | PostgreSQL · MySQL · MongoDB · Redis · Elasticsearch |
| BI | Power BI · Power Query · DAX · Excel · modélisation dimensionnelle (étoile, constellation, SCD 2) |
| Développement | FastAPI · Pydantic · Django · React · Next.js · TypeScript · React Native |
| Qualité logicielle | Pytest · Vitest · GitHub Actions · Git |

---

## 🎓 Parcours

- **Master 2 Business Intelligence** — Université Cheikh Anta Diop (en cours)
- **Développement Data, parcours Data Engineer** — Orange Digital Center (2026)
- **Master 1 Systèmes d'information répartis** — Université Cheikh Anta Diop
- **Licence Informatique** — Université Cheikh Anta Diop
