# 🧹 Traçabilité Sanitaires RUCK HOTEL - GSF Mercure

## Description

Cette application permet d'enregistrer les passages dans les sanitaires et vestiaires via un simple scan de QR Code.

L'objectif est de garantir la traçabilité des interventions tout en conservant un processus simple et rapide pour les agents.

Aucun compte Microsoft ou GSF n'est nécessaire.

---

## Fonctionnement

1. Un QR Code est affiché dans chaque sanitaire.
2. L'agent scanne le QR Code avec son téléphone personnel.
3. La page web s'ouvre automatiquement.
4. Le passage est enregistré.
5. Un message de confirmation s'affiche.

Temps d'utilisation : moins de 2 secondes.

---

## Sanitaires suivis

| Code | Emplacement |
|--------|-------------|
| SAN001 | Sanitaires hommes |
| SAN002 | Sanitaires femmes |
| SAN003 | Sanitaires PMR 1 |
| SAN004 | Sanitaires PMR 2 |
| SAN005 | Sanitaires bureaux |
| SAN006 | Vestiaires hommes Ruck |
| SAN007 | Vestiaires femmes Ruck |
| SAN008 | Vestiaires hommes GSF |
| SAN009 | Vestiaires femmes GSF |

---

## Architecture

```text
QR Code
   ↓
GitHub Pages
   ↓
Power Automate
   ↓
Liste SharePoint
   ↓
Power BI
