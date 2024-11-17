# Étape 1 : Créer et initialiser le projet
mkdir ~/Documents/guessinggame
cd ~/Documents/guessinggame
touch guessinggame.sh makefile
nano guessinggame.sh
nano makefile
chmod +x guessinggame.sh

# Étape 2 : Générer le fichier README.md
make
cat README.md

# Étape 3 : Initialiser Git
git init
git add .
git commit -m "Initial commit for guessinggame project"

# Étape 4 : Lier à GitHub et envoyer les fichiers
git remote add origin https://github.com/<votre-utilisateur>/guessinggame.git
git branch -M main
git push -u origin main
