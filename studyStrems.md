# Streams - NodeJS

## Objetivo
Um das maiores coisas legais do NodeJS "Strems", é utilizado para processar dados ou informações sob demanda, exemplo imagina que voçê tenha um video ou um audio para processar e enviar ele para o cliente , o que voçê faria ? enviaria o arquivo completo contendo 1GB de tamanho para o cliente. Esta não é umas das melhores formas de fazer este tipo de aplicação, e ai que streams do nodejs entra ele cria uma pipeline com 3 componentes o read ou readble onde se encontra a fonte de dados a entrada o transform onde esta situado a parte da tratativa da entrada (readble) o processamento, e temos o write ou writeble, cujo objetivo é dar a saída quando o processo (dado) termina e este é encaminhado para o cliente ou para alguma outra aplicação.
 

