# ***Desafio lista no JS***
- Crie uma lista vazia, com o nome listaGenerica.
- Crie uma lista de linguagens de programação chamada linguagensDeProgramacao com os seguintes elementos: 'JavaScript','C','C++', 'Kotlin' e 'Python'.
- Adicione à lista linguagensDeProgramacao os seguintes elementos: 'Java', 'Ruby' e 'GoLang'.
- Crie uma lista com 3 nomes e exiba no console apenas o primeiro elemento.

```js
let listaGenerica = [];
let listaProgramação = ['JavaScript','C','C++','Kotlin','Python'];
listaProgramação.push('Java', 'Ruby', 'GoLang');
console.log(listaProgramação);

let nomes = ['junio bixa', 'augusto gonzaga', 'roberto'];
console.log(nomes[0]);
```
**Sendo sincero**, nesse curso eu peguei ele pela metade, pois eu **não estava entendendo nada**, aí eu tive que ver o primeiro curso, que **não conta horas pro fechamento do Caldeira**, mas felizmente essas **coisinhas básicas** eu já tinha sacado antes do curso 2, então **tô mais tranquilo**. **Única coisa que eu não sei** é o `function`, **esse é uma dúvida gigante** na minha mente.

**Mas bom**, falando sobre o código acima, **basicamente a gente usa o `Array` pra criar uma lista de coisas**, e adiciona um novo conteúdo, chamado `push`, que **nada mais é do que um negócio que eu não sei o nome**, que **ele adiciona coisas à sua lista**. **Pra ser sincero**, eu não sei qual é a **real finalidade dele**, sendo que é **mais fácil adicionar manualmente no array principal**.

**Seguido disso**, nós temos que fazer um array, **mas que ele exiba o item que nós queremos dentro desse array**, pra isso nós usamos **colchetes `[]`** para **conseguirmos exibir no console o que queremos**, **acho que isso tem o nome de `length`**, se eu não estou enganado.

**Acho que no fim das contas**, esse foi o exercício, **bem básico e simples**, graças a Deus. **Não consegui colocar uma gracinha** porque minha criatividade tá **meio merda**, mas é isso aí.

\[Comentário:

* O `push` serve pra **adicionar novos elementos no fim de um array** de forma dinâmica, sem precisar editar diretamente o array original. Isso é muito útil quando você quer montar uma lista aos poucos, com base em eventos ou interações do usuário.

* O que você quis usar com o `length`, na verdade, é **acesso por índice**, usando os colchetes `[]` com o número da posição. Exemplo: `nomes[2]` pega o terceiro nome da lista (porque começa em 0). Já o `.length` serve pra **contar quantos itens tem no array**.

* E o `function` que você mencionou: ele serve pra **criar blocos de código que podem ser reutilizados**. Tipo um mini-programa dentro do seu programa.]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
