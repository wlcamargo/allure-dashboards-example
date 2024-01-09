# Criar dashboard de Testes com Allure Report

## Tutorial
https://www.youtube.com/watch?v=DpfLjB84EQU&t=266s

## step 1
pip install allure-pytest

## step 2 - Executar teste e salvar "json" na pasta do projeto
pytest --alluredir=AllureReport

## step 3
Adicionar variável de ambiente à pasta bin

## step 3 - abrir a porta do servidor de report
allure serve .\AllureReport\

