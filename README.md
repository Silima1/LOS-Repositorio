# LOS-Repositorio
Para actividades cientificas
class SouLeo {
public static voin main ( String[] args){
System.out.println(" Sou Leo");
}
package com.leonel.cursojava.aula11;

public class adiçãodeduasvariaveis {

	public static void main(String[] args) {
		int var1 = 2383791;
		int var2 = 25;
		System.out.println(var1+var2);
		

	}

}

package com.leonel.cursojava.aula12;

import java.util.Scanner;

public class leituraDadosTeclado {

	public static void main(String[] args) {
	Scanner scan = new Scanner (System.in); 
	System.out.println("Digite o teu nome completo:");
	String nomeCompleto = scan.nextLine();
	System.out.println(" Seu nome completo é:" + nomeCompleto);
	
	System.out.println("Digite o teu primeiro nome:");
	String primeiroNome = scan.nextLine();
	System.out.println(" o teu primeiro nome é:" + primeiroNome);
	
	System.out.println(" Qual é a tua altura?");
	int idade = scan.nextInt(); 
	System.out.println(" A tua idade é: " + idade);
	
	System.out.println(" Digite: Nome, Sobrenome, idade, Altura, BI, Morada, Distrito, País, Nivel academico");
	String nome = scan.nextLine();
	String sobrenome = scan.nextLine();
    int idade1 = scan.nextInt(); 
	float altura = scan.nextFloat();
	byte bi = scan.nextByte();
	String morada = scan.nextLine();
	String distrito = scan.nextLine();
	String pais = scan.nextLine();
	String nivelacademico = scan.nextLine();
	System.out.println("Nome: " + nome);
	System.out.println("SObrenome: " + sobrenome);
	System.out.println("Idade: " + idade);
	System.out.println("Altura: " + altura);
	System.out.println("Nr de B.I: " + bi);
	System.out.println("Morada: " + morada);
	System.out.println("Distrito: " + distrito);
	System.out.println("País: " + pais);
	System.out.println("Nivel Academico: " + nivelacademico);
	
	
