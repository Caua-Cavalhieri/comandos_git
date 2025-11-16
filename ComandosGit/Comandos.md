git init = inicializa um repositório vazio

git add *nome do arquivo* = manda os arquivos pra área de stading (não seis e tá escrito corretamente, mas seria meio que um "fica esperto, vou comitar vc jaja")

git status = autoexplicativo

git commit -m "mensagem que representa o commit" = envia o arquivo para o repositório remoto

git branch -M "main" = altera o nick da branch principal(master) para main

git remote add origin *link do github* = estabelece a conexão entre o pc e o repositório do gitHUB

git push -u origin main = empurra os commits do repositório local para o GitHub(repositório remoto)

------------------------------------------------------------------------------------------------------------------------------------------------------

git checkout -b "nome da nova branch" = cria uma nova branch(ramificação) do repositório e entra nela

git checkout "branch" = troca de branch

git merge *branch alvo* = faz a junção de duas branchs (a que está sendo alterada no momento e a selecionada)

git clone *link do repositorio que quer clonar.git* = clona o repositorio de algum github

git pull = quando dentro do arquivo e já no repositório do bash ele puxa possíveis novas alterações do arquivo