# DHD — Doha Hanine Daoudi

Portfolio professionnel bilingue français / anglais, conçu en React, TypeScript et Vite. Fond blanc, bleu marine et bleu ciel, portrait personnel et CV téléchargeables.

![Aperçu du portfolio](preview.png)

## Français

### Démarrage

Node.js 22 ou version compatible.

```sh
npm ci
npm run dev
```

### Vérifications et production

```sh
npm run typecheck
npm run lint
npm run build
npm run preview
```

Fonctionnalités : langues FR/EN, thème clair/sombre persistant, menu mobile, navigation par ancres, animations respectant la réduction des mouvements, fiches projets accessibles au clavier, chronologie dépliable, deux CV PDF originaux, liens e-mail, métadonnées SEO, sitemap et favicon DHD original.

Le workflow `.github/workflows/deploy.yml` construit et déploie sur GitHub Pages à chaque push sur `main`. Dans Settings → Pages, la source doit être GitHub Actions. La base Vite est `/dhd-portfolio/`.

Les contenus proviennent des CV fournis. Les visuels des projets sont des illustrations, pas des captures d’applications. Les dépôts des projets et leurs démonstrations ne sont pas publiés ; aucun lien fictif n’est affiché. Les deux CV sont les PDF originaux validés par Doha, copiés sans modification. Son profil LinkedIn officiel est intégré au hero, au contact et au pied de page.

Contenu : `src/content.ts` ; interface : `src/App.tsx` ; styles : `src/style.css` ; documents : `public/cv/`.

## English

A bilingual professional portfolio built with React, TypeScript, Vite, Tailwind CSS, Motion and Lucide. Run `npm ci` and `npm run dev` for development; `npm run build` creates the static site in `dist/`.

Includes persistent French/English and light/dark preferences, responsive navigation, keyboard-accessible project dialogs, reduced-motion support, experience timelines, original downloadable CVs, email links and SEO metadata.

GitHub Actions publishes changes from `main` to GitHub Pages. Select GitHub Actions as the Pages source. Project illustrations are conceptual, not product screenshots. Project repositories and demos are not publicly available. Both original PDFs are preserved byte for byte. The official LinkedIn profile is included in the hero, contact section and footer.

Personal photos and CVs belong to Doha Hanine Daoudi. No blanket license is granted for reuse of personal assets.

## Original CV integrity

- `Doha_Hanine_Daoudi_CV_Francais_PFE_2027.pdf` — SHA-256: `b3bbd51ca58b9e30aaecc1a143e1793342e245efb2f710f4329449fbc9f497a8`
- `CV_DOHA_HANINE_DAOUDI.pdf` — SHA-256: `9fd25e7d1be1b9a73891494a78c257a10ace899a57067d733b46a6803dfa1935`
