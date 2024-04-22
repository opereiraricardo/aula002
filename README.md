# Guia Básico de Marcação Markdown
Este guia oferece um passo a passo detalhado sobre como utilizar a marcação Markdown para formatação de texto em documentos. Iniciando desde os conceitos básicos, como títulos e parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada tópico é acompanhado por uma descrição simples e exemplos práticos em Markdown, permitindo que os usuários aprendam e apliquem rapidamente a marcação Markdown em seus próprios documentos.

## Títulos
São usados para criar diferentes níveis de títulos em um documento Markdown.

Exemplo:
# Título 1
## Título 2
### Título 3

## Parágrafos
Simplesmente escreva seu texto como parágrafos normais. Não é necessário nenhum tipo de marcação adicional.

Exemplo:
Aqui eu tenho um parágrafo

## Listas
Permitem criar listas ordenadas ou não ordenadas.

Exemplo:
Lista não ordenada:

* Item 1
* Item 2
* Item 3

  Lista Ordenada:

1. Primeiro item
2. Segundo item
3. Terceiro item
  
## Links
Criam links para outras páginas da web.

Exemplo:

[Texto do link](URL) para criar um link.


## Imagens
Inserem imagens em um documento Markdown.

Exemplo:

![Imagem](URL_da_imagem)

![GitHub](https://github.com/opereiraricardo/aula002/assets/7780390/223ae71b-2f18-4bdb-8901-c575c5b47345)


## Ênfase
Permitem enfatizar texto, como itálico, negrito, tachado, subscrito e sobrescrito.

Exemplo:

*texto em itálico* ou _texto em itálico_ para itálico.

**texto em negrito** ou __texto em negrito__ para negrito.

~~Texto em tachado~~ 

Aqui é um texto <sub> subscrito </sub>

Aqui é um texto <sup> sobrescrito </sup>


## Citações em bloco
São usadas para destacar uma citação ou bloco de texto.

Exemplo:

> Isso é uma citação em bloco.


## Linhas horizontais
São usadas para criar uma linha horizontal para separar seções do documento.

Exemplo:

---

## Código
Permitem inserir blocos de código ou destacar código dentro do texto.

Exemplo:

Use crases (\`) para inserir código `inline`.

```
idade = 18
print(f"A idade é {idade}")
```

## Tabelas
Criam tabelas organizadas em colunas e linhas.

Exemplo:

| Cabeçalho 1 | Cabeçalho 2 |
|------------ |------------ |
| Dado 1      | Dado 2      |
| Dado 3      | Dado 4      |


## Listas de tarefas
Criam listas de tarefas que podem ser marcadas como concluídas ou pendentes.

Exemplo:

- [x] Tarefa concluída
- [ ] Tarefa pendente

## Referências
Permitem adicionar notas de rodapé para fornecer mais informações sobre o conteúdo do documento.

Exemplo:

Aqui é um exemplo de marcação em rodapé[^1].

A aula é com o Ricardo[^2].

[^1]: Rodapé: conteúdo inferior do documento.
[^2]: Ricardo: Professor da turma de Git.

## Notas de Rodapé
São usadas para adicionar informações adicionais ou explicativas ao final de um documento.

Exemplo:

Aqui é um exemplo de marcação em rodapé[^1].

A aula é com o Ricardo[^2].

[^1]: Rodapé: conteúdo inferior do documento.
[^2]: Ricardo: Professor da turma de Git.

## Alertas
São usados para destacar informações importantes, como notas, avisos ou mensagens.

Exemplo:

> **Note**
> Esta é uma Nota

> [!NOTE]
> Destaca informações que os usuários devem levar em consideração, mesmo durante a leitura superficial.

> [!IMPORTANT]
> Informações cruciais necessárias para o sucesso dos usuários.

> [!WARNING]
> Conteúdo crítico que exige atenção imediata do usuário devido a riscos potenciais.

