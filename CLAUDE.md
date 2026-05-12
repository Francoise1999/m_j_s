# Projet : Site de mariage Jaurelle

## Ce qu'on a fait
Site web de mariage — une seule page HTML (`index.html`), sans galerie, sans dépendances npm.
Design élégant : palette ivoire + or doré, typographies Cormorant Garamond + Montserrat (Google Fonts), ornements SVG fins, animations CSS fluides.

## Fichiers
- `index.html` — la page entière (HTML + CSS inline dans `<style>`)

## Ce qu'il reste à personnaliser dans index.html

| Élément | Balise / emplacement |
|---|---|
| Prénoms des mariés | `<h1 class="names">` et le `<footer>` |
| Date de la cérémonie | `<p class="date-block"><strong>…</strong></p>` |
| Lieu | `<p class="date-block">` (ligne suivante) |
| Date limite de réponse | `<strong style="color:var(--text);">15 juin 2025</strong>` |
| Lien Google Form | `href="VOTRE_LIEN_GOOGLE_FORM_ICI"` sur le bouton CTA |
| Texte d'invitation | Section `<section class="invitation">` |

## Choix de design
- Palette CSS : `--ivory #faf7f2`, `--gold #b89a6a`, `--dark #2c2416`
- Fonts : Cormorant Garamond (titres) + Montserrat (corps)
- Pas de framework, pas de JS — pur HTML/CSS
- Bouton CTA : animation fill gauche→droite au hover
- Cadre intérieur doré sur le hero (`.hero-frame`)

## Ce qu'on n'a pas fait (à faire si besoin)
- Hébergement (GitHub Pages, Netlify, Vercel…)
- Nom de domaine personnalisé
- Version mobile poussée (responsive basique déjà en place)
- Favicon / og:image pour le partage réseaux sociaux
