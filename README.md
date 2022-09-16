# Escritório de Defesa Agropecuária

*Script* para atualizar a divisão administrativa da Defesa Agropecuária do Estado de São Paulo (https://www.defesa.agricultura.sp.gov.br/).


<iframe width="100%" height="520" frameborder="0" src="https://raw.githubusercontent.com/michelmetran/sp_eda/main/maps/eda_map.html" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


O arquivo ***eda_get_infos.ipynb*** acessa o [*site* da Defesa Agropecuária](https://www.defesa.agricultura.sp.gov.br/enderecos/) que tem os endereços de cada unidade regional e organiza uma tabela com todas as informações.

O arquivo ***eda_create_map.ipynb*** acessa a tabela criada, adiciona uma coluna que armazenará o conteúdo dos *pop-ups* do mapa, gera e salva o mapa.

Script elaborado em 29.04.2021.