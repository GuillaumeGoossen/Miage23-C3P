*Auteurs : Guillaume GOOSSEN & Dimos MOUSSED-WERNITZ*

### Guillaume

#### Design pattern Visitor

Le Visitor permet d’ajouter de nouvelles opérations à une structure d’objets sans modifier les objets eux-mêmes. Chaque type d’objet (ex. `Plus`, `Times`, `Number`) accepte un Visitor via une méthode `acceptVisitor`. Le Visitor effectue alors l’opération en fonction du type d’objet grâce au double dispatch. Il devient complexe si la structure des objets change fréquemment.