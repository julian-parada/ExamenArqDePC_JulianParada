# ExamenArqDePC_JulianParada

## Objetivo
Desplegar y eliminar una instancia EC2 en AWS usando CloudFormation y GitHub Actions con Git Flow.

## Tecnologías utilizadas
- AWS CloudFormation
- AWS EC2
- GitHub Actions
- Git Flow

## Funcionalidad de Deploy
El workflow `deploy.yml` valida el template, despliega el stack y crea la EC2 con una página web funcional.

## Funcionalidad de Destroy
El workflow `destroy.yml` elimina el stack completo de CloudFormation incluyendo la EC2 y el Security Group.

## Template EC2
Crea una instancia EC2 Amazon Linux con puerto 80 habilitado y una página web con datos del estudiante.