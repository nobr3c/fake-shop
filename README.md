# Fake Shop


## Variável de Ambiente
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.

Executar o docker hub e rodar o commando a seguir

na pasta src rodar `docker build -t nobr3c/fake-shop:v1 --push . `

Em seguida aplicar: `kubectl apply -f k8s/deployment.yaml`

`kubectl get pod`

`kubectl get all`

`kubectl apply -f k8s/deployment.yaml`

`kubectl get pod`

`kubectl get service`



