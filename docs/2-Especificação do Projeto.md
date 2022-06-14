# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.


## Personas

1- Mariana de 13 anos, jovem poços caldense, cursou todo o seu ensino funtamental em escolas públicas da cidade.
Sempre se dedicou muito e gosta de estudar mais do que os outros colegas da sua idade, talvez pela referência da mãe professora do ensino médio. 
E tendo isso como base de sua formação, Mariana sempre quis um ensino médio de qualidade e por isso, se dedicou muito para
conseguir umas das concorridas vagas em escolas particulares da cidade, e ela o alcançou entrando na escola Objetivo.
Chegando lá Mariana viu que outros como ela gostavam muito de ler, e alguns adptetos do tradicional livro físico ao invés do e-book, e conversando com um desses colegas ela percebeu que muitos livros mencionados por ele, eram os que ela gostaria de ler, porém não tinha como comprar todos naquele momento, Porém ficou pensando mais quantos colegas como aquele teriam livros guardados no fundo da gaveta que ela gostaria de ler.

2- Júlia, 17 anos, menina, reside em Poços de Caldas, estudante do terceiro ano do ensino médio no Colégio Objetivo. Gosta muito de ler, por esse motivo está em dúvida entre fazer faculdade de Jornalismo ou Direito. No seu tempo livre além de ler, gosta muito de sair com suas amigas para irem ao parque ou assistir filme. Por problemas financeiros dos pais não está conseguindo manter suas compras mensais de livros, gostaria de uma forma de trocar livros que ela já leu por novas histórias.

3- Marcelo tem 29 anos e trabalha como professor de português, sempre incentivou seus alunos a lerem diariamente. Trabalha de segunda a sexta das 07:00 às 14:00 no colégio e das 17:00 às 20:00 da aula particulares para alunos que se preparam para o ENEM. No final de semana aproveita para planejar as aulas da próxima semema, para sair com os amigos, e geralmente todos aos domingos vai almoçar na casa da mãe. Como grande incentivador  da literatura gostaria de poder apresentar aos alunos suas obras favoritas. Acredita que a ideia do aplicativo de troca de livros, mais alunos terão  mais acesso à diversidade de obras.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Pesquisar livros no banco          | Poder realizar minhas trocas           |
|Usuário do sistema  | Acessar meus livros disponíveis    | Para adicionar, alterar e excluir      |
|Usuário do sistema  | Acessar tópicos da comunidade      | Poder interagir com outros leitores    |
|Usuário do sistema  | Acessar meu histórico de trocas    | Analisar as trocas anteriores          |
|Administrador       | Acessar relatório de trocas        | Analisar dados recolhidos semanalmente |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário realize seu cadastro | ALTA | 
|RF-002| Permitir que o usuário cadastre, altere e remova os livros que deseja trocar   | ALTA |
|RF-003| Buscar e filtrar os livros do banco de livros disponíveis   | ALTA |
|RF-004| Propiciar um sistema de interação entre os usuários   | MÉDIA |
|RF-005| Permitir que o usuário personalize seu perfil e altere seus dados   | MÉDIA |
|RF-006| Estabelecer o contato entre os usuários que realizarão a troca através de um chat  | ALTA |
|RF-007| Exibir histórico de trocas   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser desenvolvido utilizando WordPress | ALTA | 
|RNF-002| O sistema deve ser responsivo para ter compatibilidade mobile |  ALTA | 
|RNF-003| O sistema deve possuir conexão com um banco de dados  |  ALTA | 
|RNF-004| O sistema deve estar hospedado em um servidor online  |  MÉDIA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de back-end       |
|03| O sistema deve possuir interface básica e intuitiva   |

