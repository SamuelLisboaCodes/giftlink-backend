name: User Story
description: Template para criar user stories no GiftLink
title: "[User Story] "
labels: ["new"]
assignees: ""

body:
  - type: markdown
    attributes:
      value: |
        Preencha os campos abaixo com base na funcionalidade desejada.

  - type: input
    id: role
    attributes:
      label: Como um(a)...
      placeholder: Ex: usuário, visitante, administrador
    validations:
      required: true

  - type: input
    id: goal
    attributes:
      label: Eu quero...
      placeholder: Ex: me registrar no sistema
    validations:
      required: true

  - type: input
    id: reason
    attributes:
      label: Para que...
      placeholder: Ex: eu possa acessar minhas preferências
    validations:
      required: true

  - type: textarea
    id: acceptance
    attributes:
      label: Critérios de aceitação
      placeholder: Ex: O sistema deve salvar o usuário no banco de dados...
    validations:
      required: true
