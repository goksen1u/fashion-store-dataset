# fashion-store-dataset
Ce dépôt contient les données brutes d’une boutique de mode en ligne utilisées dans le cadre d’analyses marketing et de visualisations de ventes. Les fichiers couvrent différents aspects de l’activité : ventes, clients, produits, campagnes publicitaires, stocks, et canaux de vente.

## 📁 Données utilisées
- `sales.csv`, `sales_items.csv`, `products.csv`, `customers.csv`, `stock.csv`
- Fusion intelligente via `sale_id`, `product_id`, `customer_id`

## 🛠️ Traitement
- Nettoyage, fusion sans doublons
- Calcul de KPI : `revenue`, `profit`, `margin_%`, etc.
- Export vers Power BI pour visualisation

## 🧰 Outils utilisés
- Python (Pandas)
- Jupyter Notebook
- Power BI

## 📄 Fichier principal
- `Fashion_store_préparation_donnees_v2.ipynb`

## 📈 Visualisation
Les données nettoyées sont prêtes à être explorées dans Power BI via `ecommerce_cleaned_final.xlsx`.
