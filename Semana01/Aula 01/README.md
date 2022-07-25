# S01 - Aula 01 - A base de tudo

## 🎯 Objetivos:
* Aprender sobre termos e conceitos básicos de programação, as diferentes áreas de tecnologia que usam programação destacando as áreas de frontend e backend;
* Entender o que é uma linguagem de programação e como o javascript se insere neste contexto;
* Ter uma noção dos comandos básicos do terminal; e
* Aprender sobre controle de versão e como utilizar git localmente.
___

## Tópicos
1. [O que é programação? BackEnd/FrontEnd](#programacao)
2. [O que é JavaScript? Por que?](#javascript)
3. [Terminal](#terminal)
4. [Controle de versão - git](#controle-versao)
___

<div id='programacao'/>

## O que é programação ?
- Programação é a atividade de escrever uma sequência de passos lógicos (algoritmos) para resolver um determinado problema e que possa ser entendido por um computador;
- Código é o que utilizamos para escrever os comandos em uma determinada linguagem de programação;
- O computado não pensa, ele só processa dados (entrada) e o resultado do processamento (saída);
- Os conceitos de programação podem ser aplicados utilizando diferentes linguagens e para resolver problemas de diferentes áreas.

### Áreas de tecnologia que lidam com programação
* Engenharia e ciência de dados
* Inteligência artificial
* Desenvolvimento web (frontend e backend)
* Desenvolvimento mobile
* Engenharia Devops

### Como funciona a Web
**Clientes** - dispositivos conectados à internet e qu consomem conteúdos disponibilizados por meio de um navegador (Firefox, Chrome e outros).

**Servidores** - computadores que armazenam páginas, sites ou aplicativos

[Saiba mais como a web funciona](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

### FrontEnd e Backend:
Frontend e Backend são as duas principais áreas do desenvolvimento web. Antigamente uma pessoa desenvolvedora cuidava de tudo, era o famoso webmaster. Com o tempo as tecnologias foram ganhando complexidade e começaram a demandar um nível de especialização cada vez maior, surgiu então a necessidade de criar a separação dessas áreas.

#### Frontend 
É a área voltada para a interação com o usuário. Cuida dos seguintes aspectos:
- Estrutura da página
- Acessibilidade
- Responsividade
- Estilo/Estética
- Captura de informações e ações do usuário
- Envio de informações (requisições) para o backend

#### Backend 
Área voltada para a garantir o funcionamento de uma aplicação por debaixo dos panos:
- Criação de aplicações que permitem a interação com outras aplicações (APIs)
- Captura de informações enviadas pelo front 
- Implementação de regras de negócio
- Persistência de informações em bancos de dados
- Autenticação de usuários
___
<div id='javascript'/>

## O que é JavaScript ?
- Linguagem de programação (Web)
- Alto nível
- Interpretada
- Baseada em protótipo
- Dinamicamente tipada
- Multi-paradigma (imperativo, funcional e Orientado a objetos)
- Versátil (mobile, desktop, TVs, smartwatches, jogos)

#### Para que serve ?
* Roda no cliente servindo para:
  - Capturar ações do usuário;
  - Editar conteúdos e atributos de elementos de uma página;
  - Criar elementos e inseri-los de forma dinâmica;
  - Manipular estilo;
  - Validar valores informados pelos usuários;
  - Fazer operações;
* Também roda no servidor e serve para receber requisições, aplicar regras de negócio e persistir dados em um banco de dados;

#### Por que ?
- Fácil para iniciar (já roda no seu browser, não requer setup complexo)
- A maioria dos sites da web usam JavaScript, logo todo desenvolvedor da web precisa saber
- Consolidada, criada pelas Netscape (1995) e padronizada pela ECMA International (1997)
- Em constante evolução (ES6)
- Bem documentada [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript) e [W3schools](https://www.w3schools.com/jsref/default.asp)

[Veja as linguagens mais populares de 2022](https://survey.stackoverflow.co/2022/#most-popular-technologies-language)
___

<div id='terminal'/>

## Terminal
Comandos básicos do terminal:
- `pwd` - mostrar em que pasta estamos
- `ls` - listar tudo que está dentro de uma pasta
- `cd` - mudar de diretório
- `mkdir` - criar uma pasta/dirertório
- `touch` - criar um arquivo 
- `cat` - mostrar todo o conteúdo do arquivo
- `head` - mostrar o que está no início do arquivo
- `grep` - pesquisar conteúdo em arquivos
___

<div id='controle-versao'/>

## Controle de versão

### Git
O git é um sistema de controle de versão de código aberto amplamente utilizado no mundo. Foi criado em 2005 por Linus Torvalds, também criador do kernel do Linux. 

Saiba mais sobre o git na sua [documentação oficial](https://git-scm.com/book/pt-br/v2)


**Primeiros comandos:**
- Conhecer a versão do git:
  ```console
    $ git --version
  ```
- Ajuda do git:
  ```console
    git <comando> --help
  ```
- Configuração:
  ```console
    $ git config --global user.name "Fulano de Tal"
    $ git config --global user.email fulanodetal@exemplo.br
  ```
- Listar configurações:
  ```console
    $ git config --list
  ```

**Fluxo de trabalho local:**
1. Inicializar um repositório:
    ```console
      $ git init
    ```
2. Ver status:
    ```console
      $ git status
    ```
3. Adicionar arquivos:
    ```console
      $ git add <nome_arquivo>
      ou
      $ git add <nome_pasta>
      ou
      $ git add .
    ```
4. Registrar versões (commit):
    ```console
      $ git commit -m "Mensagem de commit"
    ```

**Mais comandos:**
* Desfazer alterações:
  - Antes do commit: 
      ```console
        $ git git restore <nome_arquvivo>
      ```
  - Depois do commit: 
      ```console
        $ git restore --staged <nome_arquvivo>
      ```
* Ver histórico de modificações:
    ```console
      $ git log
    ```
* Navegar para uma determinada versão
    ```console
      $ git checkout <identificador_versao>
    ```
