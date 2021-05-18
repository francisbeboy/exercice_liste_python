# exercice_liste_python
# exercice sur les listes en python
# ####################### exo 1 #########


# dans cette exercise vous devez récuperer les différents morceaux
# de la liste grace aux slices

# la de départ est la suivante

# liste = ["Maxime", "Martine", "Christopher", "Carlos", "Michael", "Eric"]
# L'objectif de cet exercise est de récuperer les informations grace aux slices:

# --Les trois premiers employés ('Maxime', "Martine", "Christopher") dans une liste
# trois premiers

# --les trois derniers employés ('Carlos', "Michael" et Eric) dans une liste les trois
# derniers.

# --tous les employés sauf le premiers et le derniers dans une liste milieu

# --Le premier et le derniers employé dans une liste premier_dernier

```python
liste = ["Maxime", "Martine", "Christopher", "Carlos", "Michael", "Eric"]
trois_premiers =  print(liste[0:3]) # INSERER CODE ICI
trois_derniers = print(liste[3:]) # INSERER CODE ICI
milieu = print(liste[1:-1])# INSERER CODE ICI
premier_dernier = print(liste[0::5]) # INSERER CODE ICI
```


# ############################### exo 2 #######################################


# Dans cet exercice, vous devez  ajouter le nombre 6 dans la liste.
# Faites une vérification par la suite pour vous assurer que l'élément a bien été ajouté.

# La liste de départ est la suivante :
# liste = [1, 2, 3, 4, 5] Vous devez ajouter le nombre 6 dans la liste.
# Vérifiez ensuite si le nombre 6 est présent dans la liste, si c'est le cas, 
# affichez la chaîne de caractères  Le nombre 6 a bien été ajouté à  la liste.
```python
liste = [1, 2, 3, 4, 5]
liste[4] = 6
i=6
if i== liste[4]:
    print(f"Le nombre {i} à bien été ajouter à la liste")
else:
    print(f"Erreur de l'ajout du nombre {i}")
```
###### Exo 3 ################
   


# Récuperer des élements dans une liste imbriquée
# Dans cet exercice, vous devez Récuperer des informations Ã  l'intérieur de deux  listes imbriquées.
# Le script dispose de deux listes contenant plusieurs listes imbriqués, une liste langage et une liste nombres. 
# Vous devez Récuperer dans les variables python, deux et sept, respectivement la chaîne de caractères 'Python'
# contenue dans la liste langages et les nombres 2 et 7, contenus dans la liste nombres.
# Vous n'avez pas besoin d'afficher les variables avec print, 
# il suffit de Récuperer les bonnes valeurs dans les variables à  partir 
# des listes et avec les indices des éléments.

```python
print(" ############################# Exo 3 ########################################## ")
langages = [["Python", "C++"], "Java"]
nombres = [1, [4, [2, 3]], 5, [6], [[7]]]
python =print(langages[0][0]) # entrez le code ici
deux= print(nombres[1][1][0]) # entrez le code ici
sept= print(nombres[4][0][0])# entrez le code ici
```
