Projet Reconnaissance Facial
AUCOIN Clément, DUBERNET Samuel, MARTIN Cédric

- Utiliser un environnemnt virtuel pour l'installation des packages
pip install virtualenv
virtualenv env
source env/Script/activate

- installation des packages utilisé
pip install -r requirements.txt

- Penser à modifier les chemins relatifs 

- Lancement de l'application 
python main.py

- Lors de la premiere utilisation il faudra enregistrer des photos utile à l'apprentissage de la Reconnaissance Facial
prise de photo : touche 's'

- sorti de l'application : touche 'CTRL-C' ou 'q'

- Pour l'apprentissage il faut lancer l'application 'data_set_create.py' 
python data_set_create.py

- Relancer l'application main.py

- Il est possible d'utiliser notre dataset déjà paramétré pour deux utilisateurs -Samuel et Clément-