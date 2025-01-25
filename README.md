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
```

---

## Como Funciona

1. O programa solicita ao usuário que insira um número inteiro.
2. Com base no valor fornecido, ele verifica se o número é divisível por 2:

- Se sim, o número é par.
- Caso contrário, o número é ímpar.

3. O resultado é exibido no console.

---

## Como Executar

### Pré-requisitos

- Certifique-se de que o **Java Development Kit (JDK)** está instalado em sua máquina.
- Um terminal ou IDE que suporte Java.

### Passos para executar:

1 - Clone ou faça o download do repositório:

```java
git clone https://github.com/RenatoDEV87/par-ou-impar.git
cd par-ou-impar
```

2 - Compile o programa:

```java
javac ParOuImpar.java
```

3 - Execute o programa:

```java
java ParOuImpar
```

---

## Exemplo de Execução




