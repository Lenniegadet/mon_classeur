# Mon Notebook
## Chaines :

Ex: 
'hello'
mot = hello   guillemets = indique que c´est une chaine de caractères

Possibilité d´additionner des chaines
Ex: 
'hello' + 'world'

## Variables :

Ex: 
mot = 'hello'  

--> 
  hello   
  
  
  car la variable mot est définie
  
  
Ex: 
soleil 

--> 
  erreur   
  
  car la varaible soleil n´est pas définie, Python cherche sa valeur

Ex:
mot = 'hello'  
votre_nom = Lennie  
print(mot + ' ' + votre_nom) 

--> 
  hello Lennie

## Boucle for :

for <variable> in <itérable> : <code à repéter>
Ex: 
nom : 'world'   
ligne = '-'  
for caractere in nom: 
   print(ligne + nom)
                                    
  --> 
  
  -world
  
  -world
  
  -world
  
  -world
  
  -world
  
## Construction de chaines :
  
Ex: 
nom = 'World'    
ligne = ' '    
for caractere in nom:
    ligne = ligne + caractere
    print(ligne)
  
-->

  W
  
  Wo
  
  Wor
  
  Worl
  
  World
  
On peut aussi modifier le script pour que les caractères soient inversés :
  Il suffit d´inverser caractere et ligne dans <ligne = ligne + caractere> ce qui donnerais <ligne = caractere + ligne>
  
Ex: 
nom = 'World'    
ligne = ' '    
for caractere in nom:
    ligne = caractere + ligne
    print(ligne)
  
-->
  
  W
  
  oW
  
  roW
  
  lroW
  
  dlroW

Au passage, le caractere _ dans une boucle tel que for caractere in ...: est égale à caractere, on peut donc le remplacer par _. Cela ne change pas l'exécution du script, mais est utile au lecteur.



