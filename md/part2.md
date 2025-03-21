 ## 1.Inicializar Terraform

Ejecutamos el siguiente comando para inicializar Terraform en el directorio del proyecto:

```sh
terraform init
```
![alt text](image-7.png)

## 2. Validar la configuración de Terraform

Verificamos que la sintaxis de los archivos de configuración de Terraform sea correcta:

```sh
terraform validate
```
![alt text](image-8.png)

## 3, Ver el plan de ejecución

Genera un plan de ejecución para ver qué cambios se aplicarán en la infraestructura:

```sh
terraform plan
```

![alt text](image-11.png)

## 4  Aplicar la configuración

Para desplegar la infraestructura en Azure
```sh
terraform apply
```
![alt text](image-12.png)

![alt text](image-13.png)

## 5 Nos conectamos a la vm

![alt text](image-14.png)

## 6 Eliminar la infraestructura (opcional)

para eliminar todos los recursos creados, se usa

```sh
terraform destroy
```
![alt text](image-15.png)