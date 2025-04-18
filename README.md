# Generative-AI
Ce code crée une assistance vocale intelligente utilisant l'API Gemini de Google, intégrée dans une application web Flask, qui :

Configure le modèle IA (Gemini 1.5 Pro) avec une clé API Google

Gère une conversation contextuelle en conservant l'historique des échanges

Optimise les réponses pour qu'elles soient claires et concises (sans digressions inutiles)

Offre une interface web (via Flask) avec :

Une page d'accueil (/)

Un endpoint API (/process_voice) pour traiter les requêtes vocales et renvoyer des réponses en JSON

Compare les similarités textuelles (via difflib) pour une analyse potentielle des inputs utilisateur

Fonctionnement résumé :
L'utilisateur envoie une requête vocale → L'IA génère une réponse ciblée → L'historique de conversation est mis à jour et renvoyé à l'interface.

Note : Remplacez "your api key" par une vraie clé Google API pour le faire fonctionner.

Clic on le lien below:
![image](https://github.com/user-attachments/assets/0530f464-3184-4c26-878b-4b40923a375e)


