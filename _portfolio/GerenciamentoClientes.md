---
title: "Projeto Gerenciamento de Clientes"
excerpt: "Sistema de Cadastro, Leitura, Atualização e Exclusão (CRUD) de clientes, desenvolvido com o framework Django para gerenciamento de informações dos clientes de forma simples e eficaz.<br/><img src='/images/gerenciador_clientes.png'>"
collection: projects
permalink: /projects/GerenciamentoClientes/
---

## Descrição
Este projeto consiste em um sistema de Cadastro, Leitura, Atualização e Exclusão (CRUD) de clientes, desenvolvido como uma aplicação web utilizando o framework Django. O sistema permite ao usuário gerenciar clientes, com a capacidade de adicionar, editar, visualizar e excluir registros de forma simples e eficaz.

---
## Funcionalidades Principais
Adicionar Cliente: Permite cadastrar novos clientes no sistema, incluindo informações como nome, email e telefone. O campo "status" do cliente é automaticamente atribuído como "Ativo" no momento da criação.
Listar Clientes: Exibe todos os clientes cadastrados, com possibilidade de visualizar suas informações detalhadas.
Editar Cliente: O administrador pode editar as informações de um cliente já existente, como nome, email, telefone e status.
Excluir Cliente: Permite excluir clientes do sistema.

---
## Tecnologias Utilizadas
Django: Framework web em Python utilizado para o desenvolvimento do backend, incluindo o gerenciamento do banco de dados e a criação das views, models e formulários.
HTML e CSS: Usados para estruturar e estilizar as páginas da aplicação, proporcionando uma interface simples e funcional.
Bootstrap: Framework CSS utilizado para tornar a interface responsiva e melhorar a aparência do layout, sem a necessidade de escrever CSS do zero.

---
## Como Funciona
O sistema utiliza um banco de dados relacional (gerenciado pelo Django ORM) para armazenar as informações dos clientes.
O formulário de adicionar cliente automaticamente atribui o status "Ativo" ao cliente sem precisar que o usuário altere o valor.
A interface é simples e clara, com páginas para adicionar novos clientes, listar clientes cadastrados e realizar as operações de edição e exclusão.

---

## Código no GitHub
O código-fonte completo está disponível no repositório:
[GitHub - CRUD de Clientes com Django](https://github.com/AndersonCarvalho96/gerenciamentoclientes/){:target="_blank"}
