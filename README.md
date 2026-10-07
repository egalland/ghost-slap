# Ghost Slap

Jeu Inktober 2026, thème « Claque ». Chasse de 45 secondes avec trois types de fantômes, score et combos.

## Jouer en local

Depuis ce dossier, lancer `python3 -m http.server 8000`, puis ouvrir http://localhost:8000 dans un navigateur récent.

Le mode tactile fonctionne sans caméra. Le mode selfie demande une caméra autorisée et un contexte sécurisé (HTTPS ou localhost), ainsi que les API Worker et OffscreenCanvas. La détection est effectuée sur l’appareil.

## Projet statique

Le dossier contient directement les fichiers HTML, CSS, JavaScript, images, modèles MediaPipe et fichiers WebAssembly. Aucune compilation ni base de données n’est nécessaire. Conserver toute l’arborescence `assets/` pour la détection des mains et du visage.

Version récupérée du projet original le 7 octobre 2026, commit source `2ef9b015a01ff5b6beb6f3bf244ce68020b69708`. Les scripts de l’application ont passé un contrôle de syntaxe ; la caméra réelle sur téléphone reste à vérifier.
