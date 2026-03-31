# TeaForThree 🍵

Site web familial retraçant nos voyages annuels à Londres.

**URL en ligne :** https://Adeline86.github.io/TeaForThree

---

## Structure du site

```
TeaForThree/
├── index.html              ← Page d'accueil
├── voyages.html            ← Liste de tous les voyages
├── incontournables.html    ← Nos spots favoris (avec filtre)
├── carnet.html             ← Conseils pratiques & astuces
├── avenir.html             ← Projets & wishlist 2025
├── voyage-2024.html        ← Détail voyage 2024
├── voyage-2023.html        ← Détail voyage 2023
├── voyage-2022.html        ← Détail voyage 2022
├── voyage-2021.html        ← Détail voyage 2021
├── voyage-2019.html        ← Détail voyage 2019 (le premier !)
└── css/
    └── style.css           ← Styles partagés
```

---

## Mise en ligne sur GitHub Pages

1. Aller sur **https://github.com/Adeline86/TeaForThree**
2. Cliquer sur **Settings** (onglet en haut à droite)
3. Dans le menu gauche, cliquer sur **Pages**
4. Sous "Source", sélectionner **Deploy from a branch**
5. Choisir la branche **main** et le dossier **/ (root)**
6. Cliquer sur **Save**
7. Attendre 1–2 minutes → votre site sera accessible sur :
   **https://Adeline86.github.io/TeaForThree**

---

## Personnaliser le contenu

### Ajouter vos vraies photos
Dans chaque page `voyage-XXXX.html`, cherchez les blocs `.photo-placeholder` et remplacez-les par :
```html
<img src="photos/2024/photo1.jpg" alt="Description" style="width:100%;height:100px;object-fit:cover;border-radius:8px;" />
```
Créez un dossier `photos/` à la racine pour ranger vos images.

### Modifier les textes
Tous les textes sont directement dans les fichiers HTML — cherchez et remplacez librement.

### Ajouter un nouveau voyage (ex: 2025)
1. Dupliquer `voyage-2024.html` → `voyage-2025.html`
2. Modifier le contenu
3. Ajouter la carte dans `voyages.html` et `index.html`
4. Mettre à jour les liens "Voyage suivant/précédent"

### Ajouter vos incontournables
Dans `incontournables.html`, dupliquer un bloc `.spot-card` et modifier :
- `data-cat` : `resto`, `musee`, `parc`, `marche`, `tea`, ou `balade`
- Le nom, la description, les étoiles

---

## Technologies utilisées

- HTML5 / CSS3 / JavaScript vanilla
- Google Fonts : Playfair Display + Cormorant Garamond + Lato
- Aucune dépendance, aucun framework — fonctionne partout

---

*TeaForThree — Trois voyageurs, une ville, une tradition* 🇬🇧
