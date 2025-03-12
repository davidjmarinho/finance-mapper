# Objetivo da aplicação

Listar e gerenciar as movimentações financeiras de uma pessoa para melhorar o controle financeiro.

# Funções

- Inserir fonte de receita/débitos;
- Listar saídas e entradas de receita;
- Filtrar movimentações por períodos de datas intervaladas (Por exemplo: Dias, Meses e Anos);
- Extrair/Compartilhar relatórios;
- Coletar informações da API OpenBanking;
- Categorizar os tipos de gastos;
- Categorizar os tipos de fontes de receitas (Por exemplo: Mesada, Salário, FreeLance);

# História de usuários

As a [someone] i want to [do something] so that [reach some goal];

- Eu como um usuário quero criar minha conta no aplicativo para acessar a aplicação;
- Eu como um usuário quero autenticar no aplicativo para visualizar a minha movimentação dentro da aplicação;
- Eu como um usuário quero editar minha conta no aplicativo para alterar os meus dados cadastrais;
- Eu como um usuário quero excluir minha conta no aplicativo para que a aplicação seja compliance com a LGPD;
- Eu como um usuário quero inserir minha receita para saber quanto vou poder gastar;
- Eu como um usuário quero visualizar o montante geral da minha conta para saber quanto eu posso gastar ou se está dentro do planejado;
- Eu como um usuário quero visualizar o tipo de de receita por categoria para gerar insights sobre os meus gastos.
  - Por exemplo: Gastei além do que deveria em uma determinada categoria, reduzi o gasto com outras categorias;
- Eu como um usuário quero inserir meus débitos para saber quanto irá subtrair da minha receita;
- Eu como um usuário quero categorizar os meus débitos em recorrentes ou único para que haja recorrência na subtração do valor do débito recorrentemente do montante geral;
- Eu como um usuário quero selecionar o tipo de categoria para o meu débito para separar os débitos por tipagem;
- Eu como um usuário quero adicionar um débito recorrente para constar e substrair da minha receita;
- Eu como um usuário quero remover um débito recorrente para para de substrair da minha receita;
- Eu como um usuário quero alterar um débito recorrente para mudar os dados do débitos (Por exemplo: Alterar data, Categoria, Valor);

# Modelo de Dados

- Eu como um usuário quero inserir minha receita para saber quanto vou poder gastar;
- Eu como um usuário quero visualizar o montante geral da minha conta para saber quanto eu posso gastar ou se está dentro do planejado;
- Eu como um usuário quero visualizar o tipo de de receita por categoria para gerar insights sobre os meus gastos.

Lançamento

- Valor
- Data de criação
- Date de Atualização
- Categoria Id
- Justificativa
- Tipo (Receita, Débito, Crédito)
- Usuário Id

Categoria

- Nome
- Tipo (Receita, Débito, Crédito)
