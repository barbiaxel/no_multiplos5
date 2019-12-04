# no_multiplos5
Números que no son múltiplos de 5, del 1 al 100
package ejercicio7;
//numeros que no son multiplos de 5, del 1 al 100
public class ejercicio7 {

	public static void main(String[] args) {
		int i;
		for (i=1; i<=100; i++) {	
			if (i % 5 != 0) {
				System.out.println(i);
			}
		}

	}

}
