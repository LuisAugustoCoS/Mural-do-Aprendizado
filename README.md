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

__3. Grid Layout:__
