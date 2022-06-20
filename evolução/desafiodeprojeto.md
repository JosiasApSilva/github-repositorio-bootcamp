# Módulo 1

# 1/3 Intrudução à Programação e Pensamento Computacional

 Breve resumo Modúlo 1

 O pensamento computacional é uma Habilidade generalista.

Matematica --- Leitura --- Escrita

É baseada em 4 pilares 

- Decomposição 

- Reconhecimento

- Abistração

- Designe de Algoritimo

##### Processo de pensamentos envolvidos no expressaõ de soluções em passos computacionais ou algoritimos que podem ser implementados no computador.

## Sistematico e Eficiente

A formulação e Resolução dos problemas devem ser capazes de ser resolvidas por Humanos e Maquinas.

Dentre os demais assuntos aborbados no módulo 1 estão 

- Estudo de Caso conceitual: Perdido 

- Estudo de caso aplicado: Soma de um intervalo

- Técnicas de lógica de programação 

- Tipologia e variáveis

- Instruções primitivas 

- Estruturas condicionais e operadores

- Estruturas de repetição

- Vetores e matrizes 

- Instruções 

- Caracteristica de um programa

- Analise de um cõdigo

- Paradigmas de programação

- Portugol

# 2/3 Introdução ao Git e ao GItHub

Git é um sistema de controle de versão, foi escrito por Linus Torvalds em 2005 e hoje, milhões de empresas utilizam para o eficiente gerenciamento de código e controle de versão.

Nesta etapa foi demostrado desde a instalação até o primeiro Commit 

Os tópicos estudados foram 

- Comandos básicos 

- Tópicos fundamentais para intender o funcionamento do Git

- Objetos internos do Git

- Chave SSH e Token

- Criando um Commit 

- Trabalhando com o GitHub

- Resolvendo conflitos 

##### Alguns comandos Basicos de Navegação no CMD

(obs: Podem ser utilizados no git)

dir . Lista as pastas, lista de diretorios do local setado 

cd. navega entre as pastas ( não se esqueça de utilizar / )

exemplo cd /windows você vai estar dentro da pasta de nome windows para retroceder 

basta utilizar cd .. e você esta retornando um nivel atras 

cls ou clear . limpa o terminal 

mkdir utilizado para criar uma pasta (lembre-se de estar navegando dentro da pasta ao qual deseja criar a subpasta.) exemplo de utilização >>>> mkdir workspace (enter)

Criando um arquivo você utiliza o comando echo  ele simplesmente printa de volta um texto no terminal no caso algo ao qual acabei de digitar, utilizo o comando com o nome da pasta desejado seguido de > (maior que) que funciona como um redirecionador de fluxo que vai pegar a saida (out put) desse comando echo e vai jogar em um arquivo. Abaixo um exemplo 



c: workspace > echo hello > hello.txt 

Neste exemplo estariamos criando um arquivo de texto 



Deletando um arquivo utilize o comando 

del (nome do arquivo)

quando desejar deletar uma pasta inteira utilize o comando 

rmdir nome da pasta /s /q entter



Seta para cima funciona como um um atalho para os ultimos comandos utilizados 



- sha1

- objetos fundamentais

- sistema distribuido

- segurança



sha1 Security Hash Algorithm

incriptação de dados



-  1 echo "top secret" open ssl sha1

- 2 > (stdin)= f9fc85...



No exemplo descrito acima o comando echo utilizando o openssl sha1 que joga a string para o terminal, ira forçar a istring "top secret" para um algoritimo de encriptação.

Com um arquivo ele ira geral um código de 40 caracteres, e posteriormente se uma unica virgula no arquivo, ou letra forem alteradas o código de 40 caracteres sera alterado, e se o mesmo for alterado novamente voltando para o seu estado original e código sha1 tambem retorna para seu estado inicial. 



# Objetos basicos no Git

- Blobs

- Trees

- Commits



(Vale lembrar que o comando echo pega uma string e te devolve o output da mesma.)



### Blobs e Trees



Todo o conteúdo é armazenado como objetos _tree_ e _blob_, com as _trees_ correspondendo a entradas de um diretório UNIX e _blobs_ correspondendo mais ou menos a _inodes_ ou conteúdos de arquivos. Um único objeto _tree_ contém uma ou mais entradas, cada uma contendo uma referência SHA-1 para um _blob_ ou _subtree_ com seu modo, tipo e nome de arquivo associados.



### Commits



O formato para um objeto _commit_ é simples: ele especifica a _tree_ de nível mais alto para o _snapshot_ do projeto neste ponto; a informação do autor/_commiter_ (que usa as configurações `user.name` e `user.email`, além de um _timestamp_); uma linha em branco e então a mensagem de _commit_.



## # Chave SSH e TOKENS



Forma de estabelecer conexão segura e encriptada entre duas maquinas, exemplo GitHub >> Maquina Local. 



-----------------------------------------------------------------------------------------------------------------------------------------------------------------



# Aplicando o conhecimento adquirido



Navegamos pelo terminal Git e criamos as chaves para a comunicação entre minha maquina e o git



Aqui deixo anotado alguns comando uteis que usamos durante os trabalhos (Obs: Os mesmos podem aparecer anotados diversas vezes, me ajuda a lembrar dos comandos basicos com mais facilidade)



cd / _nome/caminho da pasta_.  

ls lista e mostra o local que você esta.

pwd Lista o caminho exato do local que você esta.



# Primeiros comandos com o Git



git init ----------- inicia um repositorio 

git add ---------- adicionar 

git commit ---- comitar 

git -a a flag menos a (-a) mostra pastas ocultas dentro da pasta .



#### Quando se esta criando e vercionando arquivos com o git ele pode solicitar um user name (apelido) e um e-mail, estes são gravados ao vercionamento como autor daquele arquivo. Ele pode ser setado somente em um arquivo especifico ou de forma global.



 git config -- global user.email "exemplo@exemplo.com"

 git config -- global user.name "exemplo"



Utilizando ambos comandos acima você configua o seu e-maile o seu user name no git, vale lembrar que o seu user name e e-mail não precisam necessariamente serem os mesmos do GItHub, porem o ideal é ser.



# GitHub



Esta pasta de projeto já foi criada no meu repositorio local, utilizando os comandos git init (Este arquivo estara sendo atualizado dentro da branch principal)



Criar um projeto novo
---------------------

* Criar uma nova pasta na maquina, neste caso estou chamando de `desafio de projeto`

* Abra o git bash here nesta pasta 

* Criar um novo arquivo `README.md`

* Escrever dentro dele o seu projeto `Exemplo Projeto de conclusão`

* Salva o arquivo

usando o Git

* Abre o Git Bash que foi instalado na máquina (pode ser pelo terminal do VSCode mesmo)

* `git init` para inicializar o repositório

Foi criada uma pasta `.git`  não apague ela é util

* `git add README.md` para colocar o arquivo na área de stagging.

* `git commit -m "primeiro commit"` para de fato dar o commit no repositório

* `git branch -M "main"` para alterar o nome da branch principal de `master` para `main` (isso é uma boa prática atualmente recomendada)
  
  

Caso não tenha ocorrido nenhum erro seguimos para o proximo passo 

Repositório no Github
------------------------------------------------------------------------------------------------

* Depois de você ter criado a sua conta na plataforma, você irá em `Criar novo repositório`
  
  

Você vai preencher com as informações do projeto, então dar o nome do repositório, colocar uma breve descrição e criar



Após criar você copia o link url que aparecer para você



* Para enviar o commit do meu repositório local (A sua máquina) para um repositório na plataforma do Github, usamos o `git remote add origin <link do repositório>` Aquele link que foi copiado anteriormente 

* `origin` é o nome utilizado para referenciar o nosso repositório basicamente um apelido
  
  

O repositório local esta conectado com o respositório do Github, através do `commit` que damos na máquina, porem como o mesmo não sobe automaticamente para a plataforma precisaremos empurrar.

* Desta forma que empurramos, com o `git push -u origin main`
  
  

Agora atualizamos a página e nosso arquivo vai estar na plataforma!

Adicionando uma atualização ao arquivo
---------------------------------------------------------------------------------------------------------------

O repositório no Github esta configurado, agora faremos uma atualização no arquivo que já commitamos

* Neste caso estou adicionando mais uma pasta `evolução` e dentro mais um arquivo `desafio de projeto.md`

* Os passos são os mesmos `git add .` (agora ponto `.` ou asterisco `*` pois adiciona todos os arquivos) e `git commit -m "Atualização 1 ou escreva o que desejar"`

* Precisamos dar o push novamente, então `git push origin main` (sem o -u)

No Github, poderemos ver que o arquivo foi alterado, clicando no nome do commit teremos acesso a todas as alterações que foram feitas.



## Aqui finalizo o desafio de projeto. 










