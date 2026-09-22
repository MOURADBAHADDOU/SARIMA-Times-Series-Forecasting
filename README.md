# 📈 SARIMA - Time Series Forecasting

## 🥛 Modélisation SARIMA pour la prévision de la production laitière

Ce projet met en œuvre un modèle **SARIMA (Seasonal AutoRegressive Integrated Moving Average)** afin de prévoir la **production mensuelle de lait** à partir de données historiques couvrant la période **1962–1975**.

L'objectif est d'analyser les principales caractéristiques de la série temporelle — **tendance, saisonnalité et fluctuations** — puis de construire un modèle capable de produire des prévisions fiables pour les périodes futures.

---

## 🎯 Objectif

L'objectif principal de ce projet est de :

- analyser l'évolution de la production mensuelle de lait ;
- identifier la **tendance** et la **saisonnalité** de la série ;
- vérifier la stationnarité de la série temporelle ;
- appliquer les transformations nécessaires pour obtenir une série stationnaire ;
- identifier les paramètres appropriés du modèle SARIMA à l'aide des analyses **ACF/PACF** ;
- entraîner un modèle SARIMA ;
- évaluer ses performances sur un ensemble de test ;
- analyser les résidus afin de vérifier la qualité du modèle ;
- générer des prévisions de production future.

---

## 📊 Données utilisées

Le jeu de données contient la **production mensuelle de lait** entre **janvier 1962 et décembre 1975**.

### Source

Les données sont fournies dans le fichier :

```text
monthly-milk-production(2).csv
