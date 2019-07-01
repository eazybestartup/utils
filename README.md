# utils

Configurações
Configurar chaves ssh com o github 
Clonar na mesma estrutura de pasta os repositórios de https://gitlab.com/dev-mmcafe
No arquivo ~/.bashrc
Definir a variável de ambiente REPOS-EB para a pasta raiz dos repositórios (ex.: export REPOS=/home/mmuser/work)
Adicionar na variável de ambiente PATH :$REPOS/utils/bin (ex.: PATH="$PATH:$JAVA_HOME/bin:$MVN_HOME/bin:$GO_INSTALL/bin:$GOPATH/bin:$REPOS/install/utils/bin")

Comandos

start (iniciar os containers docker dos Serviços via docker-compose)
stop (para os serviços docker-compose)
restart (stop e start)
update (executa git pull repositórios dos Serviços e atualiza as imagens docker)
logs (logs do docker-compose)
stats (exibe os processos docker consumo/cpu/etc)
sql (abre um prompt de comando direto no postgresql para analise dos bancos e tabelas)
purge (remove todos containers associados ao docker-compose apagando todos os dados salvos)
test (não implementado)
update_api (atualiza uma api (auth/cms/user) no docker-compose da máquina 192.168.10.167)