# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Exemplo: 

Os componentes que fazem parte da solução são apresentados na Figura XX.

![Diagrama de Componentes](img/componentes.png)
<center>Figura XX - Arquitetura da Solução</center>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Canais** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **Preferidas** - lista de notícias mantidas para leitura e acesso posterior
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

> **Links Úteis**:
>
> - [Whimsical](https://whimsical.com/)

Funcionamento do fluxograma que o usuário irá realizar pelo nosso aplicativo.

A imagem a seguir ilustra a o fluxo do usuário em nossa solução. Assim
que o usuário entra na plataforma, ele é apresentado à tela inicial
(Tela 1), onde ele é  recebido com um "Bem-vindo(a)" confrontado com as opções de entrar caso já possua
um cadastro na mesma ou então realizar o cadastro.

Caso opte pela opção "Cadastrar" sera redirecionado(a) para a segunda tela (Tela 2),
onte pode como todas as demais plataformas ter duas opções de cadastro, o manual
preenchendo nome, email, criando uma senha e demais informações ou opatar por entrar com 
o Facebook ou Google. E depois temos uma tela (Tela 2.1) que mostra apenas uma mensagem agredecendo
o usuário pelo cadastro e clicando em concluir ele é direcionado para a tela "Home" (Tela 4).

Caso opte pela opção "Entrar" será redirecionado(a) para a terceira tela (Tela 3),
onde terá a opção de de digitar seu email e a senha castradas para entrar na plataforma
caso já tenha feito o cadastro anteriormente e também lhe são apresentados duas opções,
para facilitar o acesso, opções comuns en outras plataformas qeu são entrar na nossa
plataforma com os dados de uma outra rede social, aqui no caso com o "Facebook" e "Google".
E clicando em entrar é direcionado para a tela "Home" (Tela 4)

Na tela principal, a tela "Home" (Tela 4), temos algumas opções dentro da plataforma,
já aparece a foto do usuário, e quatro opções: 

[1] Buscar Livros - (Tela 5)

    Entrando nessa opção o usuário irá visualizar uma interface onde ele tem um item de busca
    onde pode pesquisar por um livro em específico que gostaria e opções de filtrar os livros
    por gêneros literários facilitando assim a sua busca na plataforma.
    
[2] Meus Livros - (Tela 6)

    Escolhendo essa opção, existe a possibilidade de também de busca por um livro que o 
    próprio usuário já cadastrou. Ele pode adicionar um novo livro no sistema e remover
    um também caso já tenha sido ocorrida a troca.
    E também um registro de todos os livros que foram adicionados, ficando organizando com o 
    título do livro, autor e a data da disponibildiade.
    
[3] Minhas Trocas - (Tela 7)

    Tela onde o usuário verá todas as trocas que foram feitas, com a data, e com quem
    foi realizada essa troca, com os dados dos livros que foram trocados e a possivbilidade
    de busca também de um livro em específico.

[4] Comunidade - (Tela 8)

    Uma aba onde temos um sistema de um rede dentro do próprio sistema para os usuários
    tenham um contato com discussões em uma especie´de forúm e minicomunidades, onde podem
    ser levantados tópicos sobre terminados livros, resenhas, entendimentos e demais itens.
_____________________________________________________________________________________________

## User Flow: Sistema de Biblioteca
![image](https://user-images.githubusercontent.com/101372028/173470243-9b781629-7e96-41d7-b788-5c505f8a0056.png)

Link User Flow (tamanho grande): https://app.flowmapp.com/share/f5fd0adf1169446fe324820c8bf50dcc/userflow/192060/

## Tecnologias Utilizadas

  Como o objetivo do projeto é desenvolver uma interface web que permita interação entre usuários. Dessa forma, será necessário a utilização de um sistema de gestão para a construção e manutenção do site. Para isso, vamos utilizar a ferramenta WordPress que permite a criação de um site responsivo que será compátivel com ambos sistemas operacionais mobile e, além disso, fazer a inserção do plugin Elementor para a construção de toda a parte visual e gráfica do sistema (além de outros plugins). 
  
  Além disso, estabeleceremos a conexão do site com um banco de dados MySQL para guardar todas as informações importantes e extrair dados para análise. Para os recursos que não encontrarmos pré-construídos, vamos implementar alguns códigos em HTML, CSS e Javascript para cumprir com os requisitos. Para a hospedagem do código e dos arquivos, utilizaremos o GitHub.

## Hospedagem

A plataforma foi realizada no Figma e será lançada pelo Wordpress
Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Figma](https://www.figma.com/?fuid=)
> - [Wordpress](https://br.wordpress.org/)

