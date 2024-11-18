Installer Python : Téléchargez et installez Python (version 3.8 ou supérieure) depuis python.org.

Créer un environnement virtuel : Ouvrez un terminal ou une invite de commande. Naviguez vers le dossier où vous voulez créer votre projet. Exécutez : python -m venv env Activez l'environnement virtuel : Sur Windows : env\Scripts\activate Sur macOS/Linux : source env/bin/activate

Cloner le projet git clone https://github.com/NormandyCode/CefMediatheque.git cd Gestion-mediatheque

Installer les dépendances : pip install django pip install pytest

Lancer le serveur de développement : python manage.py runserver

Accéder à l'application : Ouvrez un navigateur et allez à http://127.0.0.1:8000 
