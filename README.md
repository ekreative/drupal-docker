# Drupal docker image

Image used for running drupal tests on our ci server

## Build command

    docker build -t ekreative/drupal .

## Build an app

    docker run -ti --rm --volume=$(pwd):/opt/workspace ekreative/drupal ./bin/phpunit
