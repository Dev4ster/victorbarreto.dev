---
title: "Guia Rápido de Markdown"
draft: true
date: 2022-08-27T09:16:45.000Z
description: "Markdown é uma ferramenta poderosa para criar texto rico usando um editor de texto simples. Este guia é uma referência rápida para a sintaxe Markdown."
categories:
  - Desenvolvimento
tags:
  - Markdown
  - Documentação
  - Escrita
---

Este guia rápido de Markdown **fornece** uma visão geral de todos os elementos da sintaxe Markdown. Ele não pode cobrir todos os casos específicos, então se você precisar de mais informações sobre qualquer um desses elementos, consulte os guias de referência para _sintaxe_ básica e sintaxe estendida.

# Títulos

---

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

# Formatação de Texto

---

**Texto em negrito**

*Texto em itálico*

***Texto em negrito e itálico***

~~Texto tachado~~

# Listas

---

## Lista não ordenada

- Item 1
- Item 2
  - Item 2.1
  - Item 2.2
- Item 3

## Lista ordenada

1. Item 1
2. Item 2
   1. Item 2.1
   2. Item 2.2
3. Item 3

## Lista de tarefas

- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Tarefa pendente 2

# Links

---

[Link de texto](https://www.exemplo.com.br)

[Link com título](https://www.exemplo.com.br "Título do site")

URL direta: https://www.exemplo.com.br

# Imagens

---

![Imagem de um gato](cat.jpg)

![Imagem com texto alternativo](https://placekitten.com/200/300 "Gatinho fofo")

# Citações

---

> Esta é uma citação.
>
> > Esta é uma citação aninhada.

# Código

---

Código embutido: `var exemplo = "olá mundo";`

Bloco de código com destaque de sintaxe:

```javascript
function teste() {
  console.log("Olá, mundo!");
}
```

```python
def hello_world():
    print("Olá, mundo!")
```

# Tabelas

---

| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |
|-------------|-------------|-------------|
| Linha 1, Col 1 | Linha 1, Col 2 | Linha 1, Col 3 |
| Linha 2, Col 1 | Linha 2, Col 2 | Linha 2, Col 3 |
| Linha 3, Col 1 | Linha 3, Col 2 | Linha 3, Col 3 |

## Alinhamento em Tabelas

| Alinhado à Esquerda | Alinhado ao Centro | Alinhado à Direita |
|:--------------------|:------------------:|-------------------:|
| Conteúdo            |      Conteúdo      |           Conteúdo |

# Linhas Horizontais

---

Três ou mais hífens, asteriscos ou sublinhados:

---
***
___

# Quebras de Linha

---

Para criar uma quebra de linha,  
termine uma linha com dois ou mais espaços e pressione enter.

# Elementos HTML

---

Markdown também suporta HTML bruto:

<div style="color: red;">
  Este texto será vermelho em HTML.
</div>

# Notas de Rodapé

---

Aqui está uma nota de rodapé [^1].

[^1]: Esta é a nota de rodapé.

# Definições

---

Termo
: Definição para o termo.

Outro termo
: Definição para outro termo.

# Emojis (em alguns flavors de Markdown)

---

:smile: :heart: :thumbsup:

# Referências e Links Úteis

---

- [Guia Básico de Markdown](https://www.markdownguide.org/basic-syntax/)
- [Guia Estendido de Markdown](https://www.markdownguide.org/extended-syntax/)
- [Cheat Sheet de Markdown](https://www.markdownguide.org/cheat-sheet/)

# Conclusão

---

Markdown é uma sintaxe leve e fácil de aprender para formatação de texto. Com apenas alguns caracteres, você pode criar documentos bem estruturados e legíveis que podem ser convertidos em HTML para uso na web.

Espero que este guia seja útil para você começar a usar Markdown em seus projetos! 