Pour installer le hook pre-commit :

1. Copier le hook dans le dossier .git/hooks/
   cp hooks/pre-commit .git/hooks/pre-commit
2. Rendre le hook exécutable :
   chmod +x .git/hooks/pre-commit
3. Le hook sera automatiquement exécuté à chaque commit.
