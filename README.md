
A função "comparaData", utiliza de dois pârametros, e retorna o maior valor de "Date" 
essa função recebe os parametros do tipo "date" executa uma comparação entre os valores inseridos.
através do método ".getTime()", método que retorna o tempo em milesimos de segundos desde a data 01/01/1970, podemos retonar o maior valor.

já a função "intervaloData" recebe dois parâmetros que também são do tipo "Date", validamos para que a "Data1" seja maior que " Data2"  
comparamos a diferença de datas em milesimos de segundos com a função ".getTime()" e retornarmos convertidos em segundos

por último a função "ConversorData", recebe um parametro (dataAtual), utiliza-se de métodos para isolar as diferentes pripriedades de tipagem de data (mes,ano, etc etc), usa-se a estrutura "IF" para verificar e adicionar 
o valor "0" em cada inicio de números que constitua um unico algarismo (ex: 1/1/0000), após ser contruida retorna a string fomatada.  
