https://github.com/JOSEEUSTAQUIOSILVERI0/app-card.git

# Projeto de Cartão de Crédito

Este projeto é um formulário de entrada de informações de cartão de crédito desenvolvido em Android, usando `EditText` para capturar os detalhes do cartão, como número, CVV e validade. O layout é responsivo e otimizado para acessibilidade.

## Funcionalidades

- **Número do Cartão:** Campo `EditText` que aceita apenas dígitos, com limite de caracteres.
- **CVV:** Campo `EditText` para o código de segurança com três dígitos.
- **Data de Validade:** Campo `EditText` para entrada da data no formato MM/AA.
- **Acessibilidade:** Todos os campos têm um tamanho de área de toque mínimo de 48dp, conforme as recomendações de acessibilidade do Google.

## Estrutura do Projeto

- **MainActivity.kt**: Arquivo principal da atividade, onde estão implementadas as lógicas para capturar e validar as entradas do usuário.
- **activity_main.xml**: Layout principal com os campos `EditText` para número do cartão, CVV e data de validade.
