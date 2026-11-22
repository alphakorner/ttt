# Alpha Korner

Lecteur musique web (YouTube Music) — dérivé d'OpenTune / MyTune, sous licence **GPL-3.0**.
Le code a été **modifié** (nouveau nom, compte e-mail + mot de passe, build à plat sans dossier).
Le code source complet de ce build est dans `alphakorner-source.zip` (obligation GPL-3.0). `LICENSE` et `THIRD_PARTY_NOTICES.md` doivent rester.

## Mise en ligne (GitHub Pages)
1. Crée un dépôt GitHub (public), puis **Add file → Upload files** et glisse **tous** les fichiers de ce dossier (il y en a moins de 100, aucun dossier).
2. **Settings → Pages → Deploy from a branch → main / (root)**.
3. Le site est sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Extension navigateur (obligatoire pour le son)
Un site web n'a pas le droit de lire les flux YouTube tout seul : l'extension (`alphakorner-extension-chrome.zip` ou `-firefox.zip`) fait ce travail.
- Chrome/Edge/Brave : dézipper dans un nouveau dossier, `chrome://extensions`, mode développeur, **Charger l'extension non empaquetée**.
- L'extension n'accepte que l'adresse du site pour laquelle elle a été compilée : voir `extension.json` / demande la recompilation avec ton pseudo + nom de dépôt.
- Sur téléphone, les navigateurs n'acceptent pas l'extension : utiliser un ordinateur (ou Firefox Android).

## Compte
Création de compte limitée pour le moment à une adresse autorisée. Vérification faite dans le navigateur : c'est un filtre d'accès, pas une sécurité serveur.
