# Oficina-dio
Desafio de oficina.
Descrição do Projeto: Sistema de Gerenciamento de Oficina Mecânica

Este projeto é um sistema de gerenciamento para oficina mecânica, que foi modelado e estruturado utilizando o diagrama de banco de dados. O sistema tem como objetivo gerenciar clientes, veículos, ordens de serviço, serviços realizados, peças utilizadas e mecânicos. O diagrama de banco de dados foi criado para ilustrar a estrutura e os relacionamentos entre as tabelas.
Funcionalidades do Sistema

    Cadastro de Clientes: Permite registrar informações sobre os clientes da oficina, como nome, endereço e telefone.
    Cadastro de Veículos: Registra os veículos dos clientes, com dados como modelo, marca e placa.
    Ordem de Serviço: Cria ordens de serviço para cada veículo, vinculando o cliente e o mecânico responsável, além de registrar o status e os serviços a serem realizados.
    Serviços Realizados: Gerencia os serviços que são realizados na oficina, incluindo a descrição, o valor e o tempo de execução.
    Peças Utilizadas: Registra as peças que são utilizadas nos serviços realizados, com informações sobre nome, descrição e valor.
    Mecânicos: Armazena os dados dos mecânicos da oficina, como nome e especialidade.

Relacionamentos entre as Entidades

    1:N (Um para Muitos): Relacionamento entre Cliente e Veículo, onde um cliente pode ter vários veículos.
    1:N (Um para Muitos): Relacionamento entre Ordem de Serviço e Mecânico, onde uma ordem de serviço pode ter vários mecânicos.
    N:M (Muitos para Muitos): Relacionamento entre Serviço e Ordem de Serviço, permitindo que uma ordem de serviço tenha múltiplos serviços e um serviço seja realizado em várias ordens de serviço.
    1:N (Um para Muitos): Relacionamento entre Ordem de Serviço e Peça, onde uma ordem de serviço pode utilizar várias peças.

Estrutura do Banco de Dados

O banco de dados é estruturado em várias tabelas, com chaves primárias (PK) e chaves estrangeiras (FK) para garantir a integridade dos dados. As tabelas principais incluem:

    Cliente
    Veículo
    Ordem de Serviço
    Serviço
    Peça
    Mecânico
    Tabela de Referência de Mão de Obra

Este modelo facilita a gestão eficiente dos dados da oficina, possibilitando consultas rápidas e precisas sobre clientes, veículos, ordens de serviço, serviços e peças utilizadas.
Tecnologias Utilizadas

    Diagramas: Criado no diagrams.net (draw.io) para visualização da estrutura do banco de dados.
    Banco de Dados Relacional: O modelo pode ser implementado em qualquer banco de dados relacional, como MySQL, PostgreSQL, ou SQLite, para armazenar e gerenciar as informações.
