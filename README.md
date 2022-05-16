# ejercicio-OpenBootcamp
ejercicio 1 fundamentos  OpenBootcamp


public class Main{

public static void main(String[] args){
  
  int resultado;
  
  
  resultado = suma( int a= 10, unt b= 5, int c= 20);
  
 
 System.out.println(resultado);
 
 
}


public static int suma( int a, int b, int c){


 return a + b + c;
 
}


}

#Segunda parte del ejercicio:

class Coche(){


public int puertas= 0;

public static int añadirPuerta(){


this.puertas++;


}


public static void main(String[] args){


Coche miCoche = new Coche(){


miCoche.añadirPuerta();


System.out.println(miCoche.puertas);


}
