# Elasticsearch + Kibana for workshop playground

## Requirements 

- docker
- docker-compose


## Start everything

In a shell

    docker-compose up

or, if you prefer to keep them running in background

    docker-compose up -d

Then open http://localhost:5601 in your browser.

It may take several seconds to have them ready, be patient.


## Stop and remove containers

    docker-compose stop
    docker-compose rm -f


## Reset data

Remove everything in the folder `data`.