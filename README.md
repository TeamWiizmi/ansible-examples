## Add a user with username "deploy"
`ansible-playbook user.yml -i stage`

## Install Nginx webserver
`ansible-playbook webservers.yml -i stage`

## Install Mysql
`ansible-playbook dbservers.yml -t mysql -i stage`

## Install Postgresql
`ansible-playbook dbservers.yml -t postgres -i stage`

## Install Rbenv + Ruby + Nodejs
`ansible-playbook appservers.yml -i stage`
