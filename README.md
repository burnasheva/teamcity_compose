# teamcity_compose
Simple compose files to run TeamCity server together with agents

* to run latest released version use: `docker-compose up -d`
* to run latest eap use: `docker-compose -f docker-compose.yml -f docker-compose.eap.yml up -d`

TeamCity server is available on http://localhost:8112/.
