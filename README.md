# 📊 Repositionnement d'un e-commerce : mesure de l'impact sur la performance

![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyBmaWxsPSIjZmZmZmZmIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TWljcm9zb2Z0IEV4Y2VsPC90aXRsZT48cGF0aCBkPSJNMjMgMS41cS40MSAwIC43LjMuMy4yOS4zLjd2MTlxMCAuNDEtLjMuNy0uMjkuMy0uNy4zSDdxLS40MSAwLS43LS4zLS4zLS4yOS0uMy0uN1YxOEgxcS0uNDEgMC0uNy0uMy0uMy0uMjktLjMtLjdWN3EwLS40MS4zLS43US41OCA2IDEgNmg1VjIuNXEwLS40MS4zLS43LjI5LS4zLjctLjN6TTYgMTMuMjhsMS40MiAyLjY2aDIuMTRsLTIuMzgtMy44NyAyLjM0LTMuOEg3LjQ2bC0xLjMgMi40LS4wNS4wOC0uMDQuMDktLjY0LTEuMjgtLjY2LTEuMjlIMi41OWwyLjI3IDMuODItMi40OCAzLjg1aDIuMTZ6TTE0LjI1IDIxdi0zSDcuNXYzem0wLTQuNXYtMy43NUgxMnYzLjc1em0wLTUuMjVWNy41SDEydjMuNzV6bTAtNS4yNVYzSDcuNXYzem04LjI1IDE1di0zaC02Ljc1djN6bTAtNC41di0zLjc1aC02Ljc1djMuNzV6bTAtNS4yNVY3LjVoLTYuNzV2My43NXptMC01LjI1VjNoLTYuNzV2M1oiLz48L3N2Zz4=)
![Power%20Point](https://img.shields.io/badge/PowerPoint-B7472A?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyBmaWxsPSIjZmZmZmZmIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TWljcm9zb2Z0IFBvd2VyUG9pbnQ8L3RpdGxlPjxwYXRoIGQ9Ik0xMy41IDEuNXExLjQ1MyAwIDIuNzk1LjM3NSAxLjM0Mi4zNzUgMi41MDggMS4wNiAxLjE2Ni42ODYgMi4xMiAxLjY0MS45NTYuOTU1IDEuNjQxIDIuMTIxLjY4NiAxLjE2NiAxLjA2MSAyLjUwOFEyNCAxMC41NDcgMjQgMTJxMCAxLjQ1My0uMzc1IDIuNzk1LS4zNzUgMS4zNDItMS4wNiAyLjUwOC0uNjg2IDEuMTY2LTEuNjQxIDIuMTItLjk1NS45NTYtMi4xMjEgMS42NDEtMS4xNjYuNjg2LTIuNTA4IDEuMDYxLTEuMzQyLjM3NS0yLjc5NS4zNzUtMS4yOSAwLTIuNTItLjMwNS0xLjIzLS4zMDQtMi4zMzctLjg4NC0xLjEwOC0uNTgtMi4wNjMtMS40MTgtLjk1NS0uODM4LTEuNjkzLTEuODkzSC45OTdxLS40MTEgMC0uNzA0LS4yOTNUMCAxNy4wMDRWNi45OTZxMC0uNDEuMjkzLS43MDNULjk5NiA2aDMuODlxLjczOS0xLjA1NSAxLjY5NC0xLjg5My45NTUtLjgzNyAyLjA2My0xLjQxOCAxLjEwNy0uNTggMi4zMzctLjg4NFExMi4yMSAxLjUgMTMuNSAxLjV6bS43NSAxLjUzNXY4LjIxNWg4LjIxNXEtLjE0LTEuNjQtLjgyNi0zLjA3Ni0uNjg2LTEuNDM2LTEuNzgyLTIuNTMxLTEuMDk1LTEuMDk2LTIuNTM3LTEuNzgyLTEuNDQxLS42ODUtMy4wNy0uODI2em0tNS4yNjIgNy41N3EwLS42OC0uMjI4LTEuMTY2LS4yMjktLjQ4Ni0uNjI3LS43OS0uMzk5LS4zMDUtLjkzOC0uNDQ2LS41MzktLjE0LTEuMTcyLS4xNEgyLjg0OHY3Ljg2M2gxLjg0di0yLjc0Mkg1LjkzcS41NzQgMCAxLjExOS0uMTd0Ljk3OC0uNDkzcS40MzQtLjMyMi42OTgtLjgwMi4yNjMtLjQ4LjI2My0xLjExNHpNMTMuNSAyMXExLjE3MiAwIDIuMjYyLS4yODd0Mi4wNTYtLjgycS45NjctLjUzNCAxLjc3Ni0xLjI3OC44MDgtLjc0NCAxLjQxOC0xLjY2NC42MS0uOTIuOTg0LTEuOTg2LjM3NS0xLjA2Ny40NjktMi4yMjdoLTkuNzAzVjMuMDM1cS0xLjczNS4xNC0zLjI3LjkwOFQ2Ljc5NyA2aDQuMjA3cS40MSAwIC43MDMuMjkzdC4yOTMuNzAzdjEwLjAwOHEwIC40MS0uMjkzLjcwM3QtLjcwMy4yOTNINi43OTdxLjY0NC43MTUgMS40MTIgMS4yNzEuNzY4LjU1NyAxLjYyMy45NDQuODU1LjM4NyAxLjc4MS41ODZRMTIuNTQgMjEgMTMuNSAyMXpNNS44MTIgOS41OThxLjU3NSAwIC45MTUuMjI4LjM0LjIyOS4zNC44MzggMCAuMjctLjEyNC40NC0uMTIzLjE3LS4zMS4yNzUtLjE4OC4xMDUtLjQyMi4xNDYtLjIzNC4wNDEtLjQ0NS4wNDFINC42ODdWOS41OThaIi8+PC9zdmc+)
![KPIs](https://img.shields.io/badge/KPIs_E--commerce-6366f1?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=flat-square)

Un site e-commerce arrête le High-Tech pour se concentrer sur l'alimentaire. Mon analyse montre que le pari est payant sur l'audience : **trafic multiplié par 30, et une conversion à 5 %, quand la moyenne du e-commerce tourne autour de 3 %.** Elle débouche sur une double stratégie présentée à la direction.

---

## 📖 Le problème

**Le Grand Marché** vient de changer de cap : le High-Tech a disparu de son catalogue, l'alimentaire devient son moteur. La direction veut savoir si ce choix tient la route, et comment faire grimper le chiffre d'affaires maintenant que le panier est plus petit.

---

## 🛠️ Ma solution

1. **Un rapport mensuel pour la direction** : les indicateurs clés du changement de cap, présentés à un décideur non technique
2. **Un tableau de bord Excel des clients affiliés** : chiffre d'affaires, nombre d'achats et panier moyen par mois et par client, avec ses graphiques

---

## 🔍 Ce que montrent les données

### 1️⃣ Une audience multipliée par 30

Les visites mensuelles passent d'environ **20 000 à 550 000** en un an. Les ventes progressent aussi : le site est devenu une destination pour les courses du quotidien.

### 2️⃣ Une conversion toujours au-dessus du marché

Le taux de conversion passe de **11 % à 5 %**, parce que les visites augmentent plus vite que les ventes. Mais **5 % reste très bon** : la moyenne du e-commerce se situe autour de 3 %. Le site convainc presque deux fois mieux que la concurrence.

### 3️⃣ Le temps passé fait le panier

Plus un client prend le temps de découvrir les produits, plus son panier s'alourdit. Les acheteurs passent **entre 6 et 8 minutes** sur le site, pour une commande moyenne de **40 €**, et la grande majorité du chiffre d'affaires se fait sur des paniers **entre 30 et 50 €**.

### 4️⃣ Deux profils de clients qui s'éloignent

Mois après mois, l'écart se creuse entre deux façons d'acheter :
- **les clients rapides**, qui achètent en 4 minutes environ
- **les explorateurs**, qui prennent une dizaine de minutes pour découvrir

---

## 💡 Ma recommandation

Une **double stratégie**, une voie pour chaque profil :

- **Une voie rapide**, de type abonnement, pour sécuriser les achats récurrents des clients pressés
- **Une voie inspiration**, avec des recettes et des suggestions, pour faire grimper le panier des explorateurs

---

## 📂 Structure du projet

```
analyse-ventes-ecommerce/
├── README.md
└── docs/
    ├── presentation_rapport_mensuel.pptx    # le rapport présenté à la direction
    └── tableau_bord_clients_affilies.xlsx   # le tableau de bord des clients affiliés
```

---

## 🛠️ Technologies

- **Excel** : tableaux croisés dynamiques, formules, graphiques
- **PowerPoint** : rapport pour la direction et data storytelling

---

## 📈 Compétences démontrées

- ✅ Lecture des indicateurs e-commerce : trafic, conversion, panier moyen, temps passé
- ✅ Segmentation des clients selon leur comportement d'achat
- ✅ Recommandation stratégique présentée à un décideur non technique
- ✅ Tableau de bord Excel avec ses formules conservées

---

## 📧 Contact

**Helton Dos Santos Moreira**
Data Analyst | 10 ans d'expérience business (retail et e-commerce)

- 📧 Email : heltonmail8@gmail.com
- 💼 LinkedIn : [in/helton-dsm-data](https://linkedin.com/in/helton-dsm-data)
- 🐙 GitHub : [Heltondsm](https://github.com/Heltondsm)
- 🌐 Portfolio : [heltondsm.github.io](https://heltondsm.github.io/)

---

## 🔗 Autres projets

- [Pilotage financier d'une PME : trésorerie, impayés et comparaison au secteur](https://github.com/Heltondsm/pilotage-financier-pme), Airflow, dbt, BigQuery et Power BI, prévision de trésorerie à 4,8 % du réel à 30 jours, 72 contrôles dbt
- [CRM data et agents IA : centraliser opportunités, contacts et échanges](https://github.com/Heltondsm/crm-data-agents-ia), PostgreSQL alimenté par des API, collecte Python planifiée, opportunités notées par IA, testé automatiquement à chaque push
- [Étude de marché par clustering : choisir les pays où exporter de la volaille bio](https://github.com/Heltondsm/python-etude-marche-clustering-pays), ACP, CAH et k-means sur 170 pays, 4 familles, 3 marchés prioritaires
- [Tableau de bord Power BI : portefeuille de projets](https://github.com/Heltondsm/powerbi-portefeuille-projets-rls), 104 projets dans 52 pays, sécurité au niveau des lignes sur 3 rôles, 25 mesures DAX
- [Audit données catalogue : e-commerce vins](https://github.com/Heltondsm/python-audit-donnees-catalogue), 3 sources réconciliées, 9 anomalies, 276 859 € de stock valorisé
- [Tendances du streaming musical](https://github.com/Heltondsm/analyse-streaming-musical), 114 000 morceaux, tests statistiques et calendrier de sortie

---

**Projet réalisé en janvier 2026**
