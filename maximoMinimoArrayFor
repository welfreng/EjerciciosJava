/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
    ejercicio 5 Array
      Escribe un programa que pida 10 números por teclado y que luego muestre los
      números introducidos junto con las palabras “máximo” y “mínimo” al lado del
      máximo y del mínimo respectivamente
 */
package com.mycompany.holamundo;
import java.util.Scanner;
import java.lang.Math;
/**
 *
 * @author Compumag
 */
public class maxmoMinimo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] numero = new int[10];
        String[] mixta = new String[10];
        
        for (int i = 0; i < numero.length; i++){
            System.out.println("Digita numero entero: ");
            numero[i] = sc.nextInt();
        }
        
        
        int comparador = numero[0];
        for (int i = 0; i < numero.length; i++){
       
            if ((i+1) == numero.length){
                if (comparador > numero[i-1]){
                    mixta[i] = "maximo";
                    
                }else if (comparador < numero[i-1]){
                    mixta[i] = "minimo";
                }
            }else{
                
                if (comparador > numero[i+1]){
                    mixta[i] = "maximo";
                    comparador = numero[i+1];
                }else if (comparador < numero[i+1]){
                    mixta[i] = "minimo";
                    comparador = numero[i+1];
                }
            }
            
        }
        for (int i = 0; i < numero.length;i++){
            System.out.println(numero[i]+" - "+ mixta[i]);
        }
    }
    
    
}
