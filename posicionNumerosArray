/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
  
  Ejercicio 6
    Escribe un programa que lea 15 números por teclado y que los almacene en un
    array. Rota los elementos de ese array, es decir, el elemento de la posición 0
    debe pasar a la posición 1, el de la 1 a la 2, etc. El número que se encuentra en
    la última posición debe pasar a la posición 0. Finalmente, muestra el contenido
    del array.
 */
package com.mycompany.holamundo;
import java.util.Scanner;
/**
 *
 * @author Compumag
 */
public class RotarNumerosArray {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] numero = new int[15];
       
        System.out.println("Digita 15 numeros");
        for (int i = 0; i < numero.length; i++){
            numero[i] = sc.nextInt();
        }
        
        int aux3 = numero[(numero.length)-1];
        int aux = numero[0];
        int aux2 ;
        for (int i = 1; i<numero.length;i++){
            if((i+1) == numero.length){
                numero[0] = aux3;
                numero[i] = aux;
            }else{
            aux2 = numero[i];
            numero[i] = aux;
            aux = aux2;
            } 
        }
        
        for(int i = 0; i < numero.length;i++){
            System.out.println("numeros["+i+"]: "+numero[i]);
        }
        
        
    }
    
}
