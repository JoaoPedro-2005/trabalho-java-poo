# Java: História, Evolução e Mercado

Uma jornada completa pela linguagem que transformou o desenvolvimento de software — do passado ao presente, da teoria à prática.

---

## 📑 Sumário

* [Origem e História do Java](#origem-e-história-do-java)
* [Principais Versões do Java](#principais-versões-do-java)
* [Ambientes de Desenvolvimento (IDEs)](#ambientes-de-desenvolvimento-ides)
* [O Paradigma Orientado a Objetos (POO)](#o-paradigma-orientado-a-objetos-poo)

  * [Classe — O Molde dos Objetos](#classe--o-molde-dos-objetos)
  * [Objeto — A Instância da Classe](#objeto--a-instância-da-classe)
  * [Encapsulamento — Protegendo os Dados](#encapsulamento--protegendo-os-dados)
  * [Herança — Reutilizando Código](#herança--reutilizando-código)
  * [Polimorfismo — Múltiplas Formas](#polimorfismo--múltiplas-formas)
* [Mercado de Trabalho Java no Brasil](#mercado-de-trabalho-java-no-brasil)
* [Onde o Java é Utilizado](#onde-o-java-é-utilizado)
* [Tecnologias e Frameworks Exigidos](#tecnologias-e-frameworks-exigidos)
* [Conclusão](#conclusão)

---

## Origem e História do Java

### 1991 — O Início

James Gosling, Mike Sheridan e Patrick Naughton iniciam o Projeto Green na Sun Microsystems, com foco em dispositivos eletrônicos.

### 1995 — Lançamento Oficial

Java 1.0 é lançado ao público com a famosa promessa:

**"Write Once, Run Anywhere" — escreva uma vez, rode em qualquer lugar.**

### 2010 — Oracle assume

A Oracle Corporation adquire a Sun Microsystems por aproximadamente **7,4 bilhões de dólares** e passa a ser a responsável pelo desenvolvimento e manutenção do Java.

### Impacto geral

Java democratizou o desenvolvimento multiplataforma e introduziu o gerenciamento automático de memória (**Garbage Collector**), o que reduziu drasticamente erros comuns de programação em linguagens como C++.

---

## Principais Versões do Java

### Java 1.0 (1996)

Versão inicial com a JVM e conceito multiplataforma.

### Java 5 (2004)

Generics, anotações, enums e autoboxing — grande salto na expressividade.

### Java 8 (2014)

Lambdas, Streams e a nova API de datas — versão mais popular da história.

### Java 11 (2018)

Versão LTS com módulos, HTTP Client e melhorias de desempenho significativas.

### Java 17 (2021)

Versão LTS com Records, Sealed Classes e melhorias de desempenho.

### Java 21 (2023)

Virtual Threads, Pattern Matching e recursos modernos de concorrência.

---

## Ambientes de Desenvolvimento (IDEs)

### IntelliJ IDEA

Site: [https://www.jetbrains.com/idea/](https://www.jetbrains.com/idea/)

**Vantagens:**

* Considerada a mais inteligente
* Possui autocompletar avançado
* Refatoração segura
* Excelente integração com frameworks

**Desvantagens:**

* Consome muita memória RAM
* A versão completa (Ultimate) é paga

---

### Eclipse IDE

Site: [https://www.eclipse.org/](https://www.eclipse.org/)

**Vantagens:**

* Gratuita
* Comunidade grande
* Muitos plugins disponíveis
* Padrão em muitas empresas

**Desvantagens:**

* Interface mais pesada
* Considerada menos moderna

---

### Apache NetBeans

Site: [https://netbeans.apache.org/](https://netbeans.apache.org/)

**Vantagens:**

* Fácil para iniciantes
* Boa para aplicações Desktop (Swing/JavaFX)
* Fácil de configurar

**Desvantagens:**

* Evolui mais lentamente
* Possui menos plugins modernos

---

## O Paradigma Orientado a Objetos (POO)

A Programação Orientada a Objetos (POO) é o coração do Java. Em vez de pensar em instruções sequenciais, modelamos o mundo em objetos que possuem características e comportamentos.

Essa abordagem torna o código mais organizado, reutilizável e fácil de manter — essencial em projetos de grande escala.

---

## Classe — O Molde dos Objetos

Uma classe é um molde que define a estrutura e o comportamento de um objeto. Ela especifica quais atributos (dados) e métodos (comportamentos) os objetos dessa classe terão.

### Exemplo de código Java

```java
public class Carro {

    String cor;
    String marca;
    int velocidade;

    public void acelerar() {
        velocidade += 10;
    }
}
```

---

## Objeto — A Instância da Classe

Um objeto é uma instância de uma classe. Enquanto a classe é o molde, o objeto é o resultado concreto criado a partir desse molde.

### Exemplo de código Java

```java
Carro meuCarro = new Carro();
meuCarro.cor = "Vermelho";
meuCarro.marca = "Ferrari";
meuCarro.velocidade = 0;

Carro outroCarro = new Carro();
outroCarro.cor = "Azul";
outroCarro.marca = "BMW";
outroCarro.velocidade = 0;
```

---

## Encapsulamento — Protegendo os Dados

O encapsulamento é o princípio de ocultar os detalhes internos de uma classe e expor apenas o que é necessário.

### Exemplo de código Java

```java
public class Carro {

    private String cor;
    private int velocidade;

    public String getCor() {
        return cor;
    }

    public void setCor(String novaCor) {
        cor = novaCor;
    }

    public void acelerar() {
        if (velocidade < 200) {
            velocidade += 10;
        }
    }
}
```

---

## Herança — Reutilizando Código

A herança permite que uma classe filha herde atributos e métodos de uma classe mãe (superclasse).

### Exemplo de código Java

```java
public class Veiculo {

    protected String marca;
    protected int velocidade;

    public void acelerar() {
        velocidade += 10;
    }
}

public class Carro extends Veiculo {

    private int numPortas;

    public void abrirPorta() {
        System.out.println("Porta aberta!");
    }
}
```

---

## Polimorfismo — Múltiplas Formas

O polimorfismo permite que o mesmo método tenha comportamentos diferentes dependendo do objeto que o chama.

### Exemplo de código Java

```java
public class Animal {

    public void fazerSom() {
        System.out.println("Som genérico");
    }
}

public class Cachorro extends Animal {

    @Override
    public void fazerSom() {
        System.out.println("Au au!");
    }
}

public class Gato extends Animal {

    @Override
    public void fazerSom() {
        System.out.println("Miau!");
    }
}
```

---

## Mercado de Trabalho Java no Brasil

Java segue sendo uma das linguagens mais valorizadas pelo mercado brasileiro, com oportunidades em grandes empresas e startups.

### Salário médio mensal

* **Júnior:** R$ 3.000
* **Pleno:** R$ 6.000
* **Sênior:** R$ 12.000

---

## Onde o Java é Utilizado

Java está em toda parte:

* Back-end Web — construção de APIs e sistemas robustos
* Mobile Android — base histórica do desenvolvimento Android
* Sistemas Financeiros — muito utilizado em bancos
* Big Data — plataformas como Hadoop e Spark
* Sistemas Empresariais — ERPs e CRMs

---

## Tecnologias e Frameworks Exigidos

* Spring Boot
* Hibernate / JPA
* Docker e Cloud (AWS, Azure, GCP)
* Git e Maven
* JUnit e Testes automatizados

---

## Conclusão

Java possui quase 30 anos de história, evolução contínua e uma comunidade gigante. É uma das linguagens mais demandadas por empresas no Brasil e no mundo, e aprender Programação Orientada a Objetos em Java facilita o aprendizado de qualquer outra linguagem.
