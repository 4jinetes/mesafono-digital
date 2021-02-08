# Mesafono-digital
It is a project that we are covering for the operation of a set of tools for the analysis of open sources.
Now the added tools are the following:
- iKy

## Mandatory requirement must have installed:
- docker
- docker-compose

## Run the program:
- git clone https://github.com/4jinetes/mesafono-digital.git
- cd mesafono-digital
- docker-compose up
- open browser http://localhost:8100

## If it shows you this error
ERROR: Version in ".\docker-compose.yml" is unsupported. You might be seeing this error because you're using the wrong Compose file version. Either specify a supported version ("2.0", "2.1", "3.0") and place your service definitions under the `services` key, or omit the `version` key and place your service definitions at the root of the file to use version 1.
For more on the Compose file format versions, see https://docs.docker.com/compose/compose-file/
- Solution: change version: "3.2" for version: "3.0"
