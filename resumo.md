#(P1C3)
## Travaillez dans un environnement virtuel:
1. Environnement virtuel
2. Ignorer des fichiers sur GitHub
3. Fichier de dépendances

1. 
Version de python de votre environnement != Version de python de votre ordinateur.

Pour commencer il faut installer virtualenv.

Le code que je conseille utiliser est:
    python3.7 -m pip install virtualenv
ou
    sudo python3.7 -m pip install virtualenv

Pour créer un nouveau environement:
    virtualenv -p python3 nom_de_lenvironnement_souaiter

Pour activer l'environnement:
    source env/bin/activate

Pour desactiver:
    deactivate

2.  
Pour ignorer des fichiers sur GitHub il faut créer un fichier .gitignore

3.  
Pour créer le fichier de depandances il faut lui donner le nom de requirements.txt:
    touch requirements.txt
Pour installer les requirements:
    pip install -r requirements.txt