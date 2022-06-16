# ProyectoIntroduccionALaProgramacion
Grupo 7 - Proyecto 4


/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */
package com.sc202.mamando;

import java.util.Scanner;
import javax.swing.JOptionPane;

/**
 *
 * @author B1anq
 */
public class Mamando {

    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        boolean salir = false;
        do {
            System.out.println("(1) Tipo de pago");
            System.out.println("(2) Contribuyente");
            System.out.println("(3) Impuesto");
            System.out.println("(4) Aporte");
            System.out.println("(5) Pago");
            System.out.println("(6) Reporte");
            System.out.println("(7) salir");
            System.out.print("ingrese una opcion");
            int op = reader.nextInt();
            switch (op) {
                case 1:
                    System.out.println("1) Bienvenindo a la seccion de tipo de pago");
                    System.out.println("-----------------------------------------------");

                    break;

                case 2:
                    System.out.println("2) Bienvenindo a la seccion de Contrubuyente");
                    System.out.println("-----------------------------------------------");
                    break;
                case 3:
                    System.out.println("3) Bienvenindo a la seccion de Impuesto");
                    System.out.println("-----------------------------------------------");
                    break;
                case 4:
                    System.out.println("4) Bienvenindo a la seccion de Aporte");
                    System.out.println("-----------------------------------------------");
                    break;
                case 5:
                    System.out.println("5) Bienvenindo a la seccion de Pago");
                    System.out.println("-----------------------------------------------");
                    break;
                case 6:
                    System.out.println("6) Bienvenindo a la seccion de Reporte");
                    System.out.println("-----------------------------------------------");
                    break;

                case 7:
                    System.out.println("7) Salir");
                    salir = true;
                    break;
                default:
                    System.out.println("ingrese dato correcto");
            }

        } while (!salir);
    }
}
