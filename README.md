# Poc-Go-Monitoramento-Sites
Poc Simples de Programação em Go, realizando monitoramento de Sites


Instalação
O seu processo de instalação é muito simples, basta acessar o site Oficial da linguagem e baixar o instalador correspondente ao seu S.O (Sistema Operacional), após isso independente do S.O que você esta utilizando a sua instalação é padrão Windows next next finish.

Workspace
Para que possamos trabalhar com o Go, o go já cria o nosso workspace no momento da sua instalação. Para esse artigo eu estou utilizando um computador com Windows, tendo em vista esse cenário o path ficou: C:\Go\src. Agora para que possamos finalizar esse etapa do artigo, nós precisamos criar dois novos diretórios: um chamado github.com e um outro com o nome do nosso usuário do git, tendo em vista esse cenário o meu path ficou: github.com\programadriano

Hello World
Para que possamos verificar se tudo esta configurado corretamente, vamos ao famoso Hello World. Para isso, crie um novo diretório dentro da sua pasta src chamado hello. Para o nosso próximo passo iremos precisar de uma IDE, para esse artigo iremos utilizar o VS Code (Visual Studio Code).

Com o VS Code aberto dentro do nosso diretório hello, crie um novo arquivo chamado main.go, em seguida atualize ele com o código abaixo:


(Hello World GoLang)
Passando pelas linhas de código a cima nós temos:

01: Estamos informando que esse será o pacote principal da nossa aplicação;
03: Essa é a forma que nós importamos pacotes com o Go;
05: Função principal de um código Go;
06: Estamos printando a nossa mensagem.
Compilação
Vamos agora gerar o nosso executável. Para isso, execute o comando abaixo no seu terminal dentro da pasta do seu projeto:

go build 
O comando a cima irá gerar um novo arquivo dentro do nosso diretório hello chamado main.exe, para que possamos executá-lo digite o comando ./main.exe na sua console.


