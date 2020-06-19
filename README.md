<h1 align="center">
    <img alt="GIT" title="GIT" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Git.png" width="50px" />&nbsp;&nbsp;&nbsp;|<strong> Git e Github </strong> |&nbsp;&nbsp;&nbsp;
    <img alt="GitHub" title="GitHub" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/github_ver2.png" width="50px" />
</h1>

# Guia Prático para iniciantes

Este Guia foi criado para auxilia-los no aprendizado sobre o Git e GitHub.

Sempre há espaço para melhorar! Envie-nos comentários e sugestões!

# Vídeos de Referência

# Vídeos de Referência
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/embed/2alg7MQ6_sI) &nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp; [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/embed/UbJLOn1PAKw)

## Git

**Definição** ⇒ Software livre (Open Source) para controle de versões de edição de códigos, aqui chamados de *versionadores* de código.

- **Funções:** Organizar, distribuir e gerenciar as várias versões de um software.
- Repositório na nuvem que você está trabalhando **⇒** Precisa fazer um *Clone* em sua máquina para trabalhar **⇒** após o trabalho, você precisa juntar todo seu trabalho dentro de um (ou mais) pacotes chamados de *Commit* **⇒** Envia, então, para o repositório remoto utilizando o *Push***.**
- Ao utilizar um repositório **alterado** por outro desenvolvedor ⇒ Ao invés de clonar, você vai fazer um *Pull ⇒* após o trabalho, você precisa juntar todo seu trabalho dentro de um (ou mais) pacotes chamados de *Commit* **⇒** Envia, então, para o repositório remoto utilizando o *Push***.**
- *Pull Request* são pedidos de alterações/melhorias que vários desenvolvedores enviam ao repositório (via *Push*) para que sejam incorporados por meio de *Merge.*
- Para utilizar, precisa-se baixar por meio da página:

[Downloads](https://git-scm.com/download)

- *Git Pull* ⇒ Comando para baixar as alterações de outros programadores (ou até por você mesmo) deixando seu código sempre pronto para que você trabalhe na última versão disponivel.
- Eventualmente podem existir conflitos de códigos, que nada mais são áreas de códigos onde um ou mais programadores alterara e que agora precisam ser revisados.
- O que o Git não consegue resolver, ele marca com um bloco visual.

## **Github**

**Definição** ⇒ Servidor na nuvem que armazena seus códigos e possui uma interface amigável (Em outras palavras, é um Repositório de Gits).

> Além de GitHub temos: GitLab, BitBucket.

Seu cartão de visita é o GitHub, por isso é importante ter um repositório de código bem atualizado e organizado.

### Como criar seu portfolio de projetos?

Basicamente a estratégia é documentar no arquivo README.md, o qual é o arquivo padrão exibido ao acessar seu repositório e o código do projeto, e que todas as pessoas poderão lê-lo.

Lembrando que nest arquivo você explica o seu projeto de forma não muito técnico, focado no visual e na compreensão do que se trata seu código.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2499aca6-e318-4fa5-994c-bad04dd2e90e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2499aca6-e318-4fa5-994c-bad04dd2e90e/Untitled.png)

Exemplo de [README.md](http://readme.md) muito bem criado. Autoria de: [RocketSeat](https://rocketseat.com.br/)

Primeiro, antes de mais nada, devemos iniciar o Git usando o comando: 

*Git init*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fffcec92-2f8a-4712-a9ce-240d6da9b7e9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fffcec92-2f8a-4712-a9ce-240d6da9b7e9/Untitled.png)

Depois, "tocamos" o arquivo para definir a data e hora (tempo) que aquele arquivo foi modificado:

*Git touch*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c497d01d-6fc4-458c-b90b-80d04b02bbf9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c497d01d-6fc4-458c-b90b-80d04b02bbf9/Untitled.png)

Caso o terminal esteja muito poluído, basta dar o comando de limpar:

*Clear*

- **Você deseja criar pontos na história da produção do seu projeto?**

Por exemplo, para registrar quando você iniciou essa landing page basta dar o comando:

*Git add landingpage.html*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f40c70d-6ea5-4783-8ab8-1cfd3cd8dc10/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f40c70d-6ea5-4783-8ab8-1cfd3cd8dc10/Untitled.png)

Após adicionar os pontos na história do seu projeto, há necessidade de juntar as alterações para que seja enviado ao repositório. Ou seja, ele vai criar um ponto na história do projeto.

*Git commit -m "Added landing page."*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9c4a48c-66bb-4c6e-8b05-d1639afe77f5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9c4a48c-66bb-4c6e-8b05-d1639afe77f5/Untitled.png)

- **Você deseja verificar mudanças feitas no seu projeto**

Para ver os pontos da história deste projeto (os *Commits*)

*Git log*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a8a17e1-975e-4091-9a55-7877c12978ae/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a8a17e1-975e-4091-9a55-7877c12978ae/Untitled.png)

*Git status*

Mostra o estado do meu projeto.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e469166e-2649-44be-8769-3bef5202db1b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e469166e-2649-44be-8769-3bef5202db1b/Untitled.png)

Se queremos ver o que foi feito em um momento da história, precisamos, primeiro, identificar o momento e depois visualizar ele. A identificação é uma sequencia de caracteres ao lado de *commit* (sublinhado em vermelho na imagem abaixo) que aparece com o comando *git log:*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32c135c8-a1c2-40c2-9c12-bf6c748803f9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32c135c8-a1c2-40c2-9c12-bf6c748803f9/Untitled.png)

Depois, aplicamos o comando:

*Git show [insira aqui o código numerico]*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44578641-b190-4246-9787-4bbab5c77b68/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44578641-b190-4246-9787-4bbab5c77b68/Untitled.png)

Se eu quiser ver o ultimo ponto da história, basta colocar o comando:

*Git show*

- **Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.**

São a possibildiade de criar "universos" paralelos de seu projeto. Por standar, seu projeto é criado como "master"

*Git branch [nome da branch]*

Suponhamos que um cliente pediu para você adicionar um carrinho de compras.

Assim, começaremos a construir o código em um *branch* (um ramo) do projeto para que o original não seja afetado (em caso de algum erro!)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/caf59381-1e57-4032-84f3-f6ff2af121b5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/caf59381-1e57-4032-84f3-f6ff2af121b5/Untitled.png)

Para mudar para essa branch, usamos o comando:

*Git checkout [nome da branch]*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6601dba0-5ee8-46ff-9b3d-d5c158c918fc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6601dba0-5ee8-46ff-9b3d-d5c158c918fc/Untitled.png)

Para confirmar novamente, é válido ir no *Git status:*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b265e78a-61d4-47d1-8139-8699ef159ea7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b265e78a-61d4-47d1-8139-8699ef159ea7/Untitled.png)

Para voltar para a master, é só usar o comando *Git checkout master.*

Para visualizar todos as ramificações criadas, basta digitar:

*Git branch*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cf08957-9ea2-4cea-8444-dbbbc81ebdb0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cf08957-9ea2-4cea-8444-dbbbc81ebdb0/Untitled.png)

Seguido os passos acima, foi criado uma pagina html chamada de cart e escrito carrinho em produção. Foi, também, registrado na *branch*. Veja o log como fica com *branch*:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1fa584d-0f31-4008-8078-dd47a29eb8e4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1fa584d-0f31-4008-8078-dd47a29eb8e4/Untitled.png)

Quer ter certeza se não foi feito alteração no seu ramo principal? Use o comando abaixo e veja os arquivos nele presente (veja que não consta o cart.html):

*Git ls -all*

OBS: LS ⇒ List, assim, o comando significa: list all

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/16fd61dd-b197-4ae2-9633-50e0bd25327d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/16fd61dd-b197-4ae2-9633-50e0bd25327d/Untitled.png)

- **Você adiciona as novas funcionalidades ao seu projeto em produção**

Fez as alterações na ramificação, gostou, aprovou? Hora de trazer para o projeto principal (master).  Para isso, deve-se utilizar o comando:

*Git merge [nome da branch]*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5acbede4-65e5-4c31-aeb3-5e9488d5fc9c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5acbede4-65e5-4c31-aeb3-5e9488d5fc9c/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a4e61e40-c4b6-4048-b735-25f24ac78b60/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a4e61e40-c4b6-4048-b735-25f24ac78b60/Untitled.png)

- **Você quer deletar a *branch* da nova funcionalidade, depois de aplicar em seu projeto.**

Migrou a ramificação pro *master* com sucesso? projeto aprovado? hora de deletar a branch para não haver ruídos:

*Git branch -D [nome da branch]*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0477600c-eee9-4ba4-bcc3-d3cf27168153/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0477600c-eee9-4ba4-bcc3-d3cf27168153/Untitled.png)

- **Você quer colocar seu projeto na nuvem (Github).**

Primeiro acesse o GitHub e crie sua conta/faça login.

Após isso, clique em "Create Repository" caso ainda não tenha criado:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a1edbef-6ab4-4ade-86a6-61eb056a0b46/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a1edbef-6ab4-4ade-86a6-61eb056a0b46/Untitled.png)

Preencha com o nome do repositório e com uma descrição e siga para a próxima tela.

Como já temos um "Readme.md", utilizaremos:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6d102ed-4041-4f52-b328-75c2a7a614c8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6d102ed-4041-4f52-b328-75c2a7a614c8/Untitled.png)

Para ver seus repositórios remotos, utilize:

*Git remote -v*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69c77db7-13d6-48f2-91bc-c0a1da58e043/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69c77db7-13d6-48f2-91bc-c0a1da58e043/Untitled.png)

Para fazer o upload do repositório local para o repositório online, utilize o comando:

*Git push*

Como é a primeira vez que fazemos o push, temos que criar a branch master:

*Git push -u origin master*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/829d387f-997f-4edf-b849-f95baffa20c7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/829d387f-997f-4edf-b849-f95baffa20c7/Untitled.png)

Caso seja a primeira vez que esteja fazendo o upload, é possivel que seja solicitado login e senha do GitHub.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/047f003a-9a59-42da-b601-df449095e148/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/047f003a-9a59-42da-b601-df449095e148/Untitled.png)

Vejam acima que não há o arquivo README.md. Precisamos adicionar ele ao branch e fazer upload novamente.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/933ac0a4-8a07-42cc-bf78-b2407bb153bb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/933ac0a4-8a07-42cc-bf78-b2407bb153bb/Untitled.png)

Agora sim, com Readme:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d60b0403-0a38-4d10-a64e-2559dcfa35a1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d60b0403-0a38-4d10-a64e-2559dcfa35a1/Untitled.png)

- **Você vai pegar um projeto já iniciado, para trabalhar com o time**
- **Você precisa resolver um conflito.**
- **Antes de enviar a resolução, precisamos atualizar o projeto local.**
- **Você precisa voltar um arquivo para um determinado momento da linha do tempo.**
- **Você precisa recuperar algo deletado.**
- **Você precisa mudar de diretório.**

Para mudar de diretório, utilize o comando:

*cd [nome do folder]*

OBS: cd ⇒ change directory.

# Principais comandos do Git:

- `git init` // inicia a linha do tempo;
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo, atualizando os arquivos nos commits;
- `git commit -m "mensagem"`  // adiciona um ponto na l;inha do tempo
- `git log` // visualiza os pontos na linha do tempo / commit;
- `git status` // informa o estado das alterações do nosso projeto;
- `git show` // apresenta determinado ponto na história;
- `git branch` // gerenciar novas linhas do tempo;
- `git checkout` // manipula as linhas do tempo;
- `git merge` // unir linhas do tempo;
- `git push` // envia alterações locais para o repositório remoto (Github);
- `git clone` // Baixar o projeto a primeira vez na sua máquina, ou seja, clonar um projeto / repositório;
- `git pull` // puxa/recebe o código atualizado do repositório remoto;

## Developers

> Estas pessoas contribuiram para o Readme.md ser o mais completo possível!

| <a href="https://www.linkedin.com/in/lucasrgoncalves/" target="_blank">**Lucas Gonçalves**</a> |
| :---: |:---:| :---:|
| <img alt="GIT" title="GIT" src="https://avatars0.githubusercontent.com/u/66454089?s=460&u=7d44989a97508ae37a8d5d81fb1bf19e005f15e9&v=4" width="130px" />| 
| <a href="https://github.com/Auriflanos" target="_blank">`GitHub`</a>| 
| <a href="https://www.linkedin.com/in/lucasrgoncalves/" target="_blank">`LinkedIn`</a> |

Estas pessoas contribuiram para o Readme.md ser o mais completo possível!

| <a href="http://fvcproductions.com" target="_blank">**FVCproductions**</a> |
| :---: |:---:| :---:|
| [![FVCproductions](https://avatars1.githubusercontent.com/u/4284691?v=3&s=200)](http://fvcproductions.com)    |
| <a href="http://github.com/fvcproductions" target="_blank">`github.com/fvcproductions`</a> |