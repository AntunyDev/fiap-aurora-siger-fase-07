
# Planejamento do SIFSM

## 1. Objetivo

Desenvolver um sistema em Python para gerenciar informações operacionais dos módulos de uma colônia em Marte, utilizando banco de dados Oracle.

## 2. Requisitos funcionais

- **RF01 — Cadastrar módulo:** permitir registrar um novo módulo da colônia.
- **RF02 — Listar módulos:** exibir todos os módulos cadastrados.
- **RF03 — Consultar módulo:** buscar um módulo pelo seu identificador.
- **RF04 — Atualizar módulo:** modificar os dados de um módulo existente.
- **RF05 — Excluir módulo:** remover um módulo cadastrado.
- **RF06 — Emitir alertas:** identificar situações que ultrapassem limites definidos.
- **RF07 — Menu de navegação:** permitir ao usuário escolher as operações disponíveis.

## 3. Requisitos não funcionais

- **RNF01 — Linguagem:** o sistema será desenvolvido em Python.
- **RNF02 — Banco de dados:** utilizar Oracle Database.
- **RNF03 — Tratamento de erros:** utilizar `try/except` para lidar com falhas de execução e banco de dados.
- **RNF04 — Organização:** separar conexão, operações CRUD, menu e alertas em módulos distintos.
- **RNF05 — Usabilidade:** apresentar mensagens claras e um menu simples no terminal.

## 4. Estruturas de dados

O sistema utilizará:
- Uma **lista** para armazenar temporariamente os módulos consultados.
- Um **dicionário** para representar os dados de cada módulo em Python.

## 5. Regra inicial de alerta

O sistema deverá emitir um alerta quando o consumo energético de um módulo ultrapassar um limite definido. O valor do limite será estabelecido durante a implementação e utilizado apenas como parâmetro didático.

## 6. Entregáveis

- Código-fonte Python.
- Script SQL de criação das tabelas.
- Dados estruturados para testes.
- Testes das funcionalidades principais.
- Documentação de execução.

