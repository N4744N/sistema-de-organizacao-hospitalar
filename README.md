# Sistema de gestão hospitalar

Este é um programa desenvolvido em Python para automatizar o cadastro e a organização do fluxo de pacientes em uma unidade de saúde.

## Como funciona?

O projeto atualmente esta em fase de desenvolvimento.
O sistema recebe os dados de novos pacientes através de um formulário web e os armazena de forma estruturada em um banco de dados relacional. A página inicial faz a leitura automática desse banco para listar todas as pessoas cadastradas em tempo real.

O sistema também conta com uma rota dedicada para limpar o histórico de registros, permitindo reiniciar o banco de dados quando necessário.

## Conceitos de programação aplicados

* Desenvolvimento Web com Flask (Rotas GET e POST, renderização de templates e redirecionamento de páginas)
* Banco de dados relacional com SQLite (Criação de tabelas, chaves primárias, restrições de unicidade, inserção e exclusão de dados com comandos SQL)
* Arquitetura MVC básica (Separação entre a lógica do backend em Python e as telas visuais em HTML)

## Como rodar o projeto?

Certifique-se de ter o Python e o Flask instalados em sua máquina
Baixe os arquivos do repositório mantendo a pasta 'templates' no mesmo diretório do script principal
Abra o terminal na pasta do arquivo e execute o comando:
python app.py
