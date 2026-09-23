# Sistema de Compras 🛒

Projeto desenvolvido durante o curso de **Back-end com Java**, no módulo de **Listas e Coleções**.

A aplicação simula um sistema de compras, permitindo cadastrar produtos, armazená-los em uma lista e trabalhar com **ordenação e manipulação de coleções**.

## 📚 Conteúdos praticados

Neste projeto foram aplicados conceitos de:

* **Programação Orientada a Objetos (POO)**
* **Classes e objetos**
* **Encapsulamento**
* **Métodos e atributos**
* **Construtores**
* **Listas (`List`)**
* **ArrayList**
* **Coleções (`Collections`)**
* **Ordenação de listas**
* **`Collections.sort()`**
* **Interface `Comparable`**
* Implementação do método **`compareTo()`**
* Ordenação de objetos de classes criadas no projeto
* Percorrer listas utilizando estruturas de repetição
* Adição, remoção e consulta de elementos em listas

## 💻 Tecnologias utilizadas

* Java
* IntelliJ IDEA
* Git
* GitHub

## 🎯 Objetivo

O objetivo do projeto foi aplicar, na prática, os conhecimentos sobre **listas e coleções em Java**, criando uma aplicação capaz de trabalhar com produtos de um sistema de compras.

Além de armazenar os produtos, o projeto permite compreender como as coleções podem ser manipuladas e ordenadas de acordo com critérios definidos na própria classe.

## 📌 Principais conceitos

### Listas

Foi utilizada a interface `List` para armazenar objetos e a implementação `ArrayList` para criar a lista de produtos.

### Ordenação

A classe `Collections` foi utilizada para realizar operações sobre a lista, incluindo a ordenação dos elementos através do método:

```java
Collections.sort(lista);
```

### Comparable

Para possibilitar a ordenação dos objetos criados no projeto, a classe correspondente implementa a interface `Comparable`.

```java
public class Produto implements Comparable<Produto> {
```

A comparação é definida através do método:

```java
@Override
public int compareTo(Produto outroProduto) {
    return this.nome.compareTo(outroProduto.nome);
}
```

Dessa forma, os objetos podem ser organizados de acordo com o critério definido.

## 📂 Estrutura do projeto

O projeto é organizado em classes Java responsáveis pela representação dos produtos e pelo funcionamento do sistema de compras.

## 🚀 Aprendizados

Este projeto contribuiu para a compreensão prática de como trabalhar com **listas, coleções e ordenação de objetos em Java**, reforçando conceitos de Programação Orientada a Objetos e preparando a base para aplicações maiores no desenvolvimento back-end.

---

**Projeto desenvolvido para fins de estudo durante o curso de Back-end com Java.**
