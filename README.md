package main;
import java.util.Scanner;
 
public class Main {
 public static void main(String[] args) {
 
   Scanner leitura = new Scanner(System.in);
 
   Produto p = new Produto();
 
   System.out.println("Suco em pó");
   System.out.println("Tang");
   p.nome = leitura.nextLine();
 
   System.out.println(1.20);
   p.preco = leitura.nextDouble();
 
   System.out.println(10);
   p.quantidade = leitura.nextInt();
 
   System.out.println("Suco em pó"+p.imprimir());
 
   System.out.println("Suco em pó");
   int qtd = leitura.nextInt();
   p.adicionarProdutos(qtd);
   system.out.println(""+ p.imprimir());
 
   system.out.println(10);
   qtd = leitura.nextInt();
   p.removerProdutos(qtd);
   System.out.pirntln("" + p.imprimir());
  }
}
