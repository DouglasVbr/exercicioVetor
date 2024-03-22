# exercicioVetor


package vetor;


public class Vetor {

    public static void main(String[] args) {
        
      int [] Numeros = new int [5];
      Numeros[0] = 10;
      Numeros[1] = 20;
      Numeros[2] = 30;
      Numeros[3] = 40;
      Numeros[4] = 50;
      
      for (int i = 0; i < Numeros.length; i++){
          System.out.println(i);
          System.out.println(i + " = " + Numeros[i]);
      }
        
    }
    
}
