# FitGen - IA para Treinos

Alcance seus objetivos fitness com o **FitGen**, um Personal Trainer com IA! 💪  Responda a algumas perguntas e receba um plano de treino personalizado, com exercícios, séries, repetições, cargas e tempos de descanso, adaptado ao seu perfil e objetivos. Experimente!

## Sumário

* [Introdução](#introdução)
* [Funcionalidades](#funcionalidades)
* [Como Funciona](#como-funciona)
    * [Coleta de Informações](#coleta-de-informações)
    * [Geração do Plano de Treino](#geração-do-plano-de-treino)
    * [Formatação da Saída](#formatação-da-saída)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Como Usar](#como-usar)
* [Limitações](#limitações)
* [Contribuições](#contribuições)
* [Licença](#licença)

## Introdução

Este programa é um Personal Trainer IA que usa a inteligência artificial do Google Gemini para gerar planos de treino personalizados. Ele coleta informações sobre o usuário, como idade, altura, peso, objetivo, experiência e tipo corporal, para criar um plano detalhado, com alongamentos, exercícios, séries, repetições, cargas e intervalos de descanso.

## Funcionalidades

* Coleta informações detalhadas do usuário.
* Gera planos de treino personalizados.
* Apresenta o plano em formato de tabela organizada, separada por dia.
* Inclui sugestões de alongamento.
* Considera a idade, experiência, tipo corporal e objetivo do usuário.
* Utiliza o modelo de linguagem avançado Gemini 1.0 Pro.

## Como Funciona

### Coleta de Informações

O programa coleta informações do usuário através de perguntas interativas, incluindo:

* Nome
* Idade
* Altura
* Peso
* Objetivo de Treino
* Experiência com Treino
* Tipo Corporal
* Dias de Treino por Semana
* Tempo para Alcançar o Objetivo

### Geração do Plano de Treino

Com base nas informações coletadas, o programa usa o modelo Gemini 1.0 Pro para gerar um plano de treino personalizado. O modelo recebe um "prompt" detalhado, com instruções específicas para a geração do plano.

### Formatação da Saída

O programa formata a saída do modelo em tabelas organizadas, separadas por dia de treino, incluindo:

* Dia do Treino
* Exercício
* Número de Séries
* Número de Repetições
* Carga
* Tempo de Descanso

## Tecnologias Utilizadas

* Python
* Google Generative AI
* Modelo de Linguagem Gemini 1.0 Pro
* Biblioteca `tabulate`

## Como Usar

1. Instale a biblioteca `google.generativeai`: `pip install google.generativeai`
2. Substitua `YOUR_API_KEY` no código pela sua chave da API do Google Generative AI.
3. Execute o script Python.
4. Responda às perguntas para fornecer suas informações.
5. O programa irá gerar e apresentar seu plano de treino personalizado.

## Limitações

* O programa não substitui a orientação de um profissional de saúde.
* As sugestões de treino são baseadas em informações gerais.
* Consulte um médico antes de iniciar qualquer programa de exercícios.

## Contribuições

Contribuições são bem-vindas! 

## Licença

MIT License
