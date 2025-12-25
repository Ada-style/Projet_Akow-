```markdown
# Market Attractiveness Score (MAS) pour Akowé – Priorisation des Marchés EdTech en Afrique Subsaharienne

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description du Projet

Ce repository contient l'ensemble du travail réalisé en équipe pour construire le **Market Attractiveness Score (MAS)**, un indice composite (0-100) permettant de prioriser les marchés EdTech en Afrique subsaharienne pour la startup **Akowé** (formations en ligne pour lycéens et universitaires).

Le MAS repose sur 4 sous-scores complémentaires :

| Sous-score                  | Poids | Objectif principal |
|-----------------------------|-------|---------------------|
| Scale Score (Taille du marché) | 35 % | Volume d'apprenants potentiels |
| Momentum Score (Dynamique de croissance) | 25 % | Vitesse de développement du marché |
| Ability to Pay Score (Capacité de paiement) | 25 % | Probabilité de monétisation |
| Digital Readiness Score (Faisabilité opérationnelle) | 15 % | Capacité à délivrer une offre en ligne |

## Structure du Repository

```
.
├── notebooks/                          # Notebooks Jupyter individuels
│   ├── 01_Scale_Score.ipynb            # Taille du marché (35%)
│   ├── 02_Momentum_Score.ipynb         # Dynamique de croissance (25%)
│   ├── 03_Ability_to_Pay_Score.ipynb   # Capacité de paiement (25%)
│   ├── 04_Digital_Readiness_Score.ipynb# Infrastructure & Qualité (15%)
│   └── 05_MAS_Final_Merge.ipynb        # Notebook final : merge + MAS + classement
├── data/                               # Données sources (facultatif, fichiers volumineux sur Drive)
├── reports/                            # Résultats finaux
│   ├── MAS_Classement_Final_2025.xlsx
│   ├── MAS_Classement_Final_2025.csv
├── docs/                               # Documentation
│  └── RAPPORT RESUME DU PROJET.Pdf
├── requirements.txt                    # Dépendances Python
└── README.md                           # Ce fichier
```

## Notebooks & Liens Colab  

Les notebooks ont été développés en équipe. Voici les liens directs :

- [01 - Scale Score (Taille du marché)](https://colab.research.google.com/drive/1ARiH5YMcXZa3bpVYsVcTVtDHzLQgaMoe?usp=sharing)
- [02 - Momentum Score (Croissance)](https://colab.research.google.com/drive/16gWFxOUtqQ2YeOCP3SnHEvnxi1768LBp?usp=sharing)
- [03 - Ability to Pay Score (Capacité de paiement)](https://colab.research.google.com/drive/14BE7YOD6KXPS1-xQ4Mf5r3zU2w8Ri2Sq?usp=sharing)
- [04 - Digital Readiness Score (Infrastructure & Qualité)](https://colab.research.google.com/drive/1mtS7ESWLM9Y_jr6lpKm8ePPHUGch3jc2?usp=sharing)
- [05 - MAS Final : Merge & Classement Définitif](https://colab.research.google.com/drive/12yVgeiFMbnXApqm2qmHe3K3vA8MACso7?usp=sharing)

## Résultat Final

Le notebook final (`05_MAS_Final.ipynb`) produit :

- Le **Market Attractiveness Score (MAS)** global pour les 48 pays d'Afrique subsaharienne
- Un classement trié avec noms de pays, codes ISO, sous-scores et segment opérationnel (Priorité 1, 2, 3)
 


## Installation & Exécution

```bash
# Cloner le repo
git clone https://github.com/Ada-style/Projet_Akowé.git
cd mas-edtech-afrique

# Installer les dépendances
pip install -r requirements.txt

# Lancer le notebook final
Colab notebook notebooks/[05_MAS_Final_Merge.ipynb](https://colab.research.google.com/drive/12yVgeiFMbnXApqm2qmHe3K3vA8MACso7?usp=sharing)
```

## Équipe & Contributions

Projet réalisé en équipe :
- Préparation des données, filtrage et nettoyage : **travail collectif**
- Étude du Scale Score : [ADOSSI Prunelle]
- Étude du Momentum Score : [Charles]
- Étude de l'Ability to Pay Score : [MESSAN Jean]
- Étude du Digital Readiness Score : [TEKOLO Christian]
- Merge final et MAS : [ADOSSI Prunelle]

## Documentation Complémentaire
- [Rapport résumé (PDF)](https://drive.google.com/file/d/1eKjhF_8CY1nqPwWmO94Mv_t4nJAxSQQN/view?usp=drive_link)

 
 tement en valeur le travail d’équipe et le résultat final. Ton repo GitHub va faire pro ! 🚀

Si tu veux une version plus courte ou avec badge GitHub Actions, dis-moi.
