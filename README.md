<p align="center"> <img src="https://imgur.com/J3hD21O.png" alt="Javascript: criando requisições"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Página inicial e formulário de cadastro de vídeos da AluraPlay, uma plataforma de compartilhamento de vídeos.</p>

## Tecnologias utilizadas durante o curso
* Javascript
* NodeJS
* Json-server

## Tecnologias utilizadas no projeto
* HTML
* CSS

## Screenshots
![Screenshot da tela inicial do AluraPlay](https://imgur.com/aymxEsh.png)
![Screenshot da tela do formulário do AluraPlay](https://imgur.com/ShNADf2.png)

## Como visualizar e utilizar a página
<p align="center">Nesse projeto não foi utilizado banco de dados externos, impossibilitando fazer deploy da pagina pois o código não iria funcionar corretamente. Caso queira visualizar a página do projeto será necessario rodar localmente. Para isso deixarei um breve tutorial:</p>

 * Recomendo a utilização do editor de códigos VisualStudio Code
 * Para esse projeto será necessario a utilização do NodeJS instalado(caso não tenha instalado você pode acessar o site https://nodejs.dev/en/ para realizar o download e instalação)
  * No terminal digite o comando: npm init (para inciar o nodeJS, ele irá solicitar algumas configurações pode apenas dar Enter em todas.)
  * Feito issodigite o comando: npm install -g json-server (esse comando é para baixar a biblioteca JSON server, essa biblioteca cria uma API "fake" para podermos utilizar em nosso projeto)
  * aguarde a conclusão da instalação
  * Após concluída a instalação excute o comando: json-server --watch db.json
  * Agora é só abrir o arquivo index.html no browser ou usar a extensão LiveServer do VSCode.
  
  
