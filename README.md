# Portfolio · Seth-Sady Ndinga-Ndinga

Site statique (HTML/CSS/JS, sans build), bilingue FR/EN, mode clair/sombre.

## 1. Brancher le formulaire de contact (5 min, gratuit)

GitHub Pages ne peut pas envoyer d'email tout seul : le formulaire passe par **Formspree**.

1. Crée un compte sur https://formspree.io et clique sur **New Form** (mets ton email perso comme destinataire).
2. Formspree te donne une adresse du type `https://formspree.io/f/abcdwxyz`.
3. Dans `index.html`, remplace `https://formspree.io/f/VOTRE_ID_FORMSPREE` par cette adresse.
4. Au premier message reçu, confirme ton email dans Formspree. Les messages arrivent ensuite dans ta boîte mail.

Le formulaire contient un champ caché anti-spam (`_gotcha`) et affiche un message de succès ou d'erreur sans quitter la page.

## 2. À compléter

- `ton.email@exemple.com` (2 endroits) → ton email personnel
- `https://www.linkedin.com/in/seth-sady/` (renseigné)
- `cv.pdf` à ajouter à la racine (bouton « Télécharger mon CV »)
- « Basé en France », « CDI · Hybride » : à ajuster si besoin

## 3. Mise en ligne sur GitHub Pages

1. Crée un dépôt public **`testS7ven.github.io`**.
2. Mets-y `index.html`, `README.md` et le dossier `assets/`, puis :
   ```bash
   git init && git add . && git commit -m "Portfolio"
   git branch -M main
   git remote add origin https://github.com/testS7ven/testS7ven.github.io.git
   git push -u origin main
   ```
3. **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
4. En ligne après 1 à 2 minutes sur `https://testS7ven.github.io`.
