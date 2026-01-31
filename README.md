# 🚗 Sistema de Controle de Estacionamento – IFSul

Sistema desenvolvido em **Java**, utilizando **Programação Orientada a Objetos (POO)** e **persistência em banco de dados com JPA**, como parte da disciplina de **Linguagem de Programação Orientada a Objetos (LPOO)** do IFSul.

O sistema tem como objetivo gerenciar **pessoas**, **veículos** e suas **movimentações** em um estacionamento institucional, aplicando conceitos fundamentais da engenharia de software e programação orientada a objetos.

---

## Objetivos do Projeto

- Aplicar os conceitos de **POO** na prática
- Trabalhar com **persistência de dados** utilizando **JPA**
- Desenvolver uma aplicação **desktop com Java Swing**
- Implementar operações de **CRUD** completas
- Utilizar **relacionamentos entre entidades**
- Consolidar o uso de **Enums, herança e polimorfismo**

---

## Conceitos de Programação Utilizados

- Encapsulamento
- Herança
- Polimorfismo
- Classes abstratas e especializadas
- Enumerações (`enum`)
- Relacionamentos entre entidades (`@OneToMany`, `@ManyToOne`)
- Persistência com **JPA (Java Persistence API)**
- Arquitetura em camadas:
  - Model
  - DAO
  - View

---

# Funcionalidades do Sistema
## Gerenciamento de Pessoas

Cadastro, edição e remoção de pessoas

Filtro por nome

Filtro por vínculo

Associação de pessoas a veículos

Persistência em banco de dados

## Gerenciamento de Veículos

Cadastro, edição e remoção de veículos

Associação com proprietários

Identificação de veículos oficiais

Filtro por placa

Filtro por veículos oficiais

Listagem em tabela (JTable)

## Tela Sobre

Informações do sistema

Contexto acadêmico

Identificação da autora

## Galeria de Imagens

Confira as Telas do Sistema:

### - Tela Inicial:
<img width="525" height="421" alt="telaInicial" src="https://github.com/user-attachments/assets/712fe76c-c377-44db-a79b-ea2b8af59953" />

### - Tela de visão de Pessoas:
<img width="442" height="374" alt="visaoPessoas" src="https://github.com/user-attachments/assets/1aa46f06-620d-4b2e-86dc-0fcd0ee2aa7a" />

### - Tela de Cadastro de Pessoas:
<img width="337" height="344" alt="cadastroPessoas" src="https://github.com/user-attachments/assets/cd5a7af4-5a4d-41e4-a6ae-e059577c326f" />

### - Tela de visão de Veículos:
<img width="497" height="544" alt="visaoVeiculos" src="https://github.com/user-attachments/assets/78c127ec-0420-4417-ae76-ec0238d4f313" />

### - Tela de Cadastro de Modelos de Veículos:
<img width="365" height="233" alt="cadastroModelos" src="https://github.com/user-attachments/assets/126a6d7f-f84e-40c4-ac16-e40b0d3094c9" />

### - Tela de Cadastro de Veículos:
<img width="466" height="544" alt="cadastroVeiculos" src="https://github.com/user-attachments/assets/bdf6f9e5-63d1-4827-80cd-84a747a8ac70" />

### - Tela de Movimentações:
<img width="552" height="545" alt="movimentacoes" src="https://github.com/user-attachments/assets/eef8331e-5248-4c58-a324-d0b066b2fdd7" />

### - Tela de Registro de Entrada de Veículo:
<img width="416" height="271" alt="entrada" src="https://github.com/user-attachments/assets/b16f0960-7868-41dd-b9c7-876e06f7ca20" />

### - Tela Sobre:
<img width="543" height="273" alt="sobre" src="https://github.com/user-attachments/assets/a452ce12-8776-49be-a98b-2388a40deabd" />

## Persistência de Dados

A persistência é realizada utilizando JPA, com:

Mapeamento de entidades via anotações

Relacionamentos entre classes

Controle de transações

Operações de CRUD encapsuladas na classe PersistenciaJPA


## Observações

Este projeto possui caráter educacional, com foco na aplicação prática dos conceitos de POO, persistência em banco de dados e desenvolvimento de interfaces gráficas em Java.
