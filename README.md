# MANYAK & CO — Prototype de Site Web Vitrine

> Prototype d'un site web responsive pour la marque de maroquinerie haïtienne **MANYAK & CO**.
> Réalisé dans le cadre du devoir : *Composants – Mise en Page – Responsive Design* (Développement Web 1).

---

##  À propos du projet

**MANYAK & CO** est une maison de maroquinerie inspirée par l'énergie urbaine et la simplicité moderne, avec une identité visuelle fondée sur le contraste noir et blanc, avec un accent subtil haïtien. Ce prototype présente la marque à travers une interface élégante, structurée et entièrement responsive.

---

##  Arborescence du projet

```
MANYAK_CO/
│
├── index.html               ← Page d'accueil principale
├── manyak_pwodui.html       ← Page boutique / catalogue produits
├── f_a_q.html               ← Page FAQ (Frequently Asked Questions)
│
├── css/
│   ├── style.css            ← Styles de la page d'accueil
│   ├── stylepoupwodui.css   ← Styles de la page boutique
│   └── faq.css              ← Styles de la page FAQ
│
└── images/                  ← Toutes les ressources visuelles
    ├── croix (112).png      ← Logo MANYAK & CO
    ├── sandales/            ← Photos de sandales
    ├── souliers/            ← Photos de souliers
    └── sacs/                ← Photos de sacs et valises
```

---

##  Pages du site

### `index.html` — Page d'accueil
- Header avec logo et menu de navigation (offcanvas mobile)
- Section héro (présentation de la marque)
- Carrousel de produits phares
- Grille de catégories (Sandales, Souliers, Valises, Ti Valiz)
- Galeries par genre (sandales femme/homme, souliers femme/homme)
- Formulaire de contact
- Footer complet avec liens rapides et informations de contact

### `manyak_pwodui.html` — Boutique
- Grille responsive de 9 produits
- Cartes avec effet hover (double image : vue de face / vue de côté)
- Prix en HTG (Gourdes haïtiennes)
- Bouton d'achat par produit
- Barre de recherche intégrée dans la navigation

### `f_a_q.html` — FAQ
- 5 questions fréquentes présentées avec la balise `<details>`/`<summary>`
- Accordéon natif HTML sans JavaScript
- Navigation identique au reste du site

---

##  Composants UI réalisés

| Composant | Description |
|---|---|
| Navbar  Navigation responsive avec menu hamburger (offcanvas CSS pur) 
| Cards produits Cartes avec image hover, titre, description et prix |
| Carrousel  Défilement horizontal de cards produits |
| **Grille catégories** | Layout CSS Grid pour 4 catégories illustrées |
| **Galeries** | Galeries photo par section (grid responsive) |
| **Formulaire de contact** | Champs nom, email, sujet, message + bouton d'envoi |
| **Accordéon FAQ** | Basé sur `<details>` / `<summary>` HTML natif |
| **Footer** | Trois colonnes : À propos, Liens rapides, Contact |

---

## 🛠️ Technologies utilisées

- **HTML5** Balises sémantiques (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<figure>`, `<nav>`)
- **CSS3**  Flexbox, CSS Grid, Media Queries, transitions


---

## Responsive Design

Le site s'adapte à trois breakpoints :

| Écran  Largeur  Comportement 
| Mobile  ≤ 600px  Menu hamburger, layout en colonne, images fluides 
| Tablette  601px – 1024px  Grilles 2 colonnes, navigation intermédiaire 
| Desktop  ≥ 1025px  Grille complète, menu horizontal, carrousel large 

---
## Identité visuelle

- Palette principale : Noir & Blanc avec accents chauds
- Typographie : sobre et moderne, cohérente sur toutes les pages
- Style: Luxe accessible, maroquinerie haut de gamme haïtienne

---

##  Barème du devoir (100 pts)

| Partie  Points 
| Structure HTML  20 pts 
| Composants UI  20 pts 
| Mise en page CSS (Flexbox + Grid)  25 pts 
| Responsive Design  25 pts 
| Qualité générale du code  10 pts 
| TOTAL 100 pts 

> **Bonus visés** : Variables CSS, animations CSS simples

---

##  Auteur

Mardochée Gaius JNPaul
📧 jnpaulmardochee@yahoo.com
📞 (+509) 4735-2113 / 4360-7629
📍 Carrefour, Haïti

---

##  Statut

>  Prototype  Site vitrine en cours de développement.
> Les liens de paiement et la logique de commande ne sont pas encore fonctionnels.

---

© 2026 MANYAK & CO — Tout dwa rezève.
