# Aplicação React
Repositório feito para instruir na criação de um projeto React e suas necessidades

# Tópicos
1. [Tecnologias usadas do projeto](#tecnologias-usadas-do-projeto)
2. [Instalação das Dependências](#instalação-das-dependências)
3. [Sobre Github](#sobre-github)
4. [Sobre Git](#sobre-git)
5. [Sobre NVM](#sobre-nvm)
6. [Sobre NodeJS](#sobre-nodejs)
7. [Sobre React](#sobre-react)
8. [Sobre MaterialUI](#sobre-materialui)


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

## Sobre Git
Git é um sistema de controle de versão distribuído amplamente utilizado para rastrear mudanças no código-fonte durante o desenvolvimento de software. Ele permite que várias pessoas trabalhem em um projeto simultaneamente e mantém um histórico completo de todas as alterações feitas. Iremos usar o Git justamente para o envio dos arquivos criados e alterados para que todos possam trabalhar no mesmo projeto e fazer atualização do mesmo. 

O Git é uma ferramenta de linha de comando (CLI), embora também possua interfaces gráficas de usuário (GUI) disponíveis. No entanto, a interface de linha de comando do Git é a forma mais comum e poderosa de interagir com o sistema de controle de versão Git. Através da CLI do Git, os usuários podem executar uma variedade de comandos para realizar operações como clonar repositórios, criar branches, fazer commits, mesclar código e muito mais.

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
3. **git add** (o commit serve para você descrever a alteração que você fez durante o desenvolvimento, mas lembre de sempre ser o mais breve possível... diferente de mim agora):
   ```bash
   # Cria um novo commit com os arquivos preparados no índice
   git commit -m "Mensagem do commit"
   ```
4. **git status**:
   ```bash
   # Mostra o estado atual do diretório de trabalho e do índice, ou seja, o que foi adicionado ou não.
   git status
   ```
5. **git push** :
   ```bash
   # Envia commits locais para o repositório remoto
   git push origin nome-do-branch
   ```
6. **git pull** :
   ```bash
   # Recupera commits do repositório remoto e mescla-os no branch local, ou seja, puxa todas as atualizações mais recentes. Isso facilita não ter conflitos na hora de juntar as branch's
   git pull
   ```
7. **git checkout** :
   ```bash
   # Cria uma nova branch e muda para ela
   git checkout -b nova-branch

   # Alterna para uma branch existente
   git checkout nome-da-branch
   ```

```diff
- AVISO: Sempre quando criar uma nova branch ir para a branch main e executar o comando "git pull" para atualizar a main e criar uma branch nova a partir da main.
```

## Sobre NodeJS
Node.js é uma plataforma de desenvolvimento de software de código aberto que permite executar JavaScript no lado do servidor. Ele usa o motor JavaScript V8 da Google Chrome e é amplamente utilizado para criar aplicativos web escaláveis e de alto desempenho.

## Sobre NVM
NVM, ou Node Version Manager, é uma ferramenta de linha de comando que permite instalar e gerenciar várias versões do Node.js em um único sistema. Isso é útil para desenvolvedores que precisam trabalhar em projetos que requerem versões específicas do Node.js.

## Sobre React
React é um framework usado para desenvolvimneto de código aberto para construir interfaces de usuário. Desenvolvida pelo Facebook, ela permite criar componentes reutilizáveis e declarativos que compõem interfaces de usuário interativas e dinâmicas. Outros exemplos de frameworks são Vue.JS, Next.JS e até mesmo Angular.JS


## Sobre MaterialUI
Material-UI é uma biblioteca de componentes React que implementa os princípios de design do Material Design, criado pelo Google. Ele fornece uma ampla variedade de componentes prontos para uso, como botões, barras de navegação, e tabelas, seguindo as diretrizes de design do Material Design. Isso facilita a criação de interfaces de usuário elegantes e consistentes.
Existe diversas bibliotecas de componentes mas sempre cada uma específica para cada framework. Se você se pergunta se pode existir a mesma biblioteca de componentes para outros frameworks, sim, existe! Apenas muda a forma de instalação e adaptação para o framework.
