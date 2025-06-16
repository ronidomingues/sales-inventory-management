# sales-inventory-management

### Observações: Este projeto está ainda em desenvolvimento e melhoramentos constantes

### Melhorias futuras pretendidas:
- [ ] Criação de uma interface gráfica usando (PyQt ou Streamlit);
- [ ] Criação do processo de login e autenticações de usuários;
- [ ] Criação de um sistema de criptografia para os dados do banco de dados;
- [ ] Criação de validadores de dados como: CPF, telefone, email, dentre outros;
- [ ] Melhoria e criação de funções novas para a interação com banco de dados, além de simplesmente consultas, cadastro e atualização;

#### Aceito sugestões e ideias para melhoria do projeto, toda colaboração é bem-vinda!

### Objetivos:
- Gerenciamento de estoque de produtos
- Cadastro de clientes
- Cadastro de vendas
- Relatórios de vendas
- Relatórios de produtos com baixo estoque

### Requisitos:
- Python 3.11+
- pip install -r requirements.txt

### Conhecendo o projeto:
- O projeto consiste em um sistema de gerenciamento de estoque de produtos, com cadastro de clientes, vendas e relatórios de vendas e produtos com baixo estoque. Feito em Python, o projeto utiliza um banco de dados SQLite para armazenar os dados.

### Conhecimentos e experiencia adquiridos:
- Python
- Banco de dados SQLite
- Programação orientada a objetos
- Git
- GitHub
- Linux

### Origem e historia:

#### Esse projeto foi uma atividade proposta dentro do treinamento oferecido durante a semana III da [Trilha de Python](https://github.com/ronidomingues/trilha-python-forcode) da [for_code](https://github.com/forcodeufrj)

### Projeto proposto:

**Projeto:**

Sistema de Gestão de Vendas e Estoque

🎯 **Objetivo:**

Criar um programa que gerencie produtos, clientes, funcionários e vendas, controlando o estoque e registrando transações. Ideal para pequenos comércios.

🔧 **Funcionalidades Principais:**

1. Cadastro de Produtos:
   - Código, nome, preço, quantidade em estoque, categoria.
2. Cadastro de Clientes:
   - Nome, CPF, endereço, telefone.
3. Cadastro de Funcionários:
   - Nome, ID, cargo, e registro das vendas feitas por ele.
4. Registrar Venda:
    - Selecionar cliente e funcionário.
    - Adicionar itens ao carrinho (verificar estoque).
    - Atualizar estoque ao finalizar venda.
5.  Relatórios:
    - Total de vendas.
    - Produtos em baixo estoque.
    - Histórico de compras por cliente.