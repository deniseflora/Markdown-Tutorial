# Meu Tutorial para Markdown

## Definição e Aplicações

Segundo *John Gruber* do site [Daring Farinbal](#meu-tutorial-para-markdown), Markdown é uma ferramenta de software, escrita em Perl, que converte um texto simples de marcação leve para XHTML ou HTML estruturalmente válido.
Desenvolvido com o objetivo de facilitar a escrita de textos utilizando símbolos e caracteres. A sua aplicação permite a criação de sites, livros, artigos, slides, documentos técnicos, sendo muito usado para formatar arquivos **README**, em mensagens em fóruns e arquivos *readme.md* do [GitHub](https://github.com/). Arquivos usando a extensão MD são usados principalmente pelo programa Markdown a partir do site oficial [Daring Fireball](Daring Farinbal).

## Títulos

Os títulos são formados inserindo símbolos`#`e um espaço em branco antes do título. São utilizados de 1 a 6 `#` conforme o tamanho do título.  

```bash
# Título 1                              
## Título 2                              
### Título 3                            
##### Título 4                        
###### Título 5                      
###### Título 6    
```  

## Título  1

### Título  2  

#### Título 3

##### Título 4

###### Título 5

###### Título 6

## Parágrafos

Para criar parágrafos basta pular `uma linha` entre os parágrafos.

Exemplo:

```bash
Para formar o primeiro parágrafo basta pular uma linha em branco. 
            
Para formar o segundo parágrafo, também basta pular uma linha em branco. 
```

## Quebras de linha

```sh
Insira dois ou mais espaços após o ponto final.
```

## Estilo do Texto

| Estilo               | Sintaxe| Output
| ------------------------- | ------------|-------------|
| Negrito                 | Texto entre ** ou  entre__    |**Negrito**
| Itálico                 | Texto entre * ou  entre_    |*Itálico*
| Negrito e Itálico  |   Texto entre *** ou ___  | ***Negrito e Itálico***
| Tachado          |  Texto entre ~~    | ~~Tachado~~

## Linha Horizontal

Use 3 ou mais asteriscos `(*)`, hífens `(-)` ou underlines `(_)`.

```bash
***
---
___
```

----
----

## Citações de texto

Usar sinal de maior que ` (>) ` no início do texto.

```bash
>Este é um exemplo de citação do texto. 
```

> Este é um exemplo de citação do texto.
>
Inserir o código entre crases simples ``` (`) ```.
Exemplo:

````sh
O código PHP está escrito entre as tags `<?php ?>`.
````

````sh
O código PHP está escrito entre as tags <?php ?>.

```` 
### Citações de código em bloco
Inserir o código em bloco entre crases triplas `(```)`.

````bash
Exemplo:
 ```javascript
// Function Scope
function myFunction() {
  let carName = "Volvo";    
}
```
````

```javascript
// Function Scope
function myFunction() {
  let carName = "Volvo";    
}
```

## Listas

### Lista ordenadas

Adicione itens com `números seguidos de pontos`. Os números não precisam estar em ordem numérica.

```bash
1. Primeiro Item                                                     
3. Segundo Item                              
2. Terceiro item                               
```

1. Primeiro Item
2. Segundo Item
3. Terceiro item

### Lista não ordenadas

Adicione `(-)`, `(*)` ou `(+)` na frente dos itens. Recue um ou mais itens para criar uma lista aninhada.

   ```sh
- Primeiro item
- Segundo item
- Terceiro item
    - Item recuado
    - Item recuado
- Quarto item
```

- Primeiro item
- Segundo item
- Terceiro item
  - Item recuado
  - Item recuado
- Quarto item
### Lista de Tarefas
É criada com um espaço precedido de um hífen(-) entre colchetes `[ ]`. Para marcar a caixa de seleção como concluída use `[x]`.

```bash
Lista de Tarefas
- [x] Tarefa 1 
- [ ] Tarefa 2
- [ ] Outras
```

Lista de Tarefas

- [x] Tarefa 1
- [ ] Tarefa 2
- [ ] Outras

## Tabelas 
Usar pipes` (|)` para delimitar colunas e linhas. Os hífens `(-)` criam o cabeçalho de cada coluna, também separados por barras.

```bash
| Título 1 | Título 2| 
| ---------| --------| 
| Item     | Item    | 
| Item     | Item    | 
| Item     | Item    | 
| Item     | Item    | 

```

| Título 1 | Título 2|
| ---------| --------|
| Item     | Item    |
| Item     | Item    |
| Item     | Item    |
| Item     | Item    |

### Alinhamento de tabelas

- **Alinhado à esquerda:** `:` no lado esquerdo (padrão);
- **Alinhado à direita:** `:` no lado direito;
- **Centralizado:** `:`dos dois lados.

```bash
| Alinhado à Esquerda  | Centralizado  | Alinhado à Direita |
| :---------------------------- |:---------------:| --------------------:|
| Item                          | Item          |  Item             |
| Item                         | Item           |   Item            |
| Item                         | Item          |    Item           |
```

| Alinhado à Esquerda  | Centralizado  | Alinhado à Direita |
| :---------------------------- |:---------------:| --------------------:|
| Item                          | Item           |  Item               |
| Item                          | Item          |   Item            |
| Item                         | Item           |    Item            |

## Links 
Adicione colchetes `[ ]` seguidos de parênteses `( )`. Dentro dos colchetes insira o título do link e dos parênteses a URL. Links automáticos ficam inseridos entre `< e >`.

```bash
Links automáticos: <URL> 
Link com texto: [Texto](URL). 
```

```sh
Exemplos:

<https://github.com>

[GitHub](https://github.com)

Clique [aqui] (https://github.com) para acessar à página do GitHub.
 ```

<https://github.com>

[GitHub](https://github.com)

Clique [aqui](https://github.com) para acessar à página do GitHub.
## Imagens
```sh
São formadas como os links, adicionando `(!)`no início.
```

! [Título da imagem] (caminho/img.png).
! [Título da imagem] (URL).
[![alt text](image URL)](link URL)

Exemplo de imagem que pode ser usada como link:

[![Mozzila_B2g]( https://wiki.mozilla.org/images/d/df/B2g_wordmark.png)]( https://wiki.mozilla.org/images/d/df/B2g_wordmark.png)

### Emojis

Adicione um emoji digitando:   `:EMOJICODE:`.

Exemplo :
 :calendar:  :pencil: :satellite:  :rocket:

## Notas de rodapé

```bash
Exemplo:
Saiba mais sobre a nota.[^1]

[^1]: Tudo sobre a nota.
```

### Referências

1.[Wikipedia](https://en.wikipedia.org/wiki/Markdown)

2.[Daring Fireball](https://daringfireball.net/projects/markdown/index.text)

3.[Markdown Guide](https://www-markdownguide-org)

4.[GitHub](https://help.github.com/articles/markdown-basics/)
