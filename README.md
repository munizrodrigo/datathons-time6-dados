# datathons-time6-dados

## Diretórios

### carga_sp

Dados relacionados a carga no estado de são paulo separado por concessionárias, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém as colunas:
nom_seriehistorica,din_ocorrencia e val_itemserieoriginal. Sendo respectivamente a concessionária, a data e hora e a carga.

### correlacao_e_regressao_linear

Dados relacionados a correlação e regressão linear no estado de são paulo separado por concessionárias e por seus respectivos municípios, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém:
As informações sobre cada regressão linear, com informações de curtose, R quadrado e outros fatores importantes para a compreensão da eficiência da regressão

### distribuidoras_municipios_sp

Dados relacionados a carga e temperatura no estado de são paulo separado por concessionárias, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém as colunas:
data,Carga e o nome dos municípios . Sendo respectivamente data e hora,a concessionária, e temperatura dos diversos municípios apresentados pelo nome da coluna.

### meteorologia_sp

Dados metereológicos no estado de são paulo separado por município, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém as colunas:
Data Medicao;Hora Medicao;PRECIPITACAO TOTAL, HORARIO(mm);UMIDADE REL. MAX. NA HORA ANT. (AUT)(%);VENTO, VELOCIDADE HORARIA(m/s)

### municipios_sp

Dados dos municípios do estado de são paulo, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém as colunas:
codigo_ibge,nome,latitude,longitude,capital,codigo_uf,siafi_id,ddd,fuso_horario. As colunas representam as informações de latitude e longitude, código utilizados pela organização e seu fuso/horário 

### temperatura_sp

Dados relacionados a temperatura no estado de são paulo separado por município, utilizados para os scripts em python para tratamento de dados do (Desafio 2): Análise da relação carga x temperatura para o estado de São Paulo.

Contém as colunas:
id_estacaometeo,id_varmeteo,nom_varmeteo,nom_longo,din_medicao,din_inclusaodl,val_medicao,val_altitude,val_latitude,val_longitude. informaçõs do ponto onde são recolhidas as informações metereológicas e as informações de temperatura e outros valores
