## TAREFA- 2


### Com base neste arquivos foi definido um trabalho, o qual foi trabalhado de forma mais especifica com cada junção dos arquivos:
1 - genome_scores X genome-tags (4 colunas resultantes)
	> quantidade de registros resultantes ?
	> quantidade de registros com relevancia maior que 0.5 ?
	> grave 1 arquivo csv com separador ';' - qual o tamanho do arquivo em bytes ?
	> salvando de novo com compressão gzip, qual o tamanho do arquivo em bytes ?
	> faça um comparativo de tempo entre a gravação entre os dois arquivos.

2 - (genome_scores X genome-tags) x movies (6 colunas resultantes)
	> qual a quantidade de registros ?
	> qual o filme que tem a tag com a maior relevancia ?
	> considerando apenas relevância acima de 0.5, quantos registros aparecem ?
	> grave 1 arquivo csv com separador ';' - qual o tamanho do arquivo em bytes ?
	> ao salvar com compressão gzip, qual o tamanho do arquivo em bytes ?
	> faça um comparativo de tempo entre a gravação entre os dois arquivos.
	> nome dos cinco filmes com maior quantidade de tags ?

3 - movies X links (5 colunas resultantes)
	> quantidade de registros resultantes ?
	> grave o DF num arquivo parquet com compressão padrão. qual o tamanho do arquivo em bytes ?
	> e utilizando compressão gzip, qual o tamanho do arquivo em bytes ?
	> faça um comparativo de tempo entre a gravação entre os dois arquivos.
	> inclua duas colunas, cada uma com o link completo das páginas IMDb e The Movie Database de cada filme.
	> guarde este DF em 1 arquivo parquet com compressão padrão.

4 - ratings
	> levante a frequência das notas, ou seja, quantas vezes cada uma aparece no DF, e coloque em ordem crescente de notas

5 - movies X ratings (5 colunas)
	> quantidade de registros considerando também aqueles que não têm avaliação ?
	> quantidade de filmes sem avaliação ?
	> considerando inclusive os filmes sem avaliações, grave 1 arquivo parquet com compressão snappy, qual o tamanho do arquivo em bytes ?
	> com compressão gzip, qual o tamanho do arquivo em bytes ?
	> faça um comparativo de tempo entre a gravação entre os dois arquivos.
	> entre os filmes sem avaliação, qual o código do filme que possui o título mais estenso ?
	> e o código do filme com título mais curto ?
	> entre todos os filmes, qual o código do filme com título mais estenso ?
	> calcule a nota média dos filmes. qual o melhor classificado ? com quantas avaliações ?
	> avalie o resultado.
	> considerando apenas os filmes com mais de 50 avaliações, qual a média do melhor classificado? com quantas avaliações ?
	> grave este DF em formato parquet com compressão padrão.

6 - movies X tags (6 colunas resultantes)
	> o que representa o cruzamento entre estes dois dataframes ?
	> grave 1 arquivo em formato parquet e compressão gzip. qual o tamanho deste arquivo em bytes ?
	> utilizando compressão snappy, qual o tamanho deste arquivo em bytes ?
	> faça um comparativo de tempo entre a gravação entre os dois arquivos.
	> verifique se incluiu no dataframe os filmes sem tags. 
	> o DF completo (incluindo filmes sem tags), tem quantos registros ?
	> considerando apenas filmes com tags, quantos registros são ?
	> considerando apenas filmes com tags, quantos filmes são ?
	> quantos filmes não receberam tags ?
	> entre os filmes sem tags, qual o id do filme com o título mais estenso ?
	> entre os filmes sem tags, qual o id do filme com o título mais curto ?
