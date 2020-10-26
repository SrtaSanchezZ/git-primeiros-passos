# git-primeiros-passos
Guia simples e objetivo para utilizar funções básicas do Git.

<h1> - GIT - </h1>

<h1> 1 - Crie um repositório</h1>

![1 - Crie](https://user-images.githubusercontent.com/59312153/97127364-2efe3e00-1718-11eb-91e9-23fa0cce616b.PNG)

<h1> 2 - Pense em um nome "OK"</h1>

OBS: Lembre-se que o nome do seu repositório será parte da URL do mesmo, então não dificulta a vida de quem fará uso. Sobre a DESCRIÇÃO: deixe os detalhes para o README.

![3 - Fazer](https://user-images.githubusercontent.com/59312153/97127629-e7c47d00-1718-11eb-9b9d-942927a00655.PNG)

<h1> 3 - Tipo de Privacidade</h1>

Todo mundo pode acessar ou é algo apenas para você e quem você convidar?

![4 - Visualização](https://user-images.githubusercontent.com/59312153/97128086-2a3a8980-171a-11eb-9865-c65ee4e863ae.PNG)

<h1> 4 - README e Licença</h1>

README: Pode criar o arquivo agora e editar depois, ou criar quando tiver ideia do que escrever, mas crie antes de clonar, ajuda. Uma dica de customização é usar de recursos de html, como hierarquia de títulos com TAG (h1, h2, etc) e pre carregar as imagens na aba ISSUES e usar a URL gerada dentro do README.</br></br>
  
Sobre as [Licenças](https://docs.github.com/pt/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository) , dê uma olhadinha nesse artigo que você irá encontrar algo que se encaixe ao seu projeto.

![5 - README e Licença](https://user-images.githubusercontent.com/59312153/97128402-06c40e80-171b-11eb-8222-33e94ae9c9ec.PNG)

<h1> - SEU PC - </h1>

1 - Faça [donwload do Git](https://git-scm.com/downloads) e instale no seu computador.

2 - Abra ou direcione o caminho da pasta em que você irá salvar o projeto que será trabalhado, no seu interpretador de linha de comando e digite o comando para verificar s está instalado corretamente e validar qual a versão que você está usando:

<h3>git version</h3>

![6 - CMD](https://user-images.githubusercontent.com/59312153/97130015-088fd100-171f-11eb-8012-9708a69fdbee.PNG)

3 - Configure seu PC com os dados do seu perfil no Git:

<h3> git config --global user.name SEUNOMEDEUSUARIO</h3>
<h3> git config --global user.email SEUEMAILDEACESSONOGIT@TANTOFAZ.COM.BR</h3>

OBS: Para visualizar as configurações de perfil GIT habilitadas no seu PC use o comando:

<h3>git config --list</h3>

![7 - config](https://user-images.githubusercontent.com/59312153/97130499-61139e00-1720-11eb-89bf-c0776ebf3eaa.PNG)

4 - Vá até a página no Git do seu repositório e copie o endereço da maneira que deseja clonar (copiar) o conteúdo para começar a trabalhar localmente (PC) no seu projeto.

![8 - clone](https://user-images.githubusercontent.com/59312153/97131165-2f033b80-1722-11eb-8c10-b151b96daa56.PNG)

5 - Faça o comando para clonar seu projeto:

<h3>git clone ENDERECODOREPOSITORIO</h3>

![9 - comando clone](https://user-images.githubusercontent.com/59312153/97131288-89040100-1722-11eb-8b4f-5478244b8607.PNG)

6 - Dentro da pasta que será criada, você poderá criar seu projeto e começar a fazer uso do compartilhamento em nuvem do mesmo via Git:

![10 - uso](https://user-images.githubusercontent.com/59312153/97131452-0891d000-1723-11eb-9966-1903e5688ff3.PNG)

<h1> - TRABALHANDO COM GIT - </h1>

1 - Agora que você já fez alterações no pacote de arquivos da sua pasta de projeto local, você precisa saber se houveram alterações nos arquivos do repositório em nuvem (origem), antes de enviar as suas alterações para o repositório no Git. Para isso, use o comando:

<h3>git pull origin</h3>

![11 - pull](https://user-images.githubusercontent.com/59312153/97132104-b81b7200-1724-11eb-9263-5bf9154cf5cd.PNG)

2 - O segundo passo é adicionar a relação de alterações e comentar sobre a relevância delas:

<h3>git add .</h3>
<h3>git commit -a -m "MENSAGEM DE REFERENCIA"</h3>

OBS: Caso queira adicionar apenas um arquivo, em vez do comando "git add .", use o seguinte comando: <h3>git add NOMEDOARQUIVO.EXTENSAO</h3>

![12 - commit](https://user-images.githubusercontent.com/59312153/97132650-6542ba00-1726-11eb-95df-af1404b61fbc.PNG)

3 - Por fim, basta utilizar o comando de envio das atualizações para o repositório.

<h3>git push origin</h3>
OBS: Possivelmente, após utilizar o comando o sistema do Git solicite que você acesse o sistema local com suas credenciais do Git, basta logar com seu e-mail e senha para seguir.</br>

![13 - push](https://user-images.githubusercontent.com/59312153/97133175-d2a31a80-1727-11eb-998a-6c759ca63443.PNG)
