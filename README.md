# Mural-do-Aprendizado
## "O intuito deste repositório é expor meu aprendizado e atualizações constantes em matérias e tecnologias que estarei estudando."  
&ensp;
### *__"Aqui nesta batalha interna, se inicia a guerra de sabedoria entre o eu de agora e o eu de amanhã, na luta constante pela evolução e crescimento pessoal."__*
&ensp;
<center>HTML modelos de Modelos de Layout:</center>

 __1. Box model:__

Trata os elementos como um Box e cada possue 4 edges;

**margin**: parte externa da caixa utilizado para dar espaço entre os elementos.

**border**: linha em volta do conteudo e padding.

**padding**: camada entre conteudo e a borda.

**content**: parte interna. 
&ensp;
<center> box-sizing:</center>

Define como o tamanho total do elemento e calculado considerando o conteudo preenchimento borda  e determina se a dimensão inclue ou não a borda.

**content-box**: valor padrão, leva em consideração apenas o conteudo do elemento para o tamnho total, a borda e o preenchimento não são levados em consideração.

**border-box**: Ja o border-box , leva em consideração o preenchimento e a borda para o calculo total.

**box-sizing**: Permite definir com mais precisão os tamnho total dos elementos evitando que não encaixam nos containers.

&ensp;
__2. Flexbox:__

**Flex-direction**: Define se o comportamento sera em row (linha) ou column (coluna) podendo receber os valores -reverse.

**Justify-content**: alinha no eixo principal sendo seu comportamento padrão na horizontal , porem seu comportamento muda quando se utiliza o flex-direction: column ou reverse, que muda o eixo de orientação. 

**Align-items**:alinha o itens no eixo secundário que se altera junto ao justify-content.

**Flex-wrap**: definira se tera quebra ou não sendo despostas na mesma linha podendo receber o valor wrap,no,e reverse.

**Align-content**: usado para alinhar quando ha mais de uma linha.

**Flex-grow**: define como os item devem crescer em relação aos outros para preecer o espaço disponivel .

**Flex-shrink**: define o quanto devem diminuir de acordo com o espaço disponivel.

**Flex-basis**: define o tamanho base dos itens 

**Flex**:e abreviação dos três ultimos 

**Flex-flow**: abreviação do direction e do wrap 

&ensp;
__3. Grid Layout:__

**Grid-column-start**: especifica a posição de um grid item dentro de uma grid-coluna.

**Grid-column-end**: define onde terminiara a posição grid-item podem receber volores negativos.

_span_ quantas colunas a frente merminara a posição do grid item. quando se usa é relativo ao end e ao start.

**Grid-column**: e a abreviação dos itens anteriores. 

**Grid-row-start**:tem a mesma função do grid-column-start porém em linha.

**Grid-row-end**:tem a mesma função do grid-column-start porém em linha.

**Grid-row**: e a abreviação dos itens anteriores. 

**Grid-area**: abreviação de grid row e column começa row - column termina com row - column.

_order_ é a ordem dos grid items , parecido com o z-index.

**Grid-template-columns**: define o tamnho que sera a coluna e a quantidade  de colunas.
grid-template-columns:100px 3em 40%
**Grid-template-rows**: define o tamnho que sera a linhas e a quantidade  de colunas.
grid-template-columns:100px 3em 40%

_repeat_ define o quanto de linhas sera feito (5,12.5);
_fr_ nova unidade introduzida junto ao grid.

**grid-gap**: faz ter espaços entre as linhas e colunas;