<h1 align="center">
    <img alt="GIT" title="GIT" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Git.png" width="50px" />&nbsp;&nbsp;&nbsp;|<strong> Git e Github </strong> |&nbsp;&nbsp;&nbsp;
    <img alt="GitHub" title="GitHub" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/github_ver2.png" width="50px" />
</h1>

# Guia Prático para iniciantes

Este Guia foi criado para auxilia-los no aprendizado sobre o Git e GitHub.

Sempre há espaço para melhorar! Envie-nos comentários e sugestões!

# Table of Contents
- [Videos de Referência](#Vídeos-de-Referência)
- [Antes de Começar](#Antes-de-Começar)
- [Git](#Git)
- [Github](#GitHub)
- [Como criar seu portfolio de projetos?](#Como-criar-seu-portfolio-de-projetos?)
- [Como criar pontos na história da produção do seu projeto?](#Como-criar-pontos-na-história-da-produção-do-seu-projeto?)
- [Como verificar mudanças feitas no seu projeto?](#Como-verificar-mudanças-feitas-no-seu-projeto?)
- [Como começar uma nova funcionalidade no seu projeto, sem estragar o que já foi feito?](#Como-começar-uma-nova-funcionalidade-no-seu-projeto,-sem-estragar-o-que-já-foi-feito?)
- [Como adicionar as novas funcionalidades ao seu projeto em produção?](#Como-adicionar-as-novas-funcionalidades-ao-seu-projeto-em-produção?)
- [Como pegar um projeto já iniciado, para trabalhar com em equipe?](#Como-pegar-um-projeto-já-iniciado,-para-trabalhar-com-em-equipe?)
- [Como resolver um conflito entre arquivos?](#Como-resolver-um-conflito-entre-arquivos?)
- [Como, antes de enviar a resolução do conflito, atualizar o projeto local?](#Como,-antes-de-enviar-a-resolução-do-conflito,-atualizar-o-projeto-local?)
- [Como voltar um arquivo para um determinado momento da linha do tempo?](#Como-voltar-um-arquivo-para-um-determinado-momento-da-linha-do-tempo?)
- [Como recuperar algo deletado?](#Como-recuperar-algo-deletado?)
- [Resumo dos comandos principais do Git](#Resumo-dos-comandos-principais-do-Git)
- [Developers](#Developers)


# Vídeos de Referência
<a href="https://www.youtube.com/embed/2alg7MQ6_sI" target="_blank"><img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Video1.jpg" width="200px"/></a>| <a href="https://www.youtube.com/embed/UbJLOn1PAKw" target="_blank"><img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Video2.jpg" width="200px"/></a>


# **Antes de começar**

|Descrição|Link|
|--|--|
|Link do GIT: &nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp; [Git](https://git-scm.com/)|
Link da Biblioteca do Git para saber mais sobre esta ferramenta: &nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp; [Book](https://git-scm.com/book/en/v2)
Link do GIT para download: &nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp; [Downloads](https://git-scm.com/downloads)
|Link para um outro curso: &nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp; [Katacoda](https://www.katacoda.com/courses/git)|

# **Git**

**Definição** <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> Software livre (Open Source) para controle de arquivos num projeto em geral, ou em outras palavras, controlador de versionamento distribuído, aqui chamados de *versionadores* de código.

**Função** <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> Organizar, distribuir e gerenciar as várias versões de um software. Ou seja, é um repositório na nuvem.

**Utilização** <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" />Para utilizar, precisa-se baixar por meio da página:

## [Downloads](https://git-scm.com/download)

**Conflitos** <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> Eventualmente podem existir conflitos de códigos, que nada mais são áreas de códigos onde um ou mais programadores alterara e que agora precisam ser revisados. Os conflitos que o Git não consegue resolver, ele marca com um bloco visual.

## **Github**

**Definição** ⇒ Servidor na nuvem que armazena seus códigos e possui uma interface amigável (Em outras palavras, é um Repositório de Gits).

> Além de GitHub temos: GitLab, BitBucket.

Seu cartão de visita é o GitHub, por isso é importante ter um repositório de código bem atualizado e organizado.

##  **Como criar seu portfolio de projetos?**

Basicamente a estratégia é documentar no arquivo **README.md**, o qual é o arquivo padrão exibido ao acessar seu repositório e o código do projeto, e que todas as pessoas poderão lê-lo.

Lembrando que nest arquivo você explica o seu projeto de forma não muito técnico, focado no visual e na compreensão do que se trata seu código.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2499aca6-e318-4fa5-994c-bad04dd2e90e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2499aca6-e318-4fa5-994c-bad04dd2e90e/Untitled.png)

Exemplo de [README.md](http://readme.md) muito bem criado. Autoria de: [RocketSeat](https://rocketseat.com.br/)

Primeiro, antes de mais nada, devemos iniciar o Git usando o comando: 

>*Git init*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fffcec92-2f8a-4712-a9ce-240d6da9b7e9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fffcec92-2f8a-4712-a9ce-240d6da9b7e9/Untitled.png)

Depois, "tocamos" o arquivo para definir a data e hora (tempo) que aquele arquivo foi modificado:

>*Git touch*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c497d01d-6fc4-458c-b90b-80d04b02bbf9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c497d01d-6fc4-458c-b90b-80d04b02bbf9/Untitled.png)

Caso o terminal esteja muito poluído, basta dar o comando de limpar:

>*Clear*

## **Como criar pontos na história da produção do seu projeto?**

Por exemplo, para registrar quando você iniciou essa landing page basta dar o comando:

>*Git add landingpage.html*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f40c70d-6ea5-4783-8ab8-1cfd3cd8dc10/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f40c70d-6ea5-4783-8ab8-1cfd3cd8dc10/Untitled.png)

Após adicionar os pontos na história do seu projeto, há necessidade de juntar as alterações para que seja enviado ao repositório. Ou seja, ele vai criar um ponto na história do projeto.

>*Git commit -m "Added landing page."*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9c4a48c-66bb-4c6e-8b05-d1639afe77f5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9c4a48c-66bb-4c6e-8b05-d1639afe77f5/Untitled.png)

## **Como verificar mudanças feitas no seu projeto?**

Para ver os pontos da história deste projeto (os *Commits*)

>*Git log*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a8a17e1-975e-4091-9a55-7877c12978ae/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a8a17e1-975e-4091-9a55-7877c12978ae/Untitled.png)

>*Git status*

Mostra o estado do meu projeto.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e469166e-2649-44be-8769-3bef5202db1b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e469166e-2649-44be-8769-3bef5202db1b/Untitled.png)

Se queremos ver o que foi feito em um momento da história, precisamos, primeiro, identificar o momento e depois visualizar ele. A identificação é uma sequencia de caracteres ao lado de *commit* (sublinhado em vermelho na imagem abaixo) que aparece com o comando *git log:*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32c135c8-a1c2-40c2-9c12-bf6c748803f9/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32c135c8-a1c2-40c2-9c12-bf6c748803f9/Untitled.png)

Depois, aplicamos o comando:

>*Git show [insira aqui o código numerico]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44578641-b190-4246-9787-4bbab5c77b68/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44578641-b190-4246-9787-4bbab5c77b68/Untitled.png)

Se eu quiser ver o ultimo ponto da história, basta colocar o comando:

<p align="center">>*Git show*

## **Como começar uma nova funcionalidade no seu projeto, sem estragar o que já foi feito?**

São a possibildiade de criar "universos" paralelos de seu projeto. Por padrão, seu projeto é criado como "master"

Suponhamos que um cliente pediu para você adicionar um carrinho de compras.

Assim, começaremos a construir o código em um *branch* (um ramo) do projeto para que o original não seja afetado (em caso de algum erro!). Para criar o novo branch, utilize o código abaixo:

>*Git branch [nome da branch]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/caf59381-1e57-4032-84f3-f6ff2af121b5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/caf59381-1e57-4032-84f3-f6ff2af121b5/Untitled.png)

Para mudar para essa branch, usamos o comando:

>*Git checkout [nome da branch]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6601dba0-5ee8-46ff-9b3d-d5c158c918fc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6601dba0-5ee8-46ff-9b3d-d5c158c918fc/Untitled.png)

Para confirmar novamente, é válido ir no *Git status:*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b265e78a-61d4-47d1-8139-8699ef159ea7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b265e78a-61d4-47d1-8139-8699ef159ea7/Untitled.png)

Para voltar para a master, é só usar o comando *Git checkout master.*

Para visualizar todos as ramificações criadas, basta digitar:

>*Git branch*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cf08957-9ea2-4cea-8444-dbbbc81ebdb0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cf08957-9ea2-4cea-8444-dbbbc81ebdb0/Untitled.png)

Seguido os passos acima, foi criado uma pagina html chamada de cart e escrito carrinho em produção. Foi, também, registrado na *branch*. Veja o log como fica com *branch*:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1fa584d-0f31-4008-8078-dd47a29eb8e4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1fa584d-0f31-4008-8078-dd47a29eb8e4/Untitled.png)

Quer ter certeza se não foi feito alteração no seu ramo principal? Use o comando abaixo e veja os arquivos nele presente (veja que não consta o cart.html):

>*Git ls -all*

OBS: LS ⇒ List, assim, o comando significa: list all

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/16fd61dd-b197-4ae2-9633-50e0bd25327d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/16fd61dd-b197-4ae2-9633-50e0bd25327d/Untitled.png)

## **Como adicionar as novas funcionalidades ao seu projeto em produção?**

Fez as alterações na ramificação, gostou, aprovou? Hora de trazer para o projeto principal (master).  Para isso, deve-se utilizar o comando:

>*Git merge [nome da branch]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5acbede4-65e5-4c31-aeb3-5e9488d5fc9c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5acbede4-65e5-4c31-aeb3-5e9488d5fc9c/Untitled.png)

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a4e61e40-c4b6-4048-b735-25f24ac78b60/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a4e61e40-c4b6-4048-b735-25f24ac78b60/Untitled.png)

- **Você quer deletar a *branch* da nova funcionalidade, depois de aplicar em seu projeto.**

Migrou a ramificação pro *master* com sucesso? projeto aprovado? hora de deletar a branch para não haver ruídos:

>*Git branch -D [nome da branch]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0477600c-eee9-4ba4-bcc3-d3cf27168153/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0477600c-eee9-4ba4-bcc3-d3cf27168153/Untitled.png)

- **Você quer colocar seu projeto na nuvem (Github).**

Primeiro acesse o GitHub e crie sua conta/faça login.

Após isso, clique em "Create Repository" caso ainda não tenha criado:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a1edbef-6ab4-4ade-86a6-61eb056a0b46/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a1edbef-6ab4-4ade-86a6-61eb056a0b46/Untitled.png)

Preencha com o nome do repositório e com uma descrição e siga para a próxima tela.

Como já temos um "Readme.md", utilizaremos:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6d102ed-4041-4f52-b328-75c2a7a614c8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6d102ed-4041-4f52-b328-75c2a7a614c8/Untitled.png)

Para ver seus repositórios remotos, utilize:

>*Git remote -v*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69c77db7-13d6-48f2-91bc-c0a1da58e043/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69c77db7-13d6-48f2-91bc-c0a1da58e043/Untitled.png)

Para fazer o upload do repositório local para o repositório online, utilize o comando:

>*Git push*

Como é a primeira vez que fazemos o push, temos que criar a branch master:

>*Git push -u origin master*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/829d387f-997f-4edf-b849-f95baffa20c7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/829d387f-997f-4edf-b849-f95baffa20c7/Untitled.png)

Caso seja a primeira vez que esteja fazendo o upload, é possivel que seja solicitado login e senha do GitHub.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/047f003a-9a59-42da-b601-df449095e148/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/047f003a-9a59-42da-b601-df449095e148/Untitled.png)

Vejam acima que não há o arquivo README.md. Precisamos adicionar ele ao branch e fazer upload novamente.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/933ac0a4-8a07-42cc-bf78-b2407bb153bb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/933ac0a4-8a07-42cc-bf78-b2407bb153bb/Untitled.png)

Agora sim, com Readme:

<p>![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d60b0403-0a38-4d10-a64e-2559dcfa35a1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d60b0403-0a38-4d10-a64e-2559dcfa35a1/Untitled.png)</p>

## **Como pegar um projeto já iniciado, para trabalhar com em equipe?**

Para isso, precisamos pegar o link no GitHub. Encontre o projeto e obtenha o link. No exemplo, usaremos o GitHub da Rocketseat: 

[Rocketseat/nlw-01-booster](https://github.com/Rocketseat/nlw-01-booster)

<p align="center">[https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71f0b549-95a3-4321-9d2c-f66ee27bd205/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71f0b549-95a3-4321-9d2c-f66ee27bd205/Untitled.png)</p>

Após copiar o link, utilize o comando abaixo:

>*Git clone [link copiado]*

## **Como resolver um conflito entre arquivos?**

Normalmente, quando se trabalha com ramificações (*Branches)* é comum termos conflitos de arquivos para se tratar. Isso significa, por exemplo, que uma modificação num arquivo chamado, digamos, package.json da *branch*, corre o risco de subscrever uma modificação feita na mesma linha na *Master.*

Assim devemos arrumar esses conflitos. Veja a sequencia de eventos nas imagens abaixo. Modifiquei o arquivo "Cart.html" na branch Master e na Branch nova chamada conflito. Importante informar que o Git avalia conflitos na mesma linha, assim, no testo a linha 2 é a que possui conflito.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f79d0ac7-5b58-4d38-a821-b550f0b96197/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f79d0ac7-5b58-4d38-a821-b550f0b96197/Untitled.png)</p>

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e8ae40d-8c51-4f3d-8dab-e81bda5fa7ad/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e8ae40d-8c51-4f3d-8dab-e81bda5fa7ad/Untitled.png)</p>

Tela onde o VS Code realça o conflito:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef098c82-0c54-4298-96c9-811235fd3792/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef098c82-0c54-4298-96c9-811235fd3792/Untitled.png)</p>

No caso, como há conflitos, o próprio Git nos ajuda com opções de aceitar a mudança presente na ramificação *Master*, aceitar a da ramificação *Conflito,* aceitar ambas as alterações, comparar as alterações ou, caso tenha dúvidas, iniciar uma sessão de compartilhamento remoto para que outro programador auxilie com este conflito.

Para fim deste exercício, aceitaremos a mudança presente na *Master*:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c51352d-24a4-4662-99a3-45baaf397efa/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c51352d-24a4-4662-99a3-45baaf397efa/Untitled.png)</p>

agora que resolvemos o conflito, há necessidade de atualizar a página e o projeto para que possamos subir no GitHub as atualizações:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/24015d55-bd07-4bc4-9c42-d4281007fe5c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/24015d55-bd07-4bc4-9c42-d4281007fe5c/Untitled.png)</p>

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f7c53da-8985-4535-855e-142d0b602862/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f7c53da-8985-4535-855e-142d0b602862/Untitled.png)</p>

## **Como, antes de enviar a resolução do conflito, atualizar o projeto local?**

Digamos que alguém (ou você) alterou algo no GitHub (por meio de *Git push*, por exemplo) e você quer atualizar o projeto local. Primeiro, vamos ver como alterar um arquivo, digamos, o [Readme.md](http://readme.md) no GitHub:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75e08dac-2d65-4b6a-82b1-b9f02360cd91/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75e08dac-2d65-4b6a-82b1-b9f02360cd91/Untitled.png)</p>

Após alteração, submeter o commit:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cb9b121e-7806-460d-8eb5-81585641e131/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cb9b121e-7806-460d-8eb5-81585641e131/Untitled.png)</p>

É importante sempre verificar isso quando trabalhando em equipe para não criar conflitos ou perda de dados, assim, sempre puxe as atualizações do GitHub para somente então subir suas alterações.

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e4da1f79-f19b-49d9-9b74-922462f8726f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e4da1f79-f19b-49d9-9b74-922462f8726f/Untitled.png)</p>

## **Como voltar um arquivo para um determinado momento da linha do tempo?.**

Vamos supor que os ajustes em seu código deram muito errado. Felizmente, se você salvou seguindo as instruções acima, é possível voltar um arquivo para um determinado momento da linha do tempo. Primeiramente identifique a etapa do tempo que deseja restaurar e obtenha o código desta linha de tempo:

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/207dd6d9-72aa-49f2-98fd-b7c4971a8f22/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/207dd6d9-72aa-49f2-98fd-b7c4971a8f22/Untitled.png)</p>

Para restaurar, basta utilizar o comando abaixo:

>*Git checkout [sequencia numérica] -- [nome do arquivo **não esqueça de incluir a extensão!**]*

## **Como recuperar algo deletado?**

E se um arquivo inteiro foi eliminado? Digamos que tenhamos um arquivo chamado cart.html e esse foi eliminado. Para restaurar, basta usar o código abaixo:

>*Git checkout -- [nome do arquivo **não esqueça de incluir a extensão!**]*

<p align="center">![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e736f81-27c6-441f-8a3f-7fd79b5670bf/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e736f81-27c6-441f-8a3f-7fd79b5670bf/Untitled.png)</p>

<p="center">
  <img width="460" height="300" src="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e736f81-27c6-441f-8a3f-7fd79b5670bf/Untitled.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e736f81-27c6-441f-8a3f-7fd79b5670bf/Untitled.png">
</p>
- **Você precisa mudar de diretório.**

Para mudar de diretório, utilize o comando:

>*cd [nome do folder]*

*OBS*: cd ⇒ change directory.

# **Resumo dos comandos principais do Git**

- `git init` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> inicia a linha do tempo;
- `git add` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> adiciona ou atualiza mudanças para irem para a linha do tempo, atualizando os arquivos nos commits;
- `git commit -m "mensagem"`  <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> adiciona um ponto na l;inha do tempo
- `git log` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> visualiza os pontos na linha do tempo / commit;
- `git status` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> informa o estado das alterações do nosso projeto;
- `git show` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> apresenta determinado ponto na história;
- `git branch` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> gerenciar novas linhas do tempo;
- `git checkout` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> manipula as linhas do tempo;
- `git merge` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> unir linhas do tempo;
- `git push`  <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> envia alterações locais para o repositório remoto (Github);
- `git clone` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> Baixar o projeto a primeira vez na sua máquina, ou seja, clonar um projeto / repositório;
- `git pull` <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> puxa/recebe o código atualizado do repositório remoto;

## Developers

> Estas pessoas contribuiram para o Readme.md ser o mais completo possível!

| <a href="https://github.com/Auriflanos" target="_blank">**Lucas Gonçalves**</a> | <a href="https://github.com/DaywisonSilva" target="_blank">**Daywison Silva**</a> |
| :---: |:---:| 
| <a href="https://github.com/Auriflanos" target="_blank">***Owner***</a> | <a href="https://github.com/DaywisonSilva" target="_blank">***Supporter***</a> |
|<img alt="Developer" title="Developer" src="https://avatars0.githubusercontent.com/u/66454089?s=460&u=7d44989a97508ae37a8d5d81fb1bf19e005f15e9&v=4" width="130px" />| <img alt="Developer" title="Developer" src="https://avatars3.githubusercontent.com/u/54292958?s=460&u=77341c2bc487c5146a1d937d7c511c7087025b68&v=4" width="130px" /> |
| <a href="https://www.linkedin.com/in/lucasrgoncalves/" target="_blank">`LinkedIn`</a> | <a href="https://www.linkedin.com/in/daywison-s-ab11b6121" target="_blank">`LinkedIn`</a> |
| <a href="https://github.com/Auriflanos" target="_blank">`GitHub`</a> | <a href="https://github.com/DaywisonSilva/" target="_blank">`GitHub`</a> |