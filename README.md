# jalapeno-deployment

# Installation instructions
1. create namespace "jalapeno"
2. install using helm ``helm install jalapeno . -n jalapeno``

If ingress is not configured on the cluster use the NodePort definition in the values.yaml file and comment the ingress definition.

## Known Bugs
- arangodb works only with image tag ``3.6.12``
- influxdb has to be set to version ``1.7``

