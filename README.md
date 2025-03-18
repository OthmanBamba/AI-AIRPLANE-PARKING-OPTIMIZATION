# AI-AVIAT
# OthmanBamba-AI-AIRPLANE-PARKING-OPTIMIZATION
AI-PARK est une application web Flask qui permet de traiter des données relatives à l'optimisation du stationnement des avions sur le tarmac. Cette application permet aux utilisateurs de télécharger des fichiers CSV, de les analyser, de charger un modèle pré-entraîné, de générer des prédictions et de visualiser des résultats sous forme de tableaux et de graphiques interactifs.

Fonctionnalités

Connexion et gestion des utilisateurs : Un système de connexion sécurisé avec un nom d'utilisateur et un mot de passe.

Téléchargement et affichage des données CSV : Téléchargement de fichiers CSV et affichage des données dans un tableau avec pagination.

Prédictions basées sur un modèle pré-entraîné : Utilisation d'un modèle de machine learning pour prédire les besoins en stationnement des avions.

Visualisations interactives : Affichage de visualisations des données et des résultats de prédictions sous forme de graphiques interactifs.

Sauvegarde des résultats : Sauvegarde des données traitées et des prédictions dans un fichier CSV.


Prérequis

Avant de démarrer l'application, assurez-vous que vous avez les prérequis suivants installés sur votre machine :

Python 3.x

Flask

pandas

scikit-learn

joblib

matplotlib

seaborn

plotly

xgboost

werkzeug

pulp

kaleido

autres dépendances listées dans le fichier requirements.txt.


Installation

1.⁠ ⁠Clonez ce repository sur votre machine locale :

git clone https://github.com/OthmanBamba/AI-AVIAT


2.⁠ ⁠Installez les dépendances nécessaires :

cd AIR_OPTIMISATION
pip install -r requirements.txt


3.⁠ ⁠Assurez-vous d'avoir un modèle pré-entraîné sauvegardé sous le chemin spécifié dans le code, par exemple :

model_path = "/path/to/Train_model2.pkl"


4.⁠ ⁠Démarrez l'application Flask :

python app.py


5.⁠ ⁠Accédez à l'application via http://127.0.0.1:5000/ dans votre navigateur.



Utilisation

1.⁠ ⁠Se connecter : Accédez à la page de connexion (/) et entrez le nom d'utilisateur et le mot de passe.


2.⁠ ⁠Télécharger un fichier CSV : Allez sur la page smart_parking et téléchargez votre fichier CSV contenant les données des vols.


3.⁠ ⁠Effectuer des prédictions : Après avoir téléchargé le fichier CSV, allez à la page load_model_and_predict pour générer des prédictions basées sur le modèle pré-entraîné.


4.⁠ ⁠Visualiser les résultats : Accédez à la page visualizations pour afficher les visualisations des résultats, comme les prédictions et les données optimisées.



Structure du projet

app.py : Fichier principal contenant la logique de l'application Flask.

templates/ : Dossier contenant les fichiers HTML pour l'interface utilisateur.

static/ : Dossier contenant les fichiers CSS et JavaScript.

models/ : Dossier contenant les modèles pré-entraînés et autres fichiers nécessaires.

requirements.txt : Liste des dépendances Python pour l'application.


Contributions

Les contributions sont les bienvenues ! Si vous souhaitez améliorer cette application ou ajouter de nouvelles fonctionnalités, n'hésitez pas à ouvrir une pull request.

License

Ce projet est sous licence MIT.
