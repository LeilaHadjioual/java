## installer/configurer l'environnement  

**1 - Pour utiliser Java, installer l'environnement d'execution:**

Cet environnement  apporte la “machine virtuelle” (le
programme qui exécute le code compilé), mais aussi les librairies de base (afficher un
texte à l’écran, ouvrir un fichier, ...), le JRE (Java Runtime Environment) suffit.  

Pour créer des programmes en Java : installer le JDK ​- Java Development Kit.

vérifier si jdk et jre ne sont pas déjà installés, dans path :   
SOUS JAVA_HOME  

    ex : JAVA_HOME C:\Program Files\Java\jdk1.8.0_161 

attention! emplacement important, le jdk doit être placé avant jre 

**lien téléchargement**  
http://www.oracle.com/technetwork/java/index.html  
version 8 -161

s'il n'y a que JRE dans l'environnement (path), vérifier shell : taper javac dans le terminal  

**2 - ajouter le chemin du jdk dans le path user :** 

    C:\Program Files\Java\jdk1.8.0_161\bin
! ne pas oublié le \bin

**3 - configurer l'IDE INTELLIJ :**  

l'IDE affiche un message pour ajouter le jdk : 

    - cliquer ajout JDK avec le "+"  
    - effectuer le chemin du JDK  
    - cliquer sur ok  

**4 - afficher la console de debug dans l'ide :**  

APPLICATIONS  
CHANGER LE NOM (celui que l'on souhaite)  
MAIN CLASS (ex : personnage.jeu)

**5 - créer un nouveau projet:**  

- créer new project  

create new project  
next  
nom fichier   
ok  
aller sur src : new package  
nom : main, etc ...  

- changer src  

file  
project structure  
module  
src  
sup src seul à droite  

- créer fichier pom     

ajouter le fichier pom.xml au même niveau que le dossier src  
copier coller le contenu  

    <?xml version="1.0" encoding="UTF-8"?>
    <project>
        <modelVersion>4.0.0</modelVersion>
        <groupId>fr.campus-numerique-in-the-alps</groupId>
        <artifactId>personnage</artifactId>
        <version>1</version>
        <properties>
            <maven.compiler.source>1.8</maven.compiler.source>
            <maven.compiler.target>1.8</maven.compiler.target>
            <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        </properties>
    </project>  

**6 - installer javadoc**  
sur intelliJ   

    file  
    settings  
    plugins  
    browse repository  
    taper javadoc  
    installer 
