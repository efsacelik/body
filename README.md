# body
It calculates body mass index.

package patikaAcademy;

import java.util.Scanner;

public class vucutKitleEndeksi {

	public static void main(String[] args) {
		
		double  length, mass, indeks;
		
		Scanner input= new Scanner(System.in);
		
		System.out.println("Lütfen boyunuzu metre cinsinden giriniz:");
		length =  input.nextDouble();
		
		System.out.println("Lütfen kilonuzu kg cinsinden giriniz:");
		mass =  input.nextDouble();
		
		indeks= mass/ length * length;
		System.out.print("Vücut Kitle Endeksiniz:" + indeks);
		
	}

}
