ste projeto consiste em um prgrama que seja capaz de ler arquivos do tipo fasta contendo informaçoes geneticas e classifique elas de acordo com o seu COG de forma a salvar em um novo arquivo fasta com o nome do resoectivo COG contendo suas sequencias e IDs correspondentes

Os arquivos recebidos foram :

EggNog_T_A.xlsx (i) COG_C_T_a.xlsx (ii) Proteome_T_a.faa (iii)

(i) Tabela excel contendo informaçoes de nome dos genes (ID) e categoria COG (Esta tabela foi a que utilizamos para a criação do dicionario) (ii)Tabela excel contendo informaçoes de nome dos genes (ID) e categoria COG (Tabela nao utilizada, irei verificar com o solicitante) (iii) Arquivo contendo as sequencias proteicas de genes de Trichosporon Asahii

Ao final da execução do programa foram gerados 116 arquivos fasta referente as categoricas de COG

Foi feita uma etapa de validação aonde consiste em concatenar os 116 arquivos e contar a quantidade de sequencias a fim, de comparar com o arquivo de teste (Proteome_T_a.faa).

Durante a faze de validação se observou que de 8311 sequencias apenas 5852 foram classificadas. A hipotese sobre este resultado é a tabela usada como "dicionario" não abrangia todas as sequencias.

Conclusão: O programa se mostrou eficiente e conseguiu concluir a demanda. Algumas informações ainda precisam ser descutidas com o solicitante a fim de adicionar mais etapas de validação e adicionar mais informação aos cabeçalhos dos arquivos fasta.
