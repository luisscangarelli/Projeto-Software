# Mikado Gastronomia - Documento de Visão

## Componentes
- Luis Felipe
- Luis Fernando
- Felipe Barbosa
- Thadeu Martins

## Histórico de Versões

| Data | Versão | Descrição | Autor | Aprovado por |
|------|--------|-----------|-------|--------------|
| 28/08/2024 | 1.0 | Inicialização do Projeto | Luis Felipe | Thadeu Martins |

## Sumário
1. [Introdução](#1-introducao)
   1. [Referências](#11-referencias)
   2. [Técnicas de Elicitação Aplicadas](#12-tecnicas-de-elicitacao-aplicadas)
2. [Posicionamento](#2-posicionamento)
   1. [Definição do Problema](#21-definicao-do-problema)
   2. [Posicionamento do Produto](#22-posicionamento-do-produto)
3. [Descrição dos Stakeholders e Usuários](#3-descricao-dos-stakeholders-e-usuarios)
   1. [Stakeholders não Usuários](#31-stakeholders-nao-usuarios)
   2. [Stakeholders Usuários](#32-stakeholders-usuarios)
   3. [Ambiente dos Usuários](#33-ambiente-dos-usuarios)
   4. [Resumo das Principais Necessidades dos Stakeholders](#34-resumo-das-principais-necessidades)
   5. [Alternativas](#35-alternativas)
4. [Visão Geral do Produto](#4-visao-geral-do-produto)
   1. [Perspectiva do Produto](#41-perspectiva-do-produto)
   2. [Premissas e Dependências](#42-premissas-e-dependencias)
5. [Características do Produto](#5-caracteristicas-do-produto)
   1. [Característica 1](#51-caracteristica-1)
   2. [Característica n](#52-caracteristica-n)
6. [Requisitos Funcionais](#6-requisitos-funcionais)
   1. [Requisito 1](#61-requisito-1)
   2. [Requisito n](#62-requisito-n)
7. [Outros Requisitos](#7-outros-requisitos)
   1. [Requisitos Não Funcionais](#71-requisitos-nao-funcionais)
   2. [Outros](#72-outros)
8. [Diagrama de Caso de Uso](#8-diagrama-de-caso-de-uso)
9. [Lista de Anexos](#9-lista-de-anexos)

## 1. Introdução
Este documento tem por finalidade coletar, analisar e definir as principais necessidades do cliente e as principais características do Site. O documento procura demonstrar as características requisitadas pelos interessados e o motivo de sua presença neste.

### 1.1 Referências
[descrever os documentos usados como referência para a Elicitação de requisitos, incluir datas e número de referência dos anexos]

### 1.2 Técnicas de Elicitação Aplicadas
- Entrevistas realizadas com stakeholders 
- Brainstorming com participantes
- Prototipação

## 2. Posicionamento

### 2.1 Definição do Problema

| Aspecto | Descrição |
|---------|-----------|
| PROBLEMA | Gestão Ineficiente de Pedidos |
| AFETA | Erros frequentes, como pedidos duplicados, atrasos na entrega, e falhas na comunicação entre a equipe de atendimento e a cozinha |
| IMPACTO | Redução da Satisfação do Cliente e perda de Eficiência Operacional |
| SOLUÇÃO | Implementar um Sistema Integrado de Gestão |

### 2.2 Posicionamento do Produto

| Aspecto | Descrição |
|---------|-----------|
| PARA | Os clientes e os funcionários do Restaurante |
| QUE | que buscam eficiência e operações mais ágeis e econômicas |
| DIFERENTEMENTE DE | Soluções manuais e processos operacionais lentos e caros |
| NOSSO PRODUTO | Oferece controle centralizado e comunicação eficiente entre equipe e cozinha e cliente com relatórios |

## 3. Descrição dos Stakeholders e Usuários

Esta seção apresenta um perfil dos stakeholders e usuários envolvidos no projeto e os principais problemas que eles entendem que devam ser atacados pela solução proposta.

### 3.1 Stakeholders não Usuários

| Tipo | Descrição | Representantes | Observações |
|------|-----------|----------------|-------------|
| GERENTE | Chefe do Restaurante | José da Silva | Eventualmente solicita os relatórios do sistema |

### 3.2 Stakeholders Usuários

| Tipo | Descrição | Representantes | Observações |
|------|-----------|----------------|-------------|
| CLIENTE | SOLICITA PEDIDOS | | |
| ATENDENTE | RECEBE E DIRECIONA PEDIDOS | LUIS FERNANDO | |

### 3.3 Ambiente dos Usuários

Esta seção apresenta os ambientes possíveis do sistema, como administração, operação, exemplo, ambiente de administradores do Sistema e ambiente de usuários.

#### Cliente:
Neste ambiente o cliente poderá analisar o cardápio, vendo e analisando os produtos disponíveis, podendo acessar também seu histórico de compras

#### Administrativo:
Neste ambiente os administradores irão controlar a disponibilidade dos produtos, terão acesso ao histórico de dados para a tomada de decisão.

### 3.4 Resumo das Principais Necessidades dos Stakeholders

| Necessidade | Prioridade | Impacto | Solução Atual | Soluções Propostas |
|-------------|------------|---------|---------------|-------------------|
| | | | | |

### 3.5 Alternativas
**Concorrentes Diretos: Sistemas de Gestão de Restaurantes**
- **Exemplos**: TOTVS Chef, MarketMan
- **Descrição**: Esses sistemas são amplamente utilizados por restaurantes para gerenciar pedidos, pagamentos e, em alguns casos, o estoque.
## 4. Visão Geral do Produto

### 4.1 Perspectiva do Produto
O sistema para o Restaurante Mikado Gastronomia será uma solução integrada que suporta as principais atividades operacionais e de gestão do restaurante. Através do sistema, a equipe de atendimento poderá registrar e gerenciar pedidos de clientes, que são automaticamente repassados para a cozinha. O sistema permitirá o controle detalhado de estoque, ajustando automaticamente as quantidades conforme os ingredientes são utilizados nos pedidos.

O processo começa com o atendimento ao cliente, onde o garçom utiliza o sistema para registrar os pedidos diretamente em um dispositivo móvel. Esses pedidos são instantaneamente enviados para a cozinha, onde são exibidos em uma tela de gestão de pedidos, facilitando a comunicação e reduzindo erros.

Além disso, o sistema controla o estoque de ingredientes, alertando a equipe sobre a necessidade de reposição e evitando faltas de itens essenciais. O sistema também permite que o gerente configure promoções e ofertas especiais, ajustando automaticamente os preços dos pratos conforme as promoções são ativadas.

Os administradores do restaurante podem utilizar o sistema para gerar relatórios sobre vendas, consumo de ingredientes e desempenho operacional, auxiliando na tomada de decisões estratégicas. O sistema também oferece a possibilidade de integrar-se a sistemas de pagamento e delivery, expandindo as capacidades do restaurante de acordo com as necessidades de crescimento e expansão.

### 4.2 Premissas e Dependências

#### 4.2.1 Gerenciamento de Pedidos em Curso
Presume-se que o sistema conseguirá identificar e gerenciar pedidos em curso de um mesmo usuário, evitando a criação de novos pedidos enquanto o pedido anterior estiver em processamento.

#### 4.2.2 Sistema de Geolocalização
A verificação da área de cobertura para garantir que os pedidos sejam aceitos apenas dentro da área de cobertura definida.

## 5. Características (Features) do Produto

### 5.1 Cadastro do Cliente
Para que o cliente possa se registrar ele deverá informar seus dados: nome, CPF, CEP, celular e e-mail. Não será possível a criação de mais de uma conta por CPF, celular ou e-mail.

### 5.2 Registro do Pedido
O sistema irá registrar o pedido do cliente após o pagamento, já com todas as preferências do usuário acerca de tal produto.

## 6. Requisitos Funcionais

### 6.1 Registro e Gerenciamento de Pedidos
O sistema deve permitir que a equipe de atendimento registre pedidos de clientes utilizando dispositivos móveis. Cada pedido deve ser registrado com detalhes como itens, quantidades e informações do cliente.

### 6.2 Controle de Estoque Automatizado
O sistema deve monitorar o estoque de ingredientes e ajustar automaticamente as quantidades conforme os itens são utilizados nos pedidos. Deve enviar alertas quando os níveis de estoque atingirem o limite mínimo, permitindo a reposição oportuna.

## 7. Outros Requisitos

### 7.1 Requisitos Não Funcionais
1. O sistema deverá disponibilizar um suporte para lidar com problemas e solicitações do cliente.
2. O sistema deve ser um site rápido, didático e eficiente.

### 7.2 Outros
1. Caso o cliente se arrependa ou desista de um pedido terá um botão para o cancelamento do pedido e será feito o reembolso caso esteja dentro das normas fornecidas pelo estabelecimento.
2. Terá uma aba com a opção de acessibilidade caso o cliente necessite.

## 8. Diagrama de Caso de Uso


![Diagrama de Caso de Uso](./diagramas/diagrama-caso-uso.png)

## 9. Lista de Anexos

---

**Data do aceite**: ____________/ __________________ / ________________


_______________________________
**Patrocinador do Projeto**
Nome do Cliente


_______________________________
**Gerente de Projetos**
Nome do Gerente
