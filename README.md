# Par ou Ímpar

Este é um programa em Java que determina se um número inteiro fornecido pelo usuário é **par** ou **ímpar**. O programa utiliza conceitos básicos de Java, como entrada de dados via console e operações aritméticas simples.

---

## Tabela de Conteúdos

1. [Descrição](#descrição)
2. [Código](#código)
3. [Como Funciona](#como-funciona)
4. [Como Executar](#como-executar)
5. [Exemplo de Execução](#exemplo-de-execução)
6. [Tecnologias Utilizadas](#tecnologias-utilizadas)
7. [Contribuições](#contribuições)
8. [Licença](#licença)

---

## Descrição

Este projeto é um exercício introdutório de lógica de programação, desenvolvido para praticar o uso de:
- Estruturas condicionais (`if-else`).
- Operadores aritméticos.
- Entrada de dados com a classe `Scanner`.

O objetivo é ajudar novos desenvolvedores a entenderem os fundamentos da programação Java em um cenário simples e prático.

---

## Código

Abaixo está o código do programa:

```java
import java.util.Scanner;

public class ParOuImpar {
    public static void main(String[] args) {
        // Criando um scanner para ler a entrada do usuário
        Scanner scanner = new Scanner(System.in);

        // Pedindo ao usuário para inserir um número
        System.out.print("Digite um número inteiro: ");
        int numero = scanner.nextInt();

        // Verificando se o número é par ou ímpar
        if (numero % 2 == 0) {
            System.out.println("O número " + numero + " é par.");
        } else {
            System.out.println("O número " + numero + " é ímpar.");
        }

        // Fechando o scanner para evitar vazamento de recursos
        scanner.close();
    }
}

