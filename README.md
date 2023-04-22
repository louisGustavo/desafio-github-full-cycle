# Desafio GitHub FullCycle

### Especificação do Desafio

Um dos principais pontos para aumentar segurança e a garantia de que um commit foi realmente realizado por determinado desenvolvedor é a assinatura de commits utilizando GPG.

Nesse desafio, crie um repositório GIT no Github e faça um push de um commit assinado por você.

## Anotações Pessoais sobre a resolução do Desafio

---

Tive um pouco de dificuldade nos primeiros commits, pois como estava usando outro usuário de maneira global no computador, não conseguia modificar o usuário para fazer os commits.

Tentei mudar o usuário somente do repositório pelos comandos

```
git config user.name "louisGustavo"
git config user.mail "luis.gustavo_18@outlook.com"
```

Porém sem sucesso, ele ainda assinava os commits como "louisMascarenhas". Também tentei mudar os dados globais, mas sem sucesso (por isso os primeiros commits tem outra assinatura).

O jeito foi criar uma assinatura de commit para o outro usuário (louisMascarenhas). O que acabou dando certo para os commits seguintes.
