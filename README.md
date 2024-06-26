# Aplicação React
Repositório feito para instruir na criação de um projeto React e suas necessidades

# Tópicos
- [Tecnologias usadas do projeto](#tecnologias-usadas-do-projeto)
- [Instalação das Dependências](#instalação-das-dependências)
- [Sobre Github](#sobre-github)
- [Sobre Git](#sobre-git)
- [Sobre NVM](#sobre-nvm)
- [Sobre NodeJS](#sobre-nodejs)
- [Sobre React](#sobre-react)
- [Sobre MaterialUI](#sobre-materialui)


## Tecnologias usadas do projeto
Certifique-se de ter as seguintes dependências intaladas antes de prosseguir:

- Git
- NVM (Node Version Manager)
- Node.js (versão 20)
- VSCode
- React.JS
- Material UI

## Instalação das Dependências

1. **Git:**
   - Você pode encontrar instruções de instalação para o Git em [git-scm.com](https://git-scm.com/).

2. **NVM (Node Version Manager):**
   - Instruções de instalação do NVM podem ser encontradas no repositório oficial do projeto [nvm-sh/nvm](https://github.com/coreybutler/nvm-windows/releases).

3. **Node.js (Versão 20):**
   - Use o NVM para instalar a versão 20 do Node.js:
     ```bash
     nvm install 20
     ```
   - Em seguida, defina a versão recém-instalada como a versão padrão:
     ```bash
     nvm use 20
     ```
 

## Sobre Github
GitHub é uma plataforma de hospedagem de código-fonte que utiliza o sistema de controle de versão Git. Ele oferece recursos de colaboração, como controle de versão, rastreamento de problemas, wikis e integração com várias ferramentas de desenvolvimento. Ele é usado também como portifólio do desenvolvedor, por isso é bom sempre que começar qualquer projeto ou qualquer coisa que tenha pegado para praticar, é bom usar o Github para guarda-los!

Durante o desenvolvimento do projeto só iremos usar o github para clonar o projeto e abrir P.R (Pull request) para a branch de desenvolvimento, se possível, fazer um revisamento no código do colega e enviar para a main após os testes.

Abrir um Pull request é fazer uma solicitação para que alterações sejam aplicadas e revisar o código, como citado, mesclar as alterações na outra branch para que os testes possam ser feitos.

## Sobre Git
Git é um sistema de controle de versão distribuído amplamente utilizado para rastrear mudanças no código-fonte durante o desenvolvimento de software. Ele permite que várias pessoas trabalhem em um projeto simultaneamente e mantém um histórico completo de todas as alterações feitas. Iremos usar o Git justamente para o envio dos arquivos criados e alterados para que todos possam trabalhar no mesmo projeto e fazer atualização do mesmo. 

O Git é uma ferramenta de linha de comando (CLI), embora também possua interfaces gráficas de usuário (GUI) disponíveis. No entanto, a interface de linha de comando do Git é a forma mais comum e poderosa de interagir com o sistema de controle de versão Git. Através da CLI do Git, os usuários podem executar uma variedade de comandos para realizar operações como clonar repositórios, criar branches, fazer commits, mesclar código e muito mais.

Esse códigos serão executados no Terminal da pasta do projeto, para abrir você pode clicar **Windows + X**.

Os seus principais códigos são:
1. **git init**:
   ```bash
   # Inicia um novo repositório Git no diretório atual
   git init
   ```
2. **git clone**:
   ```bash
   # Clona um repositório remoto para o diretório local
   git clone https://github.com/usuario/nome-do-repositorio.git
   ```

3. **git add**:
   ```bash
   # Adicionar mudanças no commit
   git add .
   ```

4. **git commit** (o commit serve para você descrever a alteração que você fez durante o desenvolvimento, mas lembre de sempre ser o mais breve possível... diferente de mim agora):
   ```bash
   # Cria um novo commit com os arquivos preparados no índice
   git commit -m "Mensagem do commit"
   ```


5. **git status**:
   ```bash
   # Mostra o estado atual do diretório de trabalho e do índice, ou seja, o que foi adicionado ou não.
   git status
   ```
6. **git push** :
   ```bash
   # Envia commits locais para o repositório remoto
   git push origin nome-do-branch
   ```
7. **git pull** :
   ```bash
   # Recupera commits do repositório remoto e mescla-os no branch local, ou seja, puxa todas as atualizações mais recentes.
   # Isso facilita não ter conflitos na hora de juntar as branch's.
   git pull
   ```
7. **git checkout** :
   ```bash
   # Cria uma nova branch e muda para ela
   git checkout -b nova-branch

   # Alterna para uma branch existente
   git checkout nome-da-branch
   ```

> **AVISO:** Sempre que criar uma nova branch, vá para a branch main e execute o comando “git pull” para atualizar a main e criar uma nova branch a partir da main.

Após finalizar as alterações no projeto, sempre use “git add .”, “git commit -m ‘alterações feitas’” e, por fim, finalize com “git push”. Todas as linhas de código são executadas no cmd, terminal ou prompt de comando, como preferir chamar!


## Sobre NodeJS
Node.js é uma plataforma de desenvolvimento de software de código aberto que permite executar JavaScript no lado do servidor. Ele usa o motor JavaScript V8 da Google Chrome e é amplamente utilizado para criar aplicativos web escaláveis e de alto desempenho.
A instalação do Node é **ESSENCIAL** para as instalações de bibliotecas e frameworks através do terminal, até mesmo para instalação de dependências após clonar um projeto.

## Sobre NVM
NVM, ou Node Version Manager, é uma ferramenta de linha de comando que permite instalar e gerenciar várias versões do Node.js em um único sistema. Isso é útil para desenvolvedores que precisam trabalhar em projetos que requerem versões específicas do Node.js.
Os comandos que iremos mais usar serão:

1. **Instalação de versões do node** :
   ```bash
   nvm install (versão)
   ```

2. **Listar as versões do node** :
   ```bash
   nvm ls
   ```

3. **Usar versões do node** :
   ```bash
   nvm use (versão)
   ```

> **AVISO:** Certifique-se de seguir as instruções de instalação específicas para o seu sistema operacional. Lembre-se de reiniciar o terminal após a instalação do NVM para aplicar as alterações.

Existem outros comandos, e é sempre bom aprender mais sobre eles. No entanto, esses são os essenciais para o projeto!


## Sobre React
React é um framework usado para desenvolvimneto de código aberto para construir interfaces de usuário. Desenvolvida pelo Facebook, ela permite criar componentes reutilizáveis e declarativos que compõem interfaces de usuário interativas e dinâmicas. Outros exemplos de frameworks são Vue.JS, Next.JS e até mesmo Angular.JS

Após ter baixado as dependências para o projeto como o Node, NVM e Git. Certifique-se que está na versão mais recente do Node
- Digite no terminal o seguinte código:
   ```bash
   nvm install latest
   ```
Instalando a versão mais recente, você irá no site do [React](https://react.dev/learn) para poder se guiar e entender um pouco mais sobre o Framework. Compreendendo sobre o Framework, volte ao terminal.
- Digite no terminal o seguinte código:
   ```bash
   npx create-react-app nome-do-seu-projeto
   ```
Espere instalar e em seguida digite os seguintes comandos como irá aparecer como recomendando no terminal:
   ```bash
   cd nome-do-seu-projeto
   ```
Instale as dependências se necessário:
   ```bash
   npm install
   ```
E por fim, abra seu VSCode pelo terminal digitando:
   ```bash
   code .
   ```
Para iniciar sua aplicação digite no terminal:
   ```bash
   npm start
   ```

## Sobre MaterialUI
Material-UI é uma biblioteca de componentes React que implementa os princípios de design do Material Design, criado pelo Google. Ela fornece uma ampla variedade de componentes prontos para uso, como botões, barras de navegação e tabelas, seguindo as diretrizes de design do Material Design. Isso facilita a criação de interfaces de usuário elegantes e consistentes. Existem diversas bibliotecas de componentes, cada uma específica para um framework. Se você se pergunta se pode existir a mesma biblioteca de componentes para outros frameworks, sim, existe! Apenas muda a forma de instalação e adaptação para o framework.

Depois de fazer a criação da pasta, instalar o framework, agora você irá instalar a biblioteca de componentes do [MaterialUI](https://mui.com/material-ui/). Caso queira usar outra biblioteca de componentes que você tenha visto ou achado interessante, tudo bem mas aplique corretamente.
Para instalar e fazer o uso da biblioteca você deve digitar no terminal do seu projeto o seguinte comando:
   ```bash
   npm install @mui/material @emotion/react @emotion/styled
   ```
Feito isso você poderá usar os componentes que a biblioteca disponibiliza e para isso você pode buscar nesse link dos [Componentes](https://mui.com/material-ui/all-components/).
Se lembre de importar os componentes quando for usa-los no seu projeto, exemplo:

import Button from "@mui/material/Button"

E caso tenha mais de um componente em uso você pode apenas colocar da seguinte forma para deixar o código mais limpo:

import { Button, SnackBar, Checkbox, Select } from "@mui/material"
