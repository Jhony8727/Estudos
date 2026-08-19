# 🛠️ _**GIT**_

### _Estudo sobre o **GIT** e suas funções._

Responda as seguintes questões sobre o assunto:

O que é o **GIT**?
_R:_   Git é um Software de controle de versão.

Para que server o **GIT**?
_R:_ Como dito na resposta acima ele trabalha com o versionamento do código ou seja a cada atualização que você fizer no seu software ele vai salvar para que quando vc precise de alguma versão especifica ou algo de problema você consiga retornar a algum ponto anterior. 

**Principais vantagem:**

  - Controle de Histórico
  - Trabalho em equipe 
  - Ramificação do projeto 
  - Segurança
  - Organização

Concluindo a resposta o git e muito importante e digo que essencial para um programado para um bom gerenciamento do seu software e tbm para trabalhos em equipe como pode ser separado cada função dentro deste repositório .

Como usar o **GIT**?
_R:_  Primeiro você deve instalar o Git na sua maquina entrando no site oficial `http://git-scm.com` a instalação funciona de diferentes maneiras dependendo do sistema operacional que vc esta usando será um método diferente que o próprio site vai te mostrar o que fazer, Após instalar você inicializa o git dentro do software que vc quer usar para criar um repositório, para isso vc usa o código `git init` após criar o repositório git dentro do seu projeto e possível visualizar através deste repositório tudo que esta no seu projeto com o código `git status` esses arquivos que serão mostrados ainda não foram adicionados ao meu controle de versão eu só visualizei eles se você quiser adicionar esses arquivos existe duas opções selecionar um por um ou colocar todos os arquivos, para adicionar individualmente e só usar o código `git add "index.html"`, para adicionar todos os arquivos e só colocar um . em vez do nome desta forma `git add .` agora eu preciso criar uma versão para meu código fonte ou seja fazer um commit para ser enviado para nuvem e para fazer isso se usa o código `git commit -m "commit inicial"` o próximo passo seria enviar para o **GitHub** usando o código `git push` porem ainda e necessário configurar um repositório para que isso seja feito, No caso crie um repositório dentro do **GitHub** e depois disso vc precisa conectar o git com o **GitHub** para isso precisaremos de alguns códigos 

```git
git config --global user.name "JhonyWesley"
git config --global user.email "jhon-y-19@hotmail.com"

git commit -m "commit inicial"

git remote add origin AQUI VAI O LINK DO REPOSITORIO FEITO NO GITHUB

git push --set-upstream origin master
```

Bom agora estamos com nossos arquivos no repositório na branch **master**  para ver quais as  branch eu tenho  criado eu uso o código `git branch` e para eu criar uma nova branch eu vou usar o código `git branch Dev2` e no caso se eu quiser sair da branch que eu estou no caso a master e ir para a branch que eu criei eu uso o código `git checkout Dev2` agora todos códigos e arquivos que eu fizer vai para branch Dev2, se eu quiser ver todas as versões do meu arquivo e as suas branchs  o código é `git reflog` e se por algum motivo precisar de voltar para alguma versão o código `git reset --hard iddavesão` vai fazer esse trabalho usando o id da versão que vc quer retornar.

Ao criar seu software existem alguns arquivos que não são necessários para serem enviados para o repositório ou talvez por questões de segurança não deva se enviado como teste com banco de dados ou senhas e assim por diante para isso existe o _gitignore_  assim quando necessário descreva esses arquivos nessas parta e ele não vai ir para o repositório para criar esse arquivo usa o código `touch .gitignore`.

Imaginado que foi validado tudo que foi feito dentro da sua branch Dev2 e agora você quer implementar isso na branch principal a master, para fazer isso primeiro você tem que verificar que esta na branch master se não estiver e necessário que coloque nela apos confirmar isso e preciso digitar o seguinte código `git merge Dev2`  perceba que de dentro da minha branch principal eu linkei a branch que eu queria que fosse juntada e assim as duas branch foram unidas.

## Segue a baixo um resumo dos códigos e suas funções:

|**Comando**|**Descrição / Função**|
|---|---|
|`git init`|Inicializa um novo repositório Git na pasta atual.|
|`git clone [url]`|Cria uma cópia local de um repositório remoto.|
|`git status`|Exibe o estado dos arquivos (modificados, adicionados ou não monitorados).|
|`git add [arquivo]`|Adiciona um arquivo específico à área de preparação (_stage_).|
|`git add .`|Adiciona todas as alterações locais à área de preparação.|
|`git commit -m "[mensagem]"`|Salva as alterações da área de preparação no histórico local com uma mensagem.|
|`git log`|Exibe o histórico de _commits_ salvos no projeto.|
|`git branch`|Lista todas as ramificações (_branches_) existentes no repositório.|
|`git branch [nome]`|Cria uma nova ramificação (_branch_).|
|`git checkout [nome_branch]`|Alterna para a ramificação especificada.|
|`git checkout -b [nome_branch]`|Cria e alterna imediatamente para a nova ramificação.|
|`git merge [nome_branch]`|Combina o histórico da ramificação informada com a ramificação atual.|
|`git pull`|Baixa e aplica as alterações do repositório remoto no repositório local.|
|`git push`|Envia os _commits_ locais para o repositório remoto.|
|`git remote add origin [url]`|Vincula o repositório local a um repositório remoto.|


