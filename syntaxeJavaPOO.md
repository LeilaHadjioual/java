## SYNTAXE JAVA POO


**classe**  

    class Car { 
    }

**constructors** 

    class Car {
        //The class constructor for the Car class
        public Car() {
        }
    }

**variable d'instance**  

    class Car {
         //Using instance variables to model our Car class after a real-life car
        int modelYear;
        public Car() {
        }
    }

**paramètre du constructeur**

    class Dog {
        int age;
	    public Dog(int dogsAge) {
            age = dogsAge;
        }
	    public static void main(String[] args) {
	    }
    }


**main methode**  

    class Car {
        int modelYear;
        public Car(int year) {
            modelYear = year;
        }
        //main method
        public static void main(String[] args){
            Car myFastCar = new Car(2007); // inctance de Car qui est un objet
        }
    }

**methode** 

    class Car {
        int modelYear;
        public Car(int year) {
            modelYear = year;
        }
        //Our new method to help us get "started"
        public void startEngine() {
            System.out.println("Vroom!");
        }
        public static void main(String[] args){
            Car myFastCar = new Car(2007);
        }
    }

**appeler une méthode sur un objet**  

    class Car {
        int modelYear;
        public Car(int year) {
            modelYear = year;
        }
        public void startEngine() {
            System.out.println("Vroom!");
        }
        public static void main(String[] args){
            Car myFastCar = new Car(2007);
            myFastCar.startEngine(); // appel de la méthode sur l'objet
        }
    }

**add paramètre aux méthodes**  

    class Car {
        int modelYear;
        public Car(int year) {
            modelYear = year;
        }

    public void startEngine() {
        System.out.println("Vroom!");
    }

    public void drive(int distanceInMiles) { // paramètre passé à la méthode
        System.out.println("Miles driven: " + distanceInMiles);
    }

    public static void main(String[] args){
        Car myFastCar = new Car(2007);
        myFastCar.startEngine();
        myFastCar.drive(1628); //appel de la méthode sur l'objet
    }
