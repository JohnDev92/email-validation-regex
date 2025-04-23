# Padrão de Validação de Endereços de E-mail

## 1. Descrição

Este documento descreve o padrão utilizado para validar endereços de e-mail em sistemas de cadastro e outras aplicações. O objetivo principal é assegurar que os endereços de e-mail fornecidos pelos usuários possuam um formato válido, aderindo às convenções comuns e requisitos técnicos. A validação é realizada através da aplicação de expressões regulares (regex), uma ferramenta eficaz para a correspondência de padrões em texto.

Este padrão foi desenvolvido como parte de um projeto de intervenção para solucionar a dificuldade de uma equipe de desenvolvimento na validação de e-mails.

## 2. Expressão Regular

A seguinte expressão regular é utilizada para a validação do formato do endereço de e-mail:

```regex
^(?![.])[a-zA-Z0-9!#$%&'*+\/=?^_`{|}~.-]+@(?:[a-zA-Z0-9-]+\.)+[a-zA-Z]{2,}$

