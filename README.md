# Modelovanie dĺžky hospitalizácie podľa náročnosti ochorenia a komplexnosti liečby COVID-19
#### **Autor:** Andrea Nguyen
#### **Rok:** 2026

Cieľom tejto diplomovej práce bolo modelovanie dĺžky hospitalizácie použitím dát z Košickej nemocnice. Zahŕňa porovnanie metód pre ošetrenie chýbajúcich hodnôt, techník riešenia nerovnováhy tried a rôznych verzii modelovania.

Jupyter notebook `modelovanie_LOS.ipynb` obsahuje proces od pochopenia a spracovania dát, cez modelovanie až po vyhodnotenie modelov.

## Štruktúra projektu
- `modelovanie_LOS.ipynb`
- `data/`
- `requirements.txt`

## Dáta
Dáta nie sú verejne dostupné.

## Technológie
- Python
- Pandas, NumPy, Seaborn
- Scikit-learn
- CatBoost
- Imbalanced-learn
- SHAP

## Ako spustiť projekt

1. Inštalácia závislostí:

```bash
pip install -r requirements.txt
```

2. Spustenie `modelovanie_LOS.ipynb`