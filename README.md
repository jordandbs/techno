# 📋 Plan EC11 – Rapport de Veille Multilingue · SkillHub 

## 🟦 BLOC 1 – Objectifs SMART + Horizons 

### Exemple concret 
 **Objectif SMART :**  
> Identifier, d'ici le 30/06/2025, **3 frameworks JavaScript** (React/Vue/Svelte) adaptés au développement de parcours d'apprentissage interactifs pour SkillHub, en consultant 5 sources techniques FR + EN, avec une session de veille hebdomadaire de 30 min, afin d'orienter le choix technologique front-end du sprint 3.

| Horizon | Délai | Exemple SkillHub |
|---------|-------|------------------|
| **H1** | 0–3 mois | Choisir un framework front-end pour les modules de formation SkillHub |
| **H2** | 3–12 mois | Intégrer une IA de recommandation de compétences (type LLM embeddings) |
| **H3** | 12–36 mois | SkillHub devient une plateforme autonome de mentorat IA inter-entreprises |

---

## 🟦 BLOC 2 – Sélection des Sources + Outils (15 min)

Une liste commentée de tes sources **FR + EN** et les outils que tu utilises.

### Exemple de sources pour SkillHub

| Source | Langue | Domaine | Crédibilité |
|--------|--------|---------|-------------|
| MDN Web Docs | EN | APIs REST / JS | ⭐⭐⭐⭐⭐ |
| Dev.to | EN | Frameworks front | ⭐⭐⭐⭐ |
| Techniques de l'Ingénieur | FR | Architecture SI | ⭐⭐⭐⭐⭐ |
| CSS-Tricks / Smashing Mag | EN | UI/UX Formation | ⭐⭐⭐⭐ |
| GitHub Trending | EN | Libs open source | ⭐⭐⭐ |
| IEEE Xplore | EN | IA / ML | ⭐⭐⭐⭐⭐ |
| Le Monde Informatique | FR | Actualités tech | ⭐⭐⭐⭐ |

### Outils choisis

| Rôle | Outil | Justification |
|------|-------|---------------|
| Collecte | Feedly / Google Alerts | Agrégation flux RSS + alertes mots-clés |
| Analyse | Notion + IA (Claude) | Centralisation + résumés automatiques |
| Visualisation | Tableau / Power BI | Dashboard KPIs |
| Organisation | Notion Database | Base de connaissances consultable |

---

## 🟦 BLOC 3 – QMS / KPIs (25 min) ← Le plus important pour la note

> C'est ici que se jouent les points C37. Fais **4 tableaux KPI**, un par dimension.

### QMS 1 – Pertinence de la veille

| KPI | Définition SMART | Mesure | SLA (action si KPI < seuil) |
|-----|-----------------|--------|-----------------------------|
| **Relevance Rate (RR-KPI)** | % d'articles collectés directement applicables à SkillHub / sprint en cours | ≥ 60% des articles collectés sont taggés "applicable" dans Notion | Si RR < 60% → réviser les mots-clés de recherche sous 48h |
| **Coverage KPI** | Nombre de domaines tech couverts (front, back, API, IA, UX) | ≥ 4 domaines couverts par session | Si < 4 → ajouter 1 flux RSS manquant |

**Exemple de formule composite :**
```
Pertinence Score = 50% × RR-KPI + 50% × Coverage-KPI
Cible : ≥ 65/100
```

---

### QMS 2 – Qualité des sources

| KPI | Définition SMART | Mesure |
|-----|-----------------|--------|
| **AE-KPI** (Author Expertise) | % d'auteurs avec profil vérifié (GitHub, LinkedIn, PhD) | ≥ 70% des sources ont un auteur identifiable |
| **IR-KPI** (Institution Reputation) | Score moyen de réputation (IEEE=5, blog=2, forum=1) | Moyenne ≥ 3/5 |
| **PR-KPI** (Peer Review) | % d'articles issus de sources éditorialisées | ≥ 40% |

**Formule qualité source :**
```
Quality Score = 30% × AE-KPI + 40% × IR-KPI + 30% × PR-KPI
Cible : ≥ 70/100
```

**SLA :** Si Quality Score < 70 → supprimer la source et la remplacer sous 1 semaine.

---

### QMS 3 – Intérêt (signaux faibles)

| KPI | Définition SMART | Mesure |
|-----|-----------------|--------|
| **Weak Signal Count (WS-KPI)** | Nombre de signaux faibles détectés par session (technos émergentes, tendances non mainstream) | ≥ 2 signaux faibles par session mensuelle |
| **Signal Novelty Score** | % de signaux non déjà présents dans la base de connaissances | ≥ 80% |

**Exemple de signal faible SkillHub :**  
> Article détecté sur Dev.to : "Skills graph with vector embeddings" → Potentiel H2 pour SkillHub (recommandation de mentors par similarité vectorielle).

---

### QMS 4 – Utilité (transformation en actions)

| KPI | Définition SMART | Mesure |
|-----|-----------------|--------|
| **Usage Rate (UR-KPI)** | % d'informations collectées ayant généré une décision/action dans le projet | ≥ 30% des infos collectées → ticket Jira ou décision de sprint |
| **Time to Action (TTA-KPI)** | Délai moyen entre collecte d'une info et son utilisation dans le projet | ≤ 2 sprints (4 semaines) |

**SLA :** Si UR < 30% → revoir la fréquence de partage avec l'équipe (hebdo standup dédié).

---

## 🟦 BLOC 4 – Collecte réelle + Analyse (20 min)

### Ce que tu dois produire (Cr36.1 + Cr36.3 + Cr38.3)

Présente **5 à 8 articles/sources réelles** que tu as consultées, avec une analyse courte.

### Exemple de tableau de collecte SkillHub

| # | Source | Titre (résumé) | Langue | Date | Signal | Applicable à SkillHub ? |
|---|--------|---------------|--------|------|--------|------------------------|
| 1 | Dev.to | "Building a skill tree with React Flow" | EN | Mai 2025 | 💡 Fort | Oui – module parcours d'apprentissage |
| 2 | MDN | "Web Workers for background tasks" | EN | 2024 | Normal | Oui – performance API SkillHub |
| 3 | Le Monde Info | "L'IA générative dans la RH en 2025" | FR | Avr. 2025 | 💡 Fort | Oui – recommandation compétences H2 |
| 4 | IEEE Xplore | "Graph-based competency modeling" | EN | 2024 | 💡 Faible | Potentiel H3 |
| 5 | CSS-Tricks | "Modern CSS for dashboards" | EN | 2025 | Normal | Oui – dashboard formateurs |

### Analyse comparative (Cr38.3)

> **Tendance identifiée :** Les sources EN et FR convergent vers une **approche graph/réseau** pour modéliser les compétences (React Flow, graph DB, vector embeddings). Cette tendance est cohérente avec l'axe H2 de SkillHub (recommandation intelligente).  
> **Divergence notable :** Les sources FR restent centrées sur la conformité RGPD des données RH, là où les sources EN explorent davantage les LLM appliqués aux skills.

---

## 🟦 BLOC 5 – Base de Connaissances (10 min)

### Structure à décrire (Cr37.3 + Cr38.1)

Décris comment tu organises tes infos. Une capture ou un schéma simple suffit.

```
📁 SkillHub – Base de veille (Notion)
├── 🏷️ Sources validées (Quality Score ≥ 70)
│   ├── Front-end (React, Vue, Svelte)
│   ├── Back-end / API (Node, Symfony, REST)
│   ├── IA / ML (LLM, embeddings, recommendation)
│   └── UX / Accessibilité
├── 📌 Signaux faibles (archivés par date)
├── 📊 Dashboard KPIs (hebdo)
└── 🗂️ Historique sessions (log date + métriques)
```

**Critères de vérification fake news / cross-check :**
- Source recoupée sur ≥ 2 médias indépendants
- Auteur identifiable avec historique public
- Date de publication < 18 mois (sauf référence fondamentale)
- Pas de conflit d'intérêt éditorial évident

---

## 🟦 BLOC 6 – Scénarios H3 (15 min)

### Ce que tu dois écrire (Cr38.2)

2 scénarios pour l'évolution de SkillHub à 2-3 ans, sous hypothèses.

---

**Scénario A – "SkillHub IA-First"**  
*Hypothèse : Les LLM deviennent accessibles et conformes RGPD en entreprise d'ici 2027.*

SkillHub intègre un moteur de recommandation LLM qui suggère automatiquement mentors et formations selon le profil vectoriel de chaque collaborateur.

| Inconnue à lever | Méthode |
|-----------------|---------|
| Coût API LLM en production | Benchmark (OpenAI vs Mistral vs Ollama on-premise) |
| Conformité RGPD des embeddings | Consultation CNIL + DPO Asteria |
| Adoption utilisateurs | Test UX sur 10 collaborateurs beta |

---

**Scénario B – "SkillHub Marketplace"**  
*Hypothèse : Asteria Group ouvre SkillHub à des partenaires externes (cabinets de formation, freelances).*

SkillHub devient une marketplace de compétences inter-entreprises avec API publique et système de notation des mentors.

| Inconnue à lever | Méthode |
|-----------------|---------|
| Modèle économique (freemium/SaaS) | Étude marché + benchmarks Docebo, 360Learning |
| Sécurité multi-tenant | POC architecture micro-services |
| Contrats partenaires | Service juridique |

**Scénario retenu : A** (plus réaliste à 2 ans, dépendances moindres)

---
technology scouting
