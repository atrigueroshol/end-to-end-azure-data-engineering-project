# Azure Environment Setup
En este documento se procede a explicar como se debe hacer el set up de los recursos en Azure para el funcionamiento del proyecto.

## 1 Resource Group
En primer lugar, debemos crear un contenedor para definir los recursos de Azure que vamos a necesitar en el proyecto. Para ello,  debemos ir al portal de Azure y buscar en `Resorce Group` en el buscador. Seleccionamos la opción de `Crear`. Una vez hemos seleccionado la opción de crear se nos mostrará un formulario en el que tendremos que seleccionar la Subscipcción de Azure que queremos asignar este grupo de recursos para la facturación de los mismos, el nombre del grupo de recursos y la Región que mejor encaje con nuestras necesidades. La pestaña de `Etiquetas` la podemos ignorar.

<p align="center">
  <img src="https://github.com/atrigueroshol/end-to-end-azure-data-engineering-project/blob/main/img/resource_group.png?raw=true" alt="Texto alternativo">
</p>
 
 Una vez creado el grupo de recursos vamos a seleccionar los recursos que necesitamos para el proyecto. Dentro de nuestro grupo de recursos debemos seleccionar la opción de `Crear` y seleccionar el recurso que queremos asignar en el contenedor.
 
### Storage Account
Cuando seleccionamos la opción de Storage Account se nos mostrará un formulario con los datos a rellenar. La Subscripción y el Grupo de Recursos se rellenarán automáticamente. Debemos rellenar el nombre de la instancia, la región y la versión. Además debemos indicar el tipo de almacenamiento que queremos, en nuestro caso `Azure Data Lake Storage Gen 2`. El resto de pestañas podemos ignorarlas.

<p align="center">
  <img src="https://github.com/atrigueroshol/end-to-end-azure-data-engineering-project/blob/main/img/st_acc.png?raw=true" alt="Texto alternativo">
</p>
 
### Azure Data Factory
 
Cuando seleccionamos la opción de Azure Data Factory se nos mostrará un formulario con los datos a rellenar. La Subscripción y el Grupo de Recursos se rellenarán automáticamente. Debemos rellenar el nombre de la instancia, la región y la versión. El resto de pestañas podemos ignorarlas.

<p align="center">
  <img src="https://github.com/atrigueroshol/end-to-end-azure-data-engineering-project/blob/main/img/data_factory%20.png?raw=true" alt="Texto alternativo">
</p>

### Azure Databricks
Cuando seleccionamos la opción de Azure Databricks se nos mostrará un formulario con los datos a rellenar. La Subscripción y el Grupo de Recursos se rellenarán automáticamente. Debemos rellenar el nombre de la instancia, la región y la versión. El resto de pestañas podemos ignorarlas.

<p align="center">
  <img src="https://github.com/atrigueroshol/end-to-end-azure-data-engineering-project/blob/main/img/databricks_resource.png?raw=true" alt="Texto alternativo">
</p>
