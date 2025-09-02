# Código con comentarios en línea

# import java.util.Scanner; // Importa la clase scanner del paquete java.util para leer desde teclado

# public class Vehiculo { // Declaración de la clase pública Vehiculo
#    public static void main(String[] args) { // Punto de entrada de la aplicación Java
#        Scanner sc = new Scanner(System.in); // Crea un scanner que lee desde el teclado

#        System.out.print("Ingrese su Nombre: "); // Muestra mensaje para solicitar "Nombre"
#        String nomb = sc.nextLine(); // Lee la entrada para "Nombre"

#        System.out.print("Ingrese su Edad: "); // Muestra mensaje para solicitar "Edad"
#        int edad = sc.nextInt(); // Lee la entrada para "Edad"

#        System.out.print("Ingrese la marca del vehículo: "); // Muestra mensaje para solicitar "marca"
#        String marca = sc.nextLine(); // Lee la entrada para "marca"

#        System.out.print("Ingrese el modelo del vehículo: "); // Muestra mensaje para solicitar "modelo"
#        String modelo = sc.nextLine(); // Lee la entrada para "modelo"

#        System.out.print("Ingrese la cilindrada del vehículo: "); // Muestra mensaje para solicitar "cilindrada"
#        String cilindrada = sc.nextLine(); // Lee la entrada para "cilindrada"

#        System.out.print("Ingrese el tipo de combustible: "); // Muestra mensaje para solicitar "combustible"
#        String combustible = sc.nextLine(); // Lee la entrada para "combustible"

#        System.out.print("Ingrese la capacidad en pasajeros: "); // Muestra mensaje para solicitar "capacidad"
#        int capacidad = sc.nextInt(); // Lee la entrada para "capacidad" (entero)

#        System.out.println("\n--- Datos del Usuario ---"); // Título de salida 1
#        System.out.println("Usuario: " + nomb); // Imprime "Nombre"
#        System.out.println("Edad: " + edad); // Imprime "Edad"
#        System.out.println("\n--- Datos del Vehículo Ingresados ---"); // Título de salida 2
#        System.out.println("La marca que ha ingresado es: " + marca); // Imprime "marca"
#        System.out.println("El modelo que ha ingresado es: " + modelo); // Imprime "modelo"
#        System.out.println("La cilindrada que ha ingresado es: " + cilindrada); // Imprime "cilindrada"
#        System.out.println("El tipo de combustible es: " + combustible); // Imprime "combustible"
#        System.out.println("Tiene una capacidad de " + capacidad + " pasajeros."); // Imprime "capacidad"

        sc.close(); // Cierra el scanner
    } // Fin de main
} // Fin de clase Vehiculo
