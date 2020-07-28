Arquivo: Geral_Br_prediction.csv contém os resultados da predição do DELPHI
Arquivo: Geral_Br_real_data.csv contém as contagens totais de casos e óbitos.
Arquivo: Parameters_Global.csv contém os parâmetros fitados no modelo.

A faixa de datas é diferente nos dois arquivos, as predições começam a partir do centésimo caso, e terminam na data estipulada para a previsão; os casos começam a partir da primeira contagem, e termina um dia antes do resultado ser levantado.

São filtrados:
Predições com menos de 25% de acordo com os dados (casos totais e óbitos totais).
Localidades com menos de 300 casos
Localidades com menos de 20 novos casos no último dia da média móvel de 7 dias. 

