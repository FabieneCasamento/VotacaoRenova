# VotacaoRenova

Análise dos dados dos eleitores e candidatos mais votados no primeiro turno da eleição de 2020, no estado de São Paulo.



As colunas que foram removidas, pois neste caso não interferirão na analise do arquivo SP_turno_1.csv foram :
'DT_GERACAO',
'HH_GERACAO',
'ANO_ELEICAO',
'CD_PLEITO',
'DT_PLEITO',
'DT_CARGA_URNA_EFETIVADA',
Sendo a maioria datas e horários da chegada e apuração dos dados. Além dos tipos de eleições:
'CD_TIPO_ELEICAO',
'NM_TIPO_ELEICAO',
'CD_ELEICAO',
'DS_ELEICAO',
'CD_CARGA_1_URNA_EFETIVADA',
'CD_CARGA_2_URNA_EFETIVADA',



No Arquivo perfil_eleitorado_2020.csv foram eliminados da analise também datas e horários da geração dos dados:
'DT_GERACAO',
'HH_GERACAO',
'ANO_ELEICAO',

# análises dos arquivos em python

O arquivo Mapa_votacao_porcidade_final1.ipynb indica os candidatos mais votados para vereador e prefeito. 

Resultados:Mapas com os dados dos prefeitos mais votados em cada município do estado de São Paulo.
mapavoto_municipioSP_Prefeito.html 
mapavoto_municipioSP_vereador.html

Análise por perfil do eleitorado para o voto do primeiro turno para prefeito na cidade de SP.
Perfil_prefeitodeSP_final2.ipynb       


Análise por perfil do eleitorado para o voto do vereador mais votado na cidade de SP.
Perfil_vereador_final3.ipynb


# apresentação

O programa que gerou o arquivo (em pdf) com uma pequena apresentação dos dados é o apresentacao_fabiene.ipynb.

