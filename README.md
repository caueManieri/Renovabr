# Renovabr
		PLANILHA RESULTADOS
	Assim que abri o arquivo no excel antes de começar, notei que em diversas colunas (como: DT_GERACAO,HH_GERACAO,ANO_ELEICAO, CD_TIPO_ELEICAO, NM_TIPO_ELEICAO, CD_PLEITO, DT_PLEITO, NR_TURNO, CD_ELEICAO, DS_ELEICAO, SG_UF) os dados se repetiam de cima a baixo, portanto, excluí-las para maior facilidade de manipulação dos dados que serão necessários. Também apaguei o códigos do município e mantive apenas o nome do mesmo.
	Quando fui abrir o arquivo no python usando a biblioteca pandas, notei erro na linha 377833 do arquivo, na mesma, na coluna "NM_VOTAVEL" o nome "NELISIA," era o erro, pois o pythom entendia como uma quebra de célula. Então voltei no excel e substituí todas as células que continham "," como por exemplo os nomes "NELISIA," e "MARKIM, O FRANCANO", pelo mesmo sem a vírgula. Após isso, abri a tabela com python.
	Após a edição do dados no python, reabri o excel para fazer o gráfico dos resultados usando a opção "obter dados" do arquivo que eu salvei ocm Python.
	Como haviam muitos caracteres especiais escritos de maneira incorreta, tentei arrumar isso no proprio python, mas não consegui, então arrumei pelo localizar e substituir do excel.
	Quando tentei usar o PROCV, notei a resposta #N/D, e não consegui entender o porque e nem achar respostas na internet. Passei dias quebrando a cabeça e nada, não consegui cumprir o desafio técnico, peço desculpas.
		
