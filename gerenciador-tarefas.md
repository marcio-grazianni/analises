Características do projeto:
Python - 3.11
Django - 4.1
Postgresql - 15

empresa

usuario

tipo
  descricao * (Nova Tarefa, Correção, Análise)

situacao
  descricao * (A fazer (A), Fazendo (A), Feito (F), Testando (F), Testado (F))
  situacao * (Em aberto, Fechado)

prioridade
  descricao * (Baixa, Média, Alta)

projeto
  descricao * (Simples Varejo, Prático NF-e, Gerenciador do Simples Varejo, Gerenciador do Prático NF-e)

tarefa
  projeto *
  usuario_criador * Desabilitado
  data_tarefa *
  hora_tarefa *
  tipo *
  titulo varchar(200) *
  descricao * text (Fonte monoespaçada)
  situacao *
  prioridade *
  usuario_atribuido
  versao varchar(30)

  descricao_novidades text

  data_inicial
  hora_inicial

  data_conclusao
  hora_conclusao

tarefa_adicional
  tarefa *
  descricao * text
  imagem bytea

