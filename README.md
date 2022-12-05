
**Vidéo Demo afin de tester le fonctionnement du chatbot**

>> on va supposer qu’une personne a envie de voyager de Rabat (Maroc) à Milan ( Italie).Pour cela, elle a besoin des informations concernant le prix des vols, la 
disponibilité des hôtels et d’autres informations liées au voyage prévu.

https://user-images.githubusercontent.com/77699359/205625527-2b115a65-3010-488b-8666-5304800280fc.mp4

**Structure du fichier Chatbot**

**Train_chatbot.py :** Dans ce fichier, nous allons créer et former le modèle de deep learning. Ce dernier va classer et identifier ce que l’utilisateur demande au robot.

**Gui_Chatbot.py :** C’est dans ce fichier que nous allons créer une interface utilisateur 
graphique pour tchatter avec notre chatbot formé.

**Intents.json :** Le fichier d’intents contient toutes les données que nous allons utiliser pour 
former le modèle. Il comprend une collection de balises avec leurs modèles et réponses 
correspondants.

**Chatbot_model.h5 :** Il s’agit d’un fichier de format de données hiérarchique dans lequel nous 
avons sauvegardé les poids et l’architecture de notre modèle formé.

**Classes.pkl :** Le fichier pickle peut être utilisé pour sauvegarder tous les noms de balises à 
classer lorsque nous prédisons le message.

**Words.pkl :** Le fichier pickle words.pkl contient tous les mots uniques qui constituent le 
vocabulaire de notre modèle.


