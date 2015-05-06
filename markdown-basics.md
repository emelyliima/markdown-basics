##Marcação Básica 

Markdown permite você escrever usando um formato de texto simples, que se converte em HTML válida para visualização no GitHub.

```
On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.
```

###Escrita Básica

####Parágrafos

Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos seguido por uma ou mais linhas em branco.

```
# The largest heading (an <h1> tag)
## The second largest heading (an <h2> tag)
…
###### The 6th largest heading (an <h6> tag)
```

####Cabeçalhos

Você pode criar um título, adicionando um ou mais símbolos # antes de seu texto de título. O número de # você usa irá determinar o tamanho do cabeçalho.

```
In the words of Abraham Lincoln:

> Pardon my french
```

####Bloco de notas
Você pode indicar o bloco de notas com um >.

```
*This text will be italic*
**This text will be bold**
```

####Texto styling
Você pode fazer o texto em negrito ou itálico. 
Ambos negrito e itálico pode usar um * ou um _ em torno do texto para o estilo. Isso permite que você combinar os dois em negrito e itálico, se necessário.

```
*This text will be italic*
**This text will be bold**
```

###Listas

####Listas não ordenadas
Você pode fazer uma lista desordenada precedendo itens da lista ou com um * ou um -.

```
* Item
* Item
* Item

- Item
- Item
- Item
```

####Listas ordenadas

Você pode fazer uma lista ordenada precedendo itens da lista com um número.

```
1. Item 1
2. Item 2
3. Item 3
```

####Listas aninhadas
Você pode criar listas aninhadas pelo recuo itens da lista por dois espaços.

```
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3
```

###Formatação do código

####Formatos em linha

Use backticks individuais (`) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.

```
Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.
```

####Várias linhas

Você pode usar acentos graves triplos (`` `) para formatar o texto como seu próprio bloco distinta.

```
Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```
```
###Links

Você pode criar uma ligação em linha por envolvimento link texto entre colchetes ([]), e, em seguida, envolver a ligação entre parênteses (()).
Por exemplo, para criar um hiperlink para www.github.com, com um texto de link que diz: Visite GitHub!
