# Charte de programmation Windev

## Langue
La langue choisie pour la programmation est le français. Le WLangage simplifie son usage et permet une meilleure lisibité au sein de l'équipe de développement.  
La charte de programmation du WLangage est utilisée dans le projet incluant l'ensemble ses préfixes. Il est cependant préférable de ne pas utiliser d'accents pour le nommage des variables en cas de problème lors de différentes opérations de conversion.

## Programmation Orientée Objet 
- Modèle  
   **Préfixe : M**  
   > MClient
- Interface   
   **Préfixe : I**  
   > IDaoClient
- Présentation  
   **Préfixe : P**  
   > PFicheClient 
- Injection de dépendance  
   **Préfixe _**  
   > _connexionBase
- Getter  
  **Préfixe : get**
  > getAge()
- Setter  
  **Préfixe : set**
  > setAge()

## Les variables globales & collections

- Les collections de constantes  
  **En majuscule**
  > ESPACE 

## Les fonctions 
1. Typer le retour de fonction
   > PROCEDURE Manger() : booléen
2. Typer les paramètres 
   > PROCEDURE Manger(sAliment est une chaîne) : booléen
3. Nommer les paramètres de fonction lors de l'exécution
   > Manger(\<sAliment>: "Banane")
