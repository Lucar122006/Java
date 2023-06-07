    import java.util.Scanner;
    public class Patitos{
         public static void main (String[]args){
          Scanner sc=new Scanner(System.in);
          String nombre;
          int Clave=0;
          int Antiguedad=0;
          System.out.println("Bienvenido al sistema");
          //aqui se va aparecer el dato a solicitar
          System.out.println("Nombre del trabajador");
          //aqui pedi el nombre en texto
          nombre=nextLine();
          System.out.println("Antiguedad del trabajador");
          //aqui pedi el dato en numero
          Antiguedad=nextInt();
          System.out.println("Clave del deparatemanto del trabajador");
          //aqui pedi el dato en numero
          Clave=nextInt();
          if(Clave==1){
            if(Antiguedad==1){
              System.out.println(nombre + " 6 dias de vacaciones");
            }else if(Antiguedad>=2 && Antiguedad<=6){ 
              System.out.println(nombre + " 14 dias de vacaciones");
            }else if(Antiguedad==7){  
              System.out.println(nombre + " 20 dias de vacaciones");     
            }else{
               System.out.println(nombre + " Aun no tienes derecho a vacaciones"); 
            }
          }else if(Clave==2){
            if(Antiguedad==1){
              System.out.println(nombre + " 7 dias de vacaciones");   
            }else if(Antiguedad>=2 && Antiguedad<=6){
              System.out.println(nombre + " 15 dias de vacaciones");  
            }else if(Antiguedad==7){  
              System.out.println(nombre + " 22 dias de vacaciones");   
            }else{
              System.out.println(nombre + " Aun no tienes derecho a vacaciones"); 
            }
          }else if(Clave==3){
            if(Antiguedad==1){
              System.out.println(nombre + " 10 dias de vacaciones");
            }else if(Antiguedad>=2 && Antiguedad<=6){ 
              System.out.println(nombre + " 20 dias de vacaciones");
            }else if(Antiguedad==7){  
              System.out.println(nombre + " 30 dias de vacaciones");     
            }else{
               System.out.println(nombre + " Aun no tienes derecho a vacaciones"); 
            }
          }


     }
    }
