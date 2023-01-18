Obtain the current Tokyo release application zip file from support.
Place the servicenow application zip file in this directory, e.g.

    glide-tokyo-07-08-2022__patch5-12-21-2022_01-06-2023_1054.zip

To build:

    docker build -t servicenow .
    
A sample docker-compose file is included. To run:

    docker-compose up -d
