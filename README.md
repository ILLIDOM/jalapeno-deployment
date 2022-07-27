# jalapeno-deployment

# Installation instructions
1. create namespace "jalapeno"
2. install using helm ``helm install jalapeno . -n jalapeno``

# Changes to ArangoDB
If the arangoDB gets changed the ArangoDB Chart has to be rebuild and copied into the charts folder of the Jalapeno Chart.

- build ArangoDB Chart: ``helm package .``

## Known Bugs
- arangodb works only with image tag ``3.6.12``
- influxdb has to be set to version ``1.7``