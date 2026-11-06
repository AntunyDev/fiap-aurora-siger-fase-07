
# SIFSM — Sistema Integrado de Funcionamento e Sustentabilidade de Marte

## Sobre o projeto

O SIFSM é um sistema desenvolvido em Python para auxiliar no monitoramento e gerenciamento dos módulos de uma colônia em Marte.

O sistema permitirá cadastrar, consultar, atualizar e excluir informações dos módulos, além de acompanhar indicadores operacionais e emitir alertas com base em regras definidas.

## Tecnologias

- Python
- Oracle Database
- Biblioteca `oracledb`

## Estrutura do projeto

- `src/`: código-fonte da aplicação
- `sql/`: scripts de criação do banco de dados
- `data/`: dados fictícios para testes
- `docs/`: documentação e planejamento
- `tests/`: testes do sistema

## Como executar

1. Ativar o ambiente virtual.
2. Instalar as dependências com `python -m pip install -r requirements.txt`.
3. Configurar as credenciais do Oracle.
4. Executar `python src/main.py`.

## Status

Em desenvolvimento.
