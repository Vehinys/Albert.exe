# Albert.exe — Portfolio d'Albert Lecomte

Portfolio personnel interactif au design **OS-style** (interface Windows-like) pour Albert Lecomte, Concepteur Designer UI basé à Mulhouse.

🔗 **En ligne :** [lecomte-albert-cv.vercel.app](https://lecomte-albert-cv.vercel.app/)

---

## Aperçu

Portfolio bilingue (FR / EN) bâti comme un système d'exploitation simulé : barre des tâches, menu Démarrer, fenêtres déplaçables, et expérience immersive en glassmorphism. Pensé pour mettre en valeur des projets de design UI auprès de clients web et patrons WordPress.

## Stack technique

| Couche        | Technologie                       |
| ------------- | --------------------------------- |
| Framework     | [Astro](https://astro.build/) 5.x |
| Langage       | TypeScript 5 (strict)             |
| Styles        | Tailwind CSS v4                   |
| Contenu       | Astro Content Collections (JSON)  |
| Formulaire    | EmailJS                           |
| Analytics     | Plausible (sans cookie)           |
| Images        | Sharp (WebP)                      |
| Hébergement   | Vercel (CD auto via GitHub)       |

## Fonctionnalités

- Interface OS interactive (fenêtres, taskbar, menu Démarrer)
- Bilingue FR / EN avec routage Astro i18n
- Mode sombre / clair
- Conformité **RGAA AAA** : panel d'accessibilité (taille de police, contraste, espacement, animations réduites), navigation clavier complète, contrastes ≥ 7:1
- Respect de `prefers-reduced-motion` et `prefers-color-scheme`
- SEO : meta OG, Schema.org Person, sitemap automatique
- Formulaire de contact via EmailJS
- Pages légales (mentions, confidentialité, déclaration d'accessibilité)


```

## Structure

```
src/
├── components/    Composants Astro (ui, sections, layout, seo)
├── content/       Content Collections (projets, compétences)
├── i18n/          Traductions FR / EN + helpers
├── layouts/       Layout de base
├── pages/         Routes (FR à la racine, EN sous /en/)
├── styles/        global.css (Tailwind + design tokens)
└── utils/         emailjs, animations
public/
├── cv/            CV PDF
└── images/        Visuels et screenshots projets
```

## Licence

Tous droits réservés — © Albert Lecomte.

## Contact

Albert Lecomte — Mulhouse, Alsace
[albert.lecomte1989@gmail.com](mailto:albert.lecomte1989@gmail.com)
