# Utiliser une image de Python
FROM python:3.8

# Répertoire de travail
WORKDIR /app

# Copier les fichiers du répertoire courant dans le répertoire de travail
COPY . /app

# Installer les dépendances Python nécessaires
RUN pip install -r requirements.txt

# Port sur lequel le serveur Flask va tourner
EXPOSE 5000

# Commande pour démarrer l'application
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
