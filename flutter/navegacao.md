---
title: Navegação no Flutter
description: Visão geral sobre navegação no Flutter, abordando conceitos, organização de rotas e abordagens utilizadas no desenvolvimento de aplicativos.
keywords: navegação flutter, rotas flutter, navigator flutter, go_router flutter
lang: pt-BR
---

[Início](../index.md) › [Flutter](o-que-e-flutter.md)

## Artigos sobre Flutter

- [O que é Flutter](o-que-e-flutter.md)
- [Material Design 3 no Flutter](material-3.md)
- [Gerência de Estado no Flutter](gerencia-de-estado.md)
- [Navegação em Aplicativos Flutter](navegacao.md)

---



# Navegação no Flutter

A navegação é um dos conceitos fundamentais no desenvolvimento de aplicativos Flutter, pois permite a transição entre telas e a organização do fluxo de uso da aplicação.

No Flutter, a navegação está diretamente relacionada à forma como as telas são estruturadas e como o usuário interage com o aplicativo ao longo do tempo.

---

## Conceito de navegação

De forma conceitual, navegar em um aplicativo Flutter significa **empilhar e desempilhar telas**, controlando qual interface está visível em determinado momento.

Cada tela é representada por um widget, e a navegação define:
- qual tela será exibida
- quando uma tela é aberta
- quando uma tela é encerrada
- como o usuário retorna para telas anteriores

Esse modelo permite criar fluxos simples ou mais complexos, dependendo da necessidade da aplicação.

---

## Navegação com Navigator

O Flutter fornece, de forma nativa, o **Navigator**, responsável por gerenciar a pilha de telas do aplicativo.

Com o Navigator, é possível:
- abrir novas telas
- retornar para telas anteriores
- organizar rotas nomeadas
- controlar o histórico de navegação

Essa abordagem é adequada para aplicações simples ou com fluxos bem definidos.

---

## Navegação declarativa com go_router

Para aplicações com múltiplas telas e fluxos mais complexos, o Flutter oferece bibliotecas como o **go_router**, que adotam uma abordagem declarativa para navegação.

Nessa abordagem:
- as rotas são declaradas de forma centralizada
- a navegação é baseada no estado da aplicação
- a organização do código se torna mais clara em projetos maiores

O livro apresenta o uso do `go_router` como evolução natural da navegação tradicional.

---

## Organização de navegação em projetos

Independentemente da abordagem escolhida, é importante:

- manter as rotas organizadas
- evitar lógica de navegação espalhada pelo código
- separar responsabilidades entre telas e fluxo
- planejar a navegação desde o início do projeto

Essas práticas facilitam a manutenção e a evolução do aplicativo.

---

## Navegação no contexto do livro

No livro **Flutter Aplicado**, a navegação é introduzida de forma progressiva:

- primeiro com navegação básica entre telas
- depois com rotas nomeadas
- e, em seguida, com navegação declarativa usando `go_router`

Cada abordagem é acompanhada por **projetos práticos**, permitindo que o leitor compreenda não apenas o funcionamento, mas também quando utilizar cada solução.

---

## Próximos temas relacionados

Após entender os conceitos de navegação, o estudo avança naturalmente para:

- gerência de estado
- organização de aplicações com múltiplas telas
- integração entre navegação e lógica de negócio

Esses temas são explorados nos capítulos seguintes do livro.
