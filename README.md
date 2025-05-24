# Formulaire de contact - BATINOV

Ce dépôt contient un formulaire de contact simple et responsive, conçu pour l'entreprise **BATINOV**, spécialisée dans le secteur du BTP.

## ✉️ Fonctionnalité

- Champs : Nom, Prénom, Téléphone, Email, Sujet, Message
- Liste déroulante pour choisir le type de demande (Sujet)
- Compatible avec [Formsubmit](https://formsubmit.co) pour recevoir les messages directement par e-mail
- Responsive et facile à intégrer dans un site vitrine ou une page de contact

## 🌐 Mise en ligne

Ce formulaire est pensé pour être hébergé gratuitement via **GitHub Pages** :

1. Crée un repository public
2. Uploade les fichiers :
   - `contact.html`
   - `contact.css`
3. Active GitHub Pages dans les **Settings > Pages**
4. Configure `contact.html` comme page d’accueil

## 🔗 Exemple d'intégration avec Formsubmit

Dans `contact.html` :

```html
<form action="https://formsubmit.co/votre-email@example.com" method="POST">
  <input type="hidden" name="_captcha" value="false">
  <!-- Autres champs ici -->
</form>
