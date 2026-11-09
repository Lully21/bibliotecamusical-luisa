# 🎵 Sistema Musical

## 📌 Sobre o Projeto

O Sistema Musical é um projeto desenvolvido durante as aulas, com o objetivo de criar um site para organizar artistas e músicas em um só lugar.

A ideia é ter um sistema simples e fácil de usar, onde seja possível cadastrar artistas, adicionar suas músicas e consultar uma biblioteca musical.

O projeto foi desenvolvido utilizando HTML e CSS, colocando em prática os conteúdos aprendidos em sala de aula, como formulários, tabelas, botões, links e organização das páginas.

Nesta primeira etapa, foi criada a parte visual do sistema. Os cadastros e as informações ainda são exemplos fixos, pois a conexão com PHP e MySQL será desenvolvida na próxima etapa.

## 🎯 Objetivo

O objetivo do projeto é desenvolver um sistema que facilite a organização de artistas e músicas, permitindo visualizar as informações e navegar facilmente entre as diferentes páginas.

## 💻 Tecnologias Utilizadas

- **HTML5:** utilizado para criar a estrutura das páginas.
- **CSS3:** utilizado para deixar o sistema organizado e com uma aparência agradável.
- **Flexbox e Grid:** utilizados para organizar os elementos e formulários.
- **Media Queries:** utilizadas para adaptar o site a diferentes tamanhos de tela.

## 📂 Organização dos Arquivos

O projeto possui os seguintes arquivos:

- `login.html` – Tela de entrada do sistema.
- `index.html` – Menu principal com as opções disponíveis.
- `cadastro_artista.html` – Página para cadastrar e visualizar artistas.
- `cadastro_musica.html` – Página para cadastrar e visualizar músicas.
- `listagem_musicas.html` – Biblioteca onde as músicas são apresentadas.
- `styles.css` – Arquivo responsável pela aparência de todas as páginas.
- `README.md` – Arquivo com a descrição e as informações do projeto.

## 🔐 1. Tela de Login

A primeira página do sistema é a tela de login, onde o usuário encontra os campos para informar seu usuário e sua senha.

Também foi adicionada uma área com credenciais de teste para facilitar o acesso durante o desenvolvimento.

**Dados para teste:**
- Usuário: `admin`
- Senha: `123`

Nesta etapa, a tela possui apenas a estrutura visual. A verificação dos dados será implementada posteriormente com PHP e banco de dados.

## 🏠 2. Menu Principal

Depois da tela de login, o usuário encontra o menu principal do Sistema Musical.

Nele existem três opções:

- **Gerenciar Artistas:** para acessar os cadastros dos artistas.
- **Cadastrar Músicas:** para adicionar novas músicas.
- **Biblioteca Musical:** para visualizar as músicas disponíveis no sistema.

Também existe o botão Sair, que permite voltar para a tela de login.

## 🎤 3. Cadastro de Artistas

Nesta página é possível preencher as informações dos artistas, como nome, gênero musical, país e foto.

O formulário possui campos organizados em duas colunas para facilitar o preenchimento.

Abaixo dele, existe uma tabela que apresenta alguns artistas de exemplo, como Djavan e Marisa Monte.

Na tabela também foram adicionados botões de Editar, Excluir e Músicas, que permitem acessar as opções relacionadas a cada artista.

## 🎵 4. Cadastro de Músicas

A página de cadastro de músicas foi criada para adicionar informações sobre as músicas e relacioná-las aos seus artistas.

O formulário possui os seguintes campos:

- Artista.
- Título da música.
- Álbum.
- Gênero musical.
- Link do YouTube.
- Capa do álbum.
- Letra da música.

Alguns campos são obrigatórios, como artista, título e link do YouTube.

Abaixo do formulário, existe uma tabela com exemplos de músicas cadastradas. Também foram incluídos botões para editar e excluir os registros.

## 📚 5. Biblioteca Musical

A Biblioteca Musical é a página onde as músicas aparecem organizadas em uma tabela.

Ela apresenta informações como capa, título, artista, álbum, gênero, link do YouTube e ações disponíveis.

Também foram criados filtros para facilitar a localização das músicas:

- Busca pelo título, álbum ou artista.
- Filtro por artista.
- Filtro por gênero musical.

Além disso, existe um botão para cadastrar uma nova música.

Por enquanto, os filtros estão apenas na parte visual e ainda não realizam buscas de verdade. Isso será desenvolvido na próxima etapa.

## 🎨 6. Estilização do Sistema

Para manter todas as páginas com a mesma aparência, foi criado um único arquivo chamado `styles.css`.

Nele foram definidos os estilos dos formulários, tabelas, botões, títulos, cores, espaçamentos e outros elementos.

As cores foram escolhidas para deixar o sistema organizado e facilitar a identificação das ações:

- Azul para os botões principais e de edição.
- Verde para acessar as músicas dos artistas.
- Vermelho para as opções de exclusão.
- Azul escuro para títulos e cabeçalhos.
- Cinza claro e branco para os fundos.

Também foram adicionados efeitos nos botões e nos cards quando o usuário passa o mouse sobre eles.

## 📱 7. Responsividade

O sistema também foi preparado para funcionar em telas menores, como celulares e tablets.

Para isso, foram utilizadas Media Queries no CSS, fazendo alguns ajustes na organização das páginas.

Entre eles estão a mudança dos formulários para uma coluna, a reorganização dos cards do menu e a possibilidade de movimentar as tabelas para os lados quando necessário.

Assim, o sistema consegue se adaptar melhor a diferentes tamanhos de tela.

## 🚀 8. Próxima Etapa do Projeto

Na próxima etapa, o objetivo será fazer o sistema funcionar de verdade, utilizando PHP e MySQL.

Serão desenvolvidas funcionalidades como:

- Login com verificação de usuário e senha.
- Conexão com o banco de dados.
- Cadastro e armazenamento de artistas.
- Cadastro de músicas relacionadas aos artistas.
- Envio e armazenamento de fotos e capas.
- Edição e exclusão de registros.
- Listagem das informações diretamente do banco de dados.
- Funcionamento dos filtros da biblioteca.

## ✅ Conclusão

O desenvolvimento do Sistema Musical foi uma forma de colocar em prática os conteúdos aprendidos durante as aulas de HTML e CSS.

Durante a criação, foram desenvolvidas diferentes páginas, cada uma com sua função, além da organização dos formulários, tabelas, botões e links para facilitar a navegação.

Essa primeira etapa foi importante para construir a estrutura e a aparência do sistema. Nas próximas etapas, serão adicionadas as funcionalidades com PHP e MySQL, permitindo que os dados sejam cadastrados e armazenados de verdade.

---

**Projeto:** Sistema Musical  
**Etapa:** Desenvolvimento com HTML e CSS  
**Tecnologias utilizadas:** HTML5 e CSS3
