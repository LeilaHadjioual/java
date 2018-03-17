## installer/configurer l'environnement  

**1-Pour utiliser Java, installer l'environnement d'execution:**

cet environnement  apporte la “machine virtuelle” (le
programme qui exécute le code compilé), mais aussi les librairies de base (afficher un
texte à l’écran, ouvrir un fichier, ...), le JRE (Java Runtime Environment) suffit.  

Pour créer des programmes en Java : installer le JDK ​- Java Development Kit.

vérifier si jdk et jre ne sont pas déjà installés, dans path :   

    ex : C:\Program Files\Java\jdk1.8.0_161 

attention! emplacement important, le jdk doit être placé avant jre 

**lien téléchargement**  
http://www.oracle.com/technetwork/java/index.html  
version 8 -161

si i n'y a que jre dans le chemin path vérifier shell : taper javac dans le terminal  

**2-ajouter le chemin du jdk dans le path user** 

    C:\Program Files\Java\jdk1.8.0_161\bin
! ne pas oublié le \bin

**3-configurer l'IDE INTELLIJ:**  

l'ide affiche un message pour ajouter le jdk : 

    - cliquer ajout jdk avec le "+"  
    - effectuer le chemin du jdk  
    - cliquer sur ok  

afficher la console de debug dans l'ide :  


