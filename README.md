## Victor Andrade

## Tutorial GIT/GITHUB

## Inicializando um novo repositório: git init
Para criar um novo repositório, você vai usar o comando git init. git init é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório .git no diretório de trabalho atual. Essa ação também vai criar uma ramificação principal.

## Controlando a versão de um projeto existente com um novo repositório git
Este exemplo pressupõe que você já tem uma pasta de projeto existente dentro da qual gostaria de criar o repositório. Você primeiro fará cd à pasta raiz do projeto e depois executará o comando git init.
 Apontar git init a um diretório de projeto existente executará a mesma configuração de inicialização mencionada acima, mas com escopo para este diretório de projeto.
 
## Clonando um repositório existente: git clone
Se um projeto já foi configurado em um repositório central, o comando clonar é a forma mais comum para os usuários obterem um clone de desenvolvimento local. Como o git init, a clonagem é geralmente uma operação única. Depois que um desenvolvedor obtiver uma cópia ativa, todas as operações de controle de versão serão gerenciadas pelo seu repositório local.
git clone é usado para criar uma cópia ou clone de repositórios remotos. Você transmite o git cline em uma URL de repositório. O Git é compatível com alguns protocolos de rede diferentes e formatos correspondentes de URL. Neste exemplo, usaremos o protocolo SSH de Git. As URLs do SSH de Git seguem um modelo de:git@HOSTNAME:USERNAME/REPONAME.git

Um exemplo de URL de SHH de Git seria: git@bitbucket.org:rhyolight/javascript-data-store.git em que os valores de modelo são correspondentes:

HOSTNAME: bitbucket.org
USERNAME: rhyolight
REPONAME: javascript-data-store
Quando executada, a versão mais recente dos arquivos do repositório remoto na ramificação principal vai ser transferida e adicionada a uma nova pasta. A nova pasta vai ser nomeada de acordo com o REPONAME, neste caso, javascript-data-store. A pasta vai conter o histórico completo do repositório remoto e a ramificação principal recém-criada.
Para obter mais documentos sobre o uso de git clone e formatos de URL de Git suportados, visite a Página git clone.
