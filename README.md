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


## Install sample data
While the container is running, to install the sample data open http://localhost:5601/app/kibana#/home/tutorial_directory/sampleData.

There will be three samples. Install all of them.


## Stop and remove containers

    docker-compose stop
    docker-compose rm -f


## Reset data

Remove everything in the folder `data` except `.gitkeep` file.
