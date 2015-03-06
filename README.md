#MAEDI Capitales


## Champs de la base de données :

- **NAME** (string) : nom usuel de la ville;
- **NAME_FR** (string) : nom en français de la ville;
- **PAYS_FR** (string) : nom en français du pays;
- **CAPITAL** (string yes|no) : la ville est elle une capitale;
- **RANK** (int 1-5) : niveau d'importance de la ville permettant de modifier son affichage en fonction de son importance;
- **PRESENCE** (string yes|no) : y'a t il une présence française (ambassade, consulat, représentation auprès d'une organisation internationale) dans cette ville;
- **POPULATION** (int) : nombre d'habitant de la ville;
- **LDIR** (string N|NE|E|SE|S|SW|W|NW) : direction indiquant l'emplacement du label par rapport au point d'ancrage (dans le cas d'utilisation dans MapBox par exemple);