#### Installer Mysql pour python
```
    pip install mysql-connector-python
```

#####  Rendez vous dans le fichier `creds.py` contenu dans le répertoire modele et modifier la variable avec votre password `user_pwd`
```
 user_pwd = "your mysql password"
```
##### créez le schema de la bdd en lancant ce fichier
```bash
python db_init.py
```

##### apres avoir crée le schema, lancer l'application
```bash
python main.py
```
---


