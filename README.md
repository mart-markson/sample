# A sample of a running Symfony 5 simple blog application inside Docker containers

git clone git@github.com:mart-markson/sample.git

cd symfony-5-docker

cd docker

docker-compose up

docker exec -ti `your docker container ID>` sh -l

composer install

php bin/console doctrine:migrations:migrate

php bin/console doctrine:fixtures:load
