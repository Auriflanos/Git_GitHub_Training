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
<a href="https://www.youtube.com/embed/2alg7MQ6_sI" target="_blank"><img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Video1.jpg" width="450px"/></a>| <a href="https://www.youtube.com/embed/UbJLOn1PAKw" target="_blank"><img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Video2.jpg" width="450px"/></a>


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

<p align="center">
<a href="https://git-scm.com/download" target="_blank"><img alt="Download Git" title="Download Git" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Screen%20download.jpg" width="350px"/></a>
</p>

**Conflitos** <img alt="Icon made by Freepik from www.flaticon.com" title="Icon made by Freepik from www.flaticon.com" src="https://image.flaticon.com/icons/svg/60/60678.svg" width="15px" /> Eventualmente podem existir conflitos de códigos, que nada mais são áreas de códigos onde um ou mais programadores alterara e que agora precisam ser revisados. Os conflitos que o Git não consegue resolver, ele marca com um bloco visual.

## **Github**

**Definição** ⇒ Servidor na nuvem que armazena seus códigos e possui uma interface amigável (Em outras palavras, é um Repositório de Gits).

> Além de GitHub temos: GitLab, BitBucket.

Seu cartão de visita é o GitHub, por isso é importante ter um repositório de código bem atualizado e organizado.

##  **Como criar seu portfolio de projetos?**

|||
|--|--|
|Basicamente a estratégia é documentar no arquivo **README.md**, o qual é o arquivo padrão exibido ao acessar seu repositório e o código do projeto, e que todas as pessoas poderão lê-lo. Lembrando que neste arquivo você explica o seu projeto de forma não muito técnico, focado no visual e na compreensão do que se trata seu código. |<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem1.png" width="1000px" /> </p><p align="center">Exemplo de [README.md](http://readme.md) muito bem criado. Autoria de: <a href="https://rocketseat.com.br/" target="_blank"><img alt="RocketSeat" title="RocketSeat" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem39.png" width="200px"/></a></p>|

Primeiro, antes de mais nada, devemos iniciar o Git usando o comando: 

>*Git init*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem2.png" width="550px" /> </p>

Depois, "tocamos" o arquivo para definir a data e hora (tempo) que aquele arquivo foi modificado:

>*Git touch*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem3.png" width="550px" /> </p>

Caso o terminal esteja muito poluído, basta dar o comando de limpar:

>*Clear*

## **Como criar pontos na história da produção do seu projeto?**

Por exemplo, para registrar quando você iniciou essa landing page basta dar o comando:

>*Git add landingpage.html*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem4.png" width="550px" /> </p>

Após adicionar os pontos na história do seu projeto, há necessidade de juntar as alterações para que seja enviado ao repositório. Ou seja, ele vai criar um ponto na história do projeto.

>*Git commit -m "Added landing page."*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem5.png" width="550px" /> </p>

## **Como verificar mudanças feitas no seu projeto?**

Para ver os pontos da história deste projeto (os *Commits*)

>*Git log*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem6.png" width="550px" /> </p>

>*Git status*

Mostra o estado do meu projeto.

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem7.png" width="550px" /> </p>

Se queremos ver o que foi feito em um momento da história, precisamos, primeiro, identificar o momento e depois visualizar ele. A identificação é uma sequencia de caracteres ao lado de *commit* (sublinhado em vermelho na imagem abaixo) que aparece com o comando *git log:*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem8.png" width="550px" /> </p>

Depois, aplicamos o comando:

>*Git show [insira aqui o código numerico]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem9.png" width="550px" /> </p>

Se eu quiser ver o ultimo ponto da história, basta colocar o comando:

<p align="center">>*Git show*

## **Como começar uma nova funcionalidade no seu projeto, sem estragar o que já foi feito?**

São a possibildiade de criar "universos" paralelos de seu projeto. Por padrão, seu projeto é criado como "master"

Suponhamos que um cliente pediu para você adicionar um carrinho de compras.

Assim, começaremos a construir o código em um *branch* (um ramo) do projeto para que o original não seja afetado (em caso de algum erro!). Para criar o novo branch, utilize o código abaixo:

>*Git branch [nome da branch]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem10.png" width="550px" /> </p>

Para mudar para essa branch, usamos o comando:

>*Git checkout [nome da branch]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem11.png" width="550px" /> </p>

Para confirmar novamente, é válido ir no *Git status:*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem12.png" width="550px" /> </p>

Para voltar para a master, é só usar o comando *Git checkout master.*

Para visualizar todos as ramificações criadas, basta digitar:

>*Git branch*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem13.png" width="550px" /> </p>

Seguido os passos acima, foi criado uma pagina html chamada de cart e escrito carrinho em produção. Foi, também, registrado na *branch*. Veja o log como fica com *branch*:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem14.png" width="550px" /> </p>

Quer ter certeza se não foi feito alteração no seu ramo principal? Use o comando abaixo e veja os arquivos nele presente (veja que não consta o cart.html):

>*Git ls -all*

OBS: LS ⇒ List, assim, o comando significa: list all

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem15.png" width="550px" /> </p>

## **Como adicionar as novas funcionalidades ao seu projeto em produção?**

Fez as alterações na ramificação, gostou, aprovou? Hora de trazer para o projeto principal (master).  Para isso, deve-se utilizar o comando:

>*Git merge [nome da branch]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem16.png" width="550px" /> </p>

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem17.png" width="550px" /> </p>

- **Você quer deletar a *branch* da nova funcionalidade, depois de aplicar em seu projeto.**

Migrou a ramificação pro *master* com sucesso? projeto aprovado? hora de deletar a branch para não haver ruídos:

>*Git branch -D [nome da branch]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem18.png" width="550px" /> </p>

- **Você quer colocar seu projeto na nuvem (Github).**

Primeiro acesse o GitHub e crie sua conta/faça login.

Após isso, clique em "Create Repository" caso ainda não tenha criado:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem19.png" width="550px" /> </p>

Preencha com o nome do repositório e com uma descrição e siga para a próxima tela.

Como já temos um "Readme.md", utilizaremos:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem20.png" width="550px" /> </p>

Para ver seus repositórios remotos, utilize:

>*Git remote -v*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem21.png" width="550px" /> </p>

Para fazer o upload do repositório local para o repositório online, utilize o comando:

>*Git push*

Como é a primeira vez que fazemos o push, temos que criar a branch master:

>*Git push -u origin master*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem22.png" width="550px" /> </p>

Caso seja a primeira vez que esteja fazendo o upload, é possivel que seja solicitado login e senha do GitHub.

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem23.png" width="550px" /> </p>

Vejam acima que não há o arquivo README.md. Precisamos adicionar ele ao branch e fazer upload novamente.

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem24.png" width="550px" /> </p>

Agora sim, com Readme:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem25.png" width="550px" /> </p>

## **Como pegar um projeto já iniciado, para trabalhar com em equipe?**

Para isso, precisamos pegar o link no GitHub. Encontre o projeto e obtenha o link. No exemplo, usaremos o GitHub da Rocketseat: 

[Rocketseat/nlw-01-booster]()

<p align="center"><a href="https://github.com/Rocketseat/nlw-01-booster" target="_blank"><img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem26.png" width="600px"/></a></p>


Após copiar o link, utilize o comando abaixo:

>*Git clone [link copiado]*

## **Como resolver um conflito entre arquivos?**

Normalmente, quando se trabalha com ramificações (*Branches)* é comum termos conflitos de arquivos para se tratar. Isso significa, por exemplo, que uma modificação num arquivo chamado, digamos, package.json da *branch*, corre o risco de subscrever uma modificação feita na mesma linha na *Master.*

Assim devemos arrumar esses conflitos. Veja a sequencia de eventos nas imagens abaixo. Modifiquei o arquivo "Cart.html" na branch Master e na Branch nova chamada conflito. Importante informar que o Git avalia conflitos na mesma linha, assim, no testo a linha 2 é a que possui conflito.

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem27.png" width="550px" /> </p>

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem28.png" width="550px" /> </p>

Tela onde o VS Code realça o conflito:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem29.png" width="550px" /> </p>

No caso, como há conflitos, o próprio Git nos ajuda com opções de aceitar a mudança presente na ramificação *Master*, aceitar a da ramificação *Conflito,* aceitar ambas as alterações, comparar as alterações ou, caso tenha dúvidas, iniciar uma sessão de compartilhamento remoto para que outro programador auxilie com este conflito.

Para fim deste exercício, aceitaremos a mudança presente na *Master*:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem30.png" width="550px" /> </p>

agora que resolvemos o conflito, há necessidade de atualizar a página e o projeto para que possamos subir no GitHub as atualizações:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem31.png" width="550px" /> </p>

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem32.png" width="550px" /> </p>

## **Como, antes de enviar a resolução do conflito, atualizar o projeto local?**

Digamos que alguém (ou você) alterou algo no GitHub (por meio de *Git push*, por exemplo) e você quer atualizar o projeto local. Primeiro, vamos ver como alterar um arquivo, digamos, o [Readme.md](http://readme.md) no GitHub:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem33.png" width="550px" /> </p>

Após alteração, submeter o commit:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem34.png" width="550px" /> </p>

É importante sempre verificar isso quando trabalhando em equipe para não criar conflitos ou perda de dados, assim, sempre puxe as atualizações do GitHub para somente então subir suas alterações.

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem35.png" width="550px" /> </p>

## **Como voltar um arquivo para um determinado momento da linha do tempo?.**

Vamos supor que os ajustes em seu código deram muito errado. Felizmente, se você salvou seguindo as instruções acima, é possível voltar um arquivo para um determinado momento da linha do tempo. Primeiramente identifique a etapa do tempo que deseja restaurar e obtenha o código desta linha de tempo:

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem36.png" width="550px" /> </p>

Para restaurar, basta utilizar o comando abaixo:

>*Git checkout [sequencia numérica] -- [nome do arquivo **não esqueça de incluir a extensão!**]*

## **Como recuperar algo deletado?**

E se um arquivo inteiro foi eliminado? Digamos que tenhamos um arquivo chamado cart.html e esse foi eliminado. Para restaurar, basta usar o código abaixo:

>*Git checkout -- [nome do arquivo **não esqueça de incluir a extensão!**]*

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem37.png" width="550px" /> </p>

<p align="center"> <img alt="Developer" title="Developer" src="https://raw.githubusercontent.com/Auriflanos/Git_GitHub_Training/master/Images/Imagem38.png" width="550px" /> </p>
<p align="center">


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