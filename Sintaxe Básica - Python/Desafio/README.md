# Sistema Bancário Simples em Python

Este projeto implementa um sistema bancário simples que permite ao usuário realizar operações de depósito, saque e visualizar o extrato bancário.

## Funcionalidades

- **Depósito**: Permite ao usuário adicionar dinheiro ao saldo da conta.
- **Saque**: Permite ao usuário retirar dinheiro do saldo da conta, respeitando um limite diário e o número máximo de saques por dia.
- **Extrato**: Exibe todas as transações realizadas (depósitos e saques) e o saldo atual.
- **Sair**: Encerra a execução do programa.

## Regras de Negócio

- O valor do depósito deve ser positivo.
- O valor do saque não pode exceder o saldo disponível.
- O valor do saque não pode ultrapassar o limite definido de R$ 500 por operação.
- O usuário pode realizar no máximo 3 saques por dia.
- O extrato mostra todas as transações realizadas e o saldo final.

## Estrutura do Projeto

- `sistema_bancario.py`: Arquivo principal que contém a implementação do sistema bancário.
- Funções auxiliares definidas no script:
  - `exibir_menu()`: Exibe o menu de opções para o usuário.
  - `depositar(saldo, extrato)`: Função para realizar depósitos na conta.
  - `sacar(saldo, extrato, numero_saques, limite, LIMITE_SAQUES)`: Função para realizar saques da conta.
  - `exibir_extrato(saldo, extrato)`: Função para exibir o extrato de transações.

## Como Executar o Projeto

- Certifique-se de ter o Python instalado em seu sistema. Você pode verificar isso executando `python --version` no terminal.
- Clone o repositório ou copie o arquivo `sistema_bancario.py` para o seu ambiente local.
- Navegue até o diretório onde o arquivo `sistema_bancario.py` está localizado.
- Execute o script usando o comando:

    ```bash
    python sistema_bancario.py
    ```

- Siga as instruções exibidas no terminal para realizar depósitos, saques, visualizar o extrato ou sair do programa.

## Exemplo de Uso

Ao executar o script, o usuário verá o seguinte menu:

    Menu:
    [d] Depositar
    [s] Sacar
    [e] Extrato
    [q] Sair

- O usuário pode digitar `d` para depositar, `s` para sacar, `e` para ver o extrato e `q` para sair do programa.

## Contribuindo

Se você deseja contribuir para o projeto, sinta-se à vontade para entrar em contato comigo. Sugestões e melhorias são sempre bem-vindas!
