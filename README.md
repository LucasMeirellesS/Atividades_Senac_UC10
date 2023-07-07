# Atividades_Senac_UC10


#Atividade 1UC10

Contexto

Sua empresa venceu a concorrência para desenvolver a nova plataforma de streaming de vídeos, a Cenaflix. Seu gestor organizou um time de desenvolvimento para iniciar o projeto e, após a realização da planning referente a primeira sprint, você foi designado para desenvolver a tela inicial do cadastro de vídeos. Sua entrega deve conter um campo para identificação numérica, um campo para o nome do filme, um campo para a data de lançamento e a categoria à qual ele pertence. A equipe de UX (user experience) desenvolveu o protótipo da tela na qual você deve se basear para a criação da interface de cadastro.

 

Atividade

Desenvolva o primeiro item de um CRUD (create, read, update, delete), que é o cadastro dos dados, usando JDBC (Java Database Connectivity). Sua aplicação deve comunicar-se com o banco de dados “ATIVIDADE1”, encontrado no link Conteúdo > Material complementar, assim como realizar a inserção de dados por meio de uma interface com uso do JFrame Form. Sua interface de cadastro deve estar de acordo com o wireframe que também se encontra no material complementar da atividade. Realize o download desses materiais para realizar a atividade.


# Atividade 2UC10

Contexto

Depois de terminar a primeira sprint e realizar uma nova planning para definir tarefas da segunda sprint, você deverá implementar as demais funcionalidades de um CRUD, ou seja, agora, você deve desenvolver uma funcionalidade de consulta, uma para atualização e outra para exclusão dos dados pertinentes ao cadastro de filmes, além de criar uma aplicação executável como protótipo do projeto. Deve ser possível realizar um filtro dinâmico para a busca de categoria de filmes.

Você também deverá fornecer uma documentação técnica das classes desenvolvidas.

 

Atividade

Realize o download do banco de dados “ATIVIDADE1”, encontrado no link Conteúdo > Material complementar, para realizar esta atividade. Utilize um JTABLE para exibição dos dados cadastrados.

Para a documentação, utilize recursos de JavaDocs nas classes implementadas.

Dica: ao utilizar try-catch nos comandos SQL, crie mensagem sugestivas, caso seja retornado algum erro nos comandos SQL. Por exemplo, caso ocorra falha na inserção de dados, pode aparecer uma mensagem semelhante a “Não foi possível inserir os dados! Por favor, verifique valores digitados!”.



# Atividade 3UC10
Contexto

A empresa Cenaflix deseja ampliar seu ramo de atuação devido ao grande sucesso e agora quer expandir para streaming de áudio, com foco em podcast. Será desenvolvido para isso um módulo para gestão dos cadastros de podcast, a fim de que a equipe do Cenaflix consiga acompanhar e cadastrar as informações da plataforma. A tecnologia mais recomendada nesse caso seria JPA (Java Persistence API), por ser um framework mais seguro, que atualmente tem crescido muito no mercado, e também por ter fácil manutenção.

 

Atividade

Sua interface de cadastro deve estar de acordo com o wireframe que se encontra no material complementar da atividade.

Desenvolva uma aplicação com três telas:

A primeira tela será um login contendo usuário e senha. Ao se conectar, o usuário receberá uma mensagem em um JOptionPane semelhante a essa:
“Olá USUÁRIO, sua permissão é de TIPO_DE_USUÁRIO. Seja bem-vindo!”

Você terá que criar pelo menos três tipos de usuários diferentes, por exemplo: Administrador, Operador e Usuário. Cada usuário terá permissões diferentes, tais como:

Administrador: cadastrar, excluir e listar
Operador: cadastrar e listar
Usuário: listar
Dica: utilize a propriedade .setEnabled( ) para desabilitar, segundo a permissão de acesso de cada usuário, a visibilidade do botão ou menu que leva às telas desenvolvidas. Defina essa propriedade junto à mensagem que o usuário recebe ao se conectar.

A segunda tela será um cadastro do repositório de podcast, contendo os campos: ID, produtor, nome do episódio, nº do episódio, duração e URL do repositório.
A terceira tela será uma listagem de todos os dados cadastrados.
Realize a criação de um filtro por produtor.


# cenaflix_bd.sql
Banco de dados utilizado para a realização das atividades.
