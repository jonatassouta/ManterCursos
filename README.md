# ManterCursos
Desafio/Projeto Final Turma de Formação dotNet Cast Group, Sistema para cadastro de cursos, Feito em Angular para o Front e API Web do ASP.Net Core para Back.

----------------------------------------------------------------
Regras para o Projeto:

Título 01 – Manter Cursos

Prioridade: Média 

Complexidade: Normal

Sendo? SENDO um Administrador

Quero? QUERO cadastrar cursos para a Cast.

Para que? PARA QUE possa cadastrar os cursos disponíveis da Cast.

Critérios de Aceite

Regra: 

- Deve ser acessado pelo menu principal “Curso” da página inicial;
- Deve permitir cadastrar, visualizar, alterar e excluir um curso.
- Devem estar disponíveis os seguintes campos para criação do curso:

   Curso:
   
       Descrição do assunto (obrigatório).

       Data de início (obrigatório)

       Data de término (obrigatório)

       Quantidade de alunos por turma (opcional)

       Categoria (lista em banco de dados)
     
    
   Categorias existentes:
   
       Multiplataforma

       Banco de dados

       Metodologia

       Comportamento

       Comunicação
     
    
-  Não será permitida a inclusão de cursos dentro do mesmo período. O sistema deve
identificar tal situação e retornar um código de erro e a mensagem:
“Existe(m) curso(s) planejados(s) dentro do período informado.”
- Não será permitida a inclusão de cursos com a data de início menor que a data atual.
- Deve ter um botão “Adicionar”, para a inclusão no curso na lista;
- Deve apresentar mensagem de alerta caso o campo não for preenchido;
- Deve ter um botão “Voltar”, para encerrar o acesso e retorno a tela principal;
- Deve apresentar mensagem de alerta de dados gravados com sucesso.
- Deve apresentar mensagem de alerta de curso já cadastrada;
- Deve permitir a pesquisa pelo nome do curso e período que ele ocorre;
- Não deve permitir a exclusão de cursos já realizados;
- Deve registrar em uma tabela de log a data da última atualização, a ação realizada e
usuário responsável;
