# Projeto: Sistema de Controle de Ordens de Serviço para Oficina Mecânica 🚗🔧
Descrição
Este projeto visa modelar um banco de dados para um sistema de controle e gerenciamento de ordens de serviço (OS) em uma oficina mecânica. O sistema ajuda a gerenciar veículos, clientes, mecânicos, ordens de serviço e a execução dos serviços.

Modelagem de Dados
Entidades Principais
# Cliente 🧑‍💼

Clientes trazem veículos para conserto ou revisão.

Contém informações como código, nome, endereço e contato.

# Veículo 🚗

Veículos pertencem a clientes e são trazidos à oficina para serviços.

Contém informações como placa, modelo, ano e código do proprietário (cliente).

# Mecânico 🔧

Mecânicos são responsáveis pela avaliação e execução dos serviços nos veículos.

Contém informações como código, nome, endereço e especialidade.

# Ordem de Serviço (OS) 📋

Ordens de Serviço são criadas para cada veículo que entra na oficina.

Contém informações como número, data de emissão, valor, status e data de conclusão dos trabalhos.

Cada OS é preenchida por uma equipe de mecânicos que identifica os serviços a serem executados.

# Serviço 💼

Detalha os serviços a serem executados, consultando uma tabela de referência de mão de obra.

Contém informações sobre o valor dos serviços e peças necessários.

# Narrativa de Processos
Cliente traz o veículo à oficina.
Veículo é designado a uma equipe de mecânicos.
Equipe de mecânicos identifica os serviços necessários e preenche a OS.
Valores dos serviços são calculados com base na tabela de mão de obra e valores das peças.
Cliente autoriza a execução dos serviços.
Equipe de mecânicos avalia e executa os serviços.
Status da OS é atualizado até a conclusão do trabalho.

Resumo
Este projeto de modelagem de dados, criado para entrega de trabalho de curso, tem como objetivo criar um banco de dados eficiente para um sistema de gerenciamento de ordens de serviço em uma oficina mecânica. A estrutura permite gerenciar clientes, veículos, mecânicos e ordens de serviço, assegurando a integridade dos dados e facilitando o controle das atividades da oficina.

Marcelo F Silva
https://www.linkedin.com/in/marcelofariadasilva/
