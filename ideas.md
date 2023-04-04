BERT : entraînement sur 3 epochs (1h d'entraînement) <br>
DistillBERT pour avoir un modèle plus petit mais aussi performant <br>
BERT bon pour MLM mais pas forcément pour classification - voir SentenceBERT <br>
Mettre à frozen les couches profondes de BERT peut détériorer les performances - nécessaires de modifier en profondeur <br>

FastText et GLoVe sont à tester tous les deux
TreebankTonizer plutôt que TweetTokenizer sur cette tâche
Essayer avec des embedding randoms (couche lookup table au début du réseau)