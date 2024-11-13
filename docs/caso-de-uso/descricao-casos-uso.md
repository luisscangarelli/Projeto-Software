## Casos de Uso do Sistema Mikado Gastronomia

### UC-01: Realizar Cadastro de Cliente

| Aspecto | Descrição |
|---------|-----------|
| **Objetivo** | Permitir que o cliente se cadastre no sistema |
| **Ator(es)** | Cliente |
| **Precondições** | Não possuir cadastro prévio no sistema |
| **Fluxo Principal** | 1. Cliente acessa a opção de cadastro<br>2. Sistema exibe formulário de cadastro<br>3. Cliente preenche dados (nome, CPF, CEP, celular, e-mail)<br>4. Sistema valida os dados<br>5. Sistema confirma o cadastro |
| **Fluxo Alternativo (4)** | a. Sistema detecta CPF já cadastrado<br>b. Sistema informa erro ao cliente<br>c. Retorna ao passo 3 |
| **Pontos de Extensão** | N/A |
| **Pontos de Inclusão** | N/A |
| **Pós-condições** | Cliente cadastrado no sistema |
| **Regras de negócio** | - CPF único por cadastro<br>- Email único por cadastro<br>- Celular único por cadastro |
| **Fluxo Exceção** | - Erro de conexão<br>- Dados inválidos |
| **Requisitos não funcionais** | - Interface intuitiva<br>- Tempo de resposta rápido |
| **Autor** | [Luis Felipe] |
| **Data de elaboração** | 13/11/2024 |
| **Versão** | 1.0 |

### UC-02: Registrar Pedido

| Aspecto | Descrição |
|---------|-----------|
| **Objetivo** | Permitir que o garçom registre pedidos dos clientes |
| **Ator(es)** | Garçom, Cliente |
| **Precondições** | - Garçom logado no sistema<br>- Produtos cadastrados no cardápio |
| **Fluxo Principal** | 1. Garçom seleciona mesa/cliente<br>2. Sistema exibe cardápio<br>3. Garçom registra itens do pedido<br>4. Sistema calcula total<br>5. Garçom confirma pedido |
| **Fluxo Alternativo (3)** | a. Cliente solicita alteração do pedido<br>b. Garçom edita pedido<br>c. Retorna ao passo 4 |
| **Pontos de Extensão** | UC-03: Controle de Estoque |
| **Pontos de Inclusão** | Verificação de disponibilidade |
| **Pós-condições** | - Pedido registrado<br>- Cozinha notificada |
| **Regras de negócio** | - Pedido deve ter pelo menos 1 item<br>- Itens devem estar disponíveis no estoque |
| **Fluxo Exceção** | - Item indisponível<br>- Erro de sistema |
| **Requisitos não funcionais** | - Tempo de resposta < 2s<br>- Interface mobile-friendly |
| **Autor** | [Luis Felipe] |
| **Data de elaboração** | 13/11/2024 |
| **Versão** | 1.0 |

### UC-03: Controlar Estoque

| Aspecto | Descrição |
|---------|-----------|
| **Objetivo** | Gerenciar automaticamente o estoque de ingredientes |
| **Ator(es)** | Sistema, Administrador |
| **Precondições** | Ingredientes cadastrados no sistema |
| **Fluxo Principal** | 1. Sistema monitora níveis de estoque<br>2. Sistema atualiza quantidades após pedidos<br>3. Sistema verifica limites mínimos<br>4. Sistema gera alertas quando necessário<br>5. Administrador visualiza status do estoque |
| **Fluxo Alternativo (3)** | a. Estoque atinge limite mínimo<br>b. Sistema notifica administrador<br>c. Administrador realiza reposição |
| **Pontos de Extensão** | N/A |
| **Pontos de Inclusão** | N/A |
| **Pós-condições** | Estoque atualizado |
| **Regras de negócio** | - Alertas em 20% do estoque<br>- Atualização em tempo real |
| **Fluxo Exceção** | - Erro de cálculo<br>- Falha de sistema |
| **Requisitos não funcionais** | - Precisão nos cálculos<br>- Backup automático |
| **Autor** | [Luis Felipe] |
| **Data de elaboração** | 13/11/2024 |
| **Versão** | 1.0 |
