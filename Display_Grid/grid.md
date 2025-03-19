# Display Grid
<p> Grade invisível, organizando a página dividida entre linhas e colunas.</p>

---

## Propriedades

- ```display: grid```: tipo de organização do template.
 
- ```grid-template-columns```: define a quantidade de colunas do layout (geralmente, utiliza-se fr).

- ```grid-template-rows```: define a altura de cada linha do layout(geralmente, utiliza-se fr).

- ```grid-template-areas```: organização do grid em áreas definidas como "variáveis", define as linhas e colunas em sua estrutura.

- ```grid-area```: define ao elemento a "variável" a que ele pertence no template.

- ```grid-auto-rows```: define ao tamanho das linhas, independente da quantidade.

- ```repeate()```: recebe como parâmetro a quantidade vezes que irá repetir e a medida, exemplo: repeat(10, 100px).

- ```minmax()```: auxilia na resposividade da página, recebendo como parâmetro o tamanho mínimo e máximo da coluna, exemplo: minmax(200px, 2fr).

- ```columns-gap```: espaçamento entre as colunas dos itens, indicado no container.

- ```row-gap```: espaçamento entre as linhas dos itens, indicado no container.

- ``gap``: espaçamento abrangendo as colunas e linhas dos itens, indicado no container.

