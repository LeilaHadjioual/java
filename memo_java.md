## DEFINITION TERMES

**classe**   

    représente un ensemble d'objets ayant la même structure et les mêmes comportements.
    capable de générer des instances    

    ex : public class MaClasse
        {
            // corps de la classe
        }

**classe abstraite**  

    impossible à instancier, déclarée avec mot-clé "abstract"
    ex : public  abstract  class A {  }

**méthode**  

        fonction définie dans une classe qui décrit comment l'instance de cette classe va réagir  

        ex: /* une procédure (« void » signifie : pas de résultat) de nom « setConjoint », avec un paramètre de nom « c » et de type « Personne », qui permet de changer le conjoint */  
            void setConjoint(Personne c) {  
              
            }  

        /* une fonction de nom « âge », sans paramètre, avec un résultat de type « int » (entier), qui calcule l'âge */   
            int âge() {   
            } 


**constructeur**  

    méthode particulière, portant le même nom que la classe et automatiquement invoquée juste après la création d’une instance, son rôle est de créer un nouvel objet.
    Si aucun constructeur n’est défini, Java fournit un constructeur sans paramètre appelé constructeur implicite ou par défaut


**getter**  

    accesseur permettant d'accéder aux valeurs des variables d'instance 


**setter**   

    accesseur permettant de modifier les valeurs des variables d'instance


**objet**  

    instance de classe, la création d'objet se fait à l'aide du constructeur de cette classe

**attribut**  

    élément de la structure des objets  

    ex : class Personne {
            /* un attribut de nom « nom » et de type « String » (chaîne de caractères)*/   
            String nom;   
            /* un attribut de nom « conjoint » et de type « Personne » */ Personne conjoint;   
            /*un attribut de nom « dateNaissance » et de type « Date » */  
            Date dateNaissance;
        }

**héritage**  

    définition d’une classe par extension des caractéristiques d’une autre classe.
    permet d'éviter la redondance de code

**interface**

    définit un comportement d’une classe mais n’implémente aucune méthode.
    ensemble de méthodes abstraites, et de constantes

**package**

    fichier regroupant des classes

**polymorphisme**

    la capacité d'un objet à prendre plusieurs formes, c'est-à-dire à être manipulé en fonction de sa classe.
    une même méthode peut avoir un comportement différent en fonction de l'instance à laquelle elle est appliquée  

**extends**  

    étend une classe

**implements**  

    étend une interface  

**import**

    importer les packages  
    ex : import java.util.ArrayList;



