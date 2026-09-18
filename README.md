# Suno Prompt Forge AV6 — Google Gemini Edition

Cette édition ajoute un pont optionnel vers Google Gemini.

- **Manuel** : 100 % local.
- **Copilote local** : disponible sans clé.
- **Gemini réel** : l'utilisateur peut connecter sa clé Google AI Studio.
- La réponse Gemini peut être envoyée vers le panneau Copilote puis appliquée au Style, aux Lyrics ou aux deux.

### Sécurité
Le mode statique peut appeler Gemini directement avec une clé saisie par l'utilisateur. Pour un déploiement public, il est préférable d'utiliser un backend/proxy et de conserver `GEMINI_API_KEY` côté serveur.

### API
Le pont utilise `models.generateContent` et l'en-tête `x-goog-api-key`.

### Installation
Décompresser, héberger sur HTTPS, ouvrir sur iPhone et ajouter à l'écran d'accueil.
