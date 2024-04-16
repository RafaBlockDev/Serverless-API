# Serverless-API

Serverless 

# IAM

## IAM User

Usuarios que gestionan los servicios de AWS

## IAM Role

Servicio interno que gestiona el resto de servicios

## IAM Permissions

Conjunto de acciones, recursos y permisos que se asocian a una política. Define que puede hacer y que no, IAM User/Role

### Framework User

- IAM User: para los despliegues
- IAM Role: para la ejecución del Lambda


## AWS

- CloudFormation -> flujo para deployment
- API Gateway -> endpoints
- AWS Lambda -> donde se ejecuta el código
- Amazon S3 -> donde se almacena el API Gateway y AWS Lambda
- Cloudwatch -> Alejar logs de la app
- 