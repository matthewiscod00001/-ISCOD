HOOK PRE-COMMIT - Instructions d'installation
==============================================

Ce hook pre-commit enregistre automatiquement un fichier de suivi
lors de chaque commit si vous repondez 'y' a la question posee.

Instructions :
1. Copier le fichier 'pre-commit' dans le dossier '.git/hooks/' de votre depot local
2. Rendre le fichier executable avec la commande : chmod +x .git/hooks/pre-commit
3. A chaque commit, repondre 'y' pour enregistrer le suivi ou 'n' pour ignorer

Le fichier de suivi sera cree dans 'suivi/commitInfo.txt'
