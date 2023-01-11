# DesafioMIA_dados_ancine
Projeto feito como uma das atividades do Bootcamp de Dados MIA (Mulheres em Inteligência Artificial). O foco aqui foi a análise dos rendimentos dos filmes presentes na base.

Os dados utilizados são disponibilizados pela Agência Nacional do Cinema (ANCINE). Este conta com as seguintes colunas:
TITULO_ORIGINAL: String – Nome original do filme
TITULO_BRASILEIRO: String – Nome do filme no Brasil
GENERO: String Genero do Filme, podendo ser Ficção, Animação, etc.
PAIS_ORIGEM: String País de Origem da produtora do filme
CPB_ROE: String Código do Filme
COPIAS: Numero inteiro -  Quantas cópias foram distribuidas
SALAS: Numero inteiro – Quantas salas de cinema passaram o filme
DT_INICIO_EXIBICAO: Data – Data de estréia do filme no Brasil
DT_FIM_EXIBICAO: Data – Data da ultima sessão do filme no Brasil
PUBLICO: Numero inteiro Quantidade de expectadores
RENDA: Numero com decimais: Valores arrecadados com bilheteria
RAZAO_SOCIAL_DISTRIBUIDORA: String – Nome da distribuidora
REGISTRO_DISTRIBUIDORA: Numero inteiro – Numero do registro na Ancine
CNPJ_DISTRIBUIDORA: String – CNPJ da distribuidora
ANO_CINEMATOGRAFICO: Numero – Ano da produção


Para a pergunta proposta no Desafio Cinematográfico, "Existe algum padrão em filmes que tem alta renda?", meu grupo optou pelo caminho da análise multivariada. O presente repositório é um exercício de estratégias de modelagem, levando em considerção a importância da análise de resíduos para a avaliação de adequabilidade e interpretabilidade dos modelos.
Além dos arquivos de dados, os três notebooks contém o histórico das tentativas. O ponto de partida é regressão linear múltipla, seguida da transformação logarítmica da informação de rendimento dos filmes à regressão linear múltipla com a exclusão de outliers. Por fim, temos a regressão logistica. 
