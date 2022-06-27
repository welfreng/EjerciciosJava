/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 
 ejercicio: 
           Define tres arrays de 20 números enteros cada una, con nombres numero, cuadrado
          y cubo. Carga el array numero con valores aleatorios entre 0 y 100. En el array
          cuadrado se deben almacenar los cuadrados de los valores que hay en el array
          numero. En el array cubo se deben almacenar los cubos de los valores que hay en
          numero. A continuación, muestra el contenido de los tres arrays dispuesto en tres
          columnas.
 */
package com.mycompany.holamundo;
import java.util.Scanner;
import java.lang.Math;
/**
 *
 * @author Compumag
 */
public class TresArrays {
    public static void main(String[] args) {
        
        int[] numero = new int[20];
        int[] cuadrado = new int[20];
        int[] cubo = new int[20];
        
        
        for (int i = 0; i < numero.length; i++){
            numero[i] = (int)(Math.random()*100);     
        }
        
        for (int i = 0; i < numero.length;i++){
            cuadrado[i] = (int)(Math.pow((double)(numero[i]),2));
            cubo[i] = (int)(Math.pow((double)(numero[i]),3));
        }
        
        for (int i = 0; i <  numero.length; i++){
            System.out.print(numero[i]+ " "); 
            System.out.print(cuadrado[i]+ " ");
            System.out.print(cubo[i] + " ");
            
        }
    }
    
}
