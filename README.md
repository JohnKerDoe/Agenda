# À deux, agenda partagé

## Installation (une seule fois)

1. **Dépôt de l'appli** : crée un dépôt public `agenda` et dépose-y tous ces fichiers.
   Puis Settings > Pages > Branch `main` > Save. L'appli sera sur
   `https://johnkerdoe.github.io/agenda/`.
2. **Dépôt des données** : crée un dépôt **privé** `agenda-data`
   (coche « Add a README » pour qu'il ne soit pas vide).
3. **Jeton** : Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate.
   - Repository access : *Only select repositories* > `agenda-data`
   - Permissions > Repository > **Contents : Read and write**
   - Copie le jeton (`github_pat_…`). Le même jeton peut servir aux deux téléphones.
4. **Notifications** : installez l'appli **ntfy** sur les deux téléphones (Play Store).

## Sur chaque téléphone

1. Ouvrir l'adresse de l'appli dans Chrome > menu ⋮ > *Ajouter à l'écran d'accueil*.
2. Ouvrir l'appli > Réglages :
   - prénoms, `JohnKerDoe/agenda-data`, le jeton ;
   - **Mon canal** : touche *Générer*, puis abonne-toi à ce nom dans l'appli ntfy (+) ;
   - **Son canal** : le canal généré sur l'autre téléphone.
3. *Tester ma notification* pour vérifier.

Si les notifications arrivent en retard, active la réception instantanée
dans les réglages de l'abonnement ntfy.
