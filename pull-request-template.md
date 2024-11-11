# Padrão de Pull Request

Para manter a consistência e a clareza nas revisões de código, adotaremos o seguinte padrão para a criação de Pull Requests. Este padrão deve ser seguido para todos os tipos de mudanças, incluindo **features**, **refactors**, **documentação**, etc. No caso de **fixes**, a seção de **Justification** pode ser omitida, pois trata-se apenas de uma correção.

---

#### Template de Pull Request

## Overview

Descreva a tarefa e o que foi implementado. Forneça um contexto breve sobre o problema ou a funcionalidade adicionada.

**Exemplo:**

> Implementação da funcionalidade de busca avançada, permitindo aos usuários filtrar resultados por categoria, data e relevância.

## Changes

Liste ou comente sobre as principais alterações feitas na branch para cumprir os objetivos da tarefa.

**Exemplo:**

- Adicionado componente `AdvancedSearch`.
- Criados filtros por categoria, data e relevância.
- Atualizado o endpoint `/search` para suportar os novos parâmetros.

## Justification

Explique o porquê das mudanças e qual o benefício esperado. Detalhe a necessidade e a utilidade das implementações.

**Nota:** Esta seção não é necessária para **fixes**.

**Exemplo:**

> A busca avançada melhora a experiência do usuário ao permitir que encontrem informações mais relevantes de forma eficiente, atendendo a uma das principais solicitações dos usuários.

## How To Test

Forneça um passo a passo simples para testar o que foi implementado.

**Exemplo:**

1. Faça checkout na branch: `git checkout feature/advanced-search`.
2. Instale as dependências: `npm install`.
3. Inicie a aplicação: `npm start`.
4. Navegue até `/search` e teste os filtros disponíveis.
5. Verifique se os resultados correspondem aos critérios selecionados.

## Screenshots/Videos

Inclua imagens ou vídeos que demonstrem o resultado, caso seja necessário.

**Exemplo:**

![Exemplo de busca avançada](./screenshots/advanced-search.png)

---

## Observações

- Certifique-se de que todas as alterações estão cobertas por testes.
- Revise o código para garantir que não haja conflitos ou erros.
- Atualize a documentação, se necessário.
