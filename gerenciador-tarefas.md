usuario

tipo
  descricao * (Nova tarefa, Correção, Análise)

situacao
  descricao * (A fazer (A), Fazendo (A), Feito (F), Testando (F))
  situacao * (Em aberto, Fechado)

prioridade
  descricao * (Baixa, Média, Alta)

projeto
  descricao *

tarefa
  usuario_criador *
  data_tarefa *
  hora_tarefa *
  tipo *
  titulo varchar(200) *
  descricao * text
  situacao *
  prioridade *
  usuario_atribuido

  descricao_novidades text
  data_conclusao
  hora_conclusao

tarefa_adicional
  tarefa *
  descricao * text
  imagem bytea

