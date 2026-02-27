# OPESTRAT - Site Corporate

Site web corporate d'une page pour OPESTRAT.

**Slogan** : Opérationnalisons votre stratégie

## Structure du projet

```
Opestrat/
├── index.html              # Page principale
├── styles.css              # Feuilles de style
├── app.js                  # JavaScript (animations, formulaire)
├── signal-2026-01-14-210915.png  # Logo
└── README.md               # Documentation
```

## Sections

1. **Hero** - Logo, slogan et baseline
2. **Notre mission** - Présentation de l'entreprise
3. **Nos domaines** - 3 expertises (Défense nationale, Résilience informationnelle, Performance opérationnelle)
4. **Contact** - Formulaire de contact
5. **Footer** - Mentions légales

## Caractéristiques

- Design sobre et corporate
- Couleurs : bleu marine, blanc, touches de rouge
- Typographie : Inter (Google Fonts)
- Animations subtiles au scroll
- Responsive (mobile, tablette, desktop)
- Aucune dépendance externe (vanilla JS/CSS)

## Utilisation

Ouvrir `index.html` dans un navigateur web.

Pour le développement local avec rechargement automatique :

```bash
# Avec Python
python -m http.server 8000

# Avec Node.js (npx)
npx serve
```

## Personnalisation

### Couleurs

Les couleurs sont définies comme variables CSS dans `styles.css` :

```css
:root {
    --color-navy: #1a2744;
    --color-red: #c8102e;
    --color-white: #ffffff;
    --color-gray-light: #f7f8fa;
}
```

### Email de contact

Modifier l'adresse email dans `index.html` :

```html
<a href="mailto:contact@opestrat.fr">contact@opestrat.fr</a>
```

### Formulaire

Le formulaire est actuellement en mode simulation. Pour le connecter à un backend, modifier la fonction `initContactForm()` dans `app.js`.

## Licence

© 2026 OPESTRAT. Tous droits réservés.
