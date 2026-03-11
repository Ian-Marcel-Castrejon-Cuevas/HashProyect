# HashProyect – Sistema Bancario con Hashtable

Aplicación desarrollada en **Java** que simula un sistema básico de gestión de cuentas bancarias utilizando **estructuras de datos Hash (Hashtable)** para almacenar y administrar la información de los clientes.

## Funcionalidades

* Registro de nuevos clientes.
* Generación automática de número de cuenta.
* Consulta de cuentas bancarias por número.
* Eliminación de cuentas registradas.
* Visualización de clientes y saldos en una interfaz gráfica.

## Tecnologías utilizadas

* Java
* Java Swing (interfaz gráfica)
* Hashtable
* ArrayList

## Cómo funciona

El sistema permite registrar clientes ingresando su **nombre y saldo inicial**.
El programa genera automáticamente un **número de cuenta único** y guarda la información en estructuras de datos tipo **Hashtable**.

Desde la interfaz el usuario puede:

* **Registrar** nuevos clientes.
* **Buscar** una cuenta existente.
* **Eliminar** una cuenta del sistema.

Los datos se muestran en una **tabla dentro de la interfaz gráfica**.

## Estructura del proyecto

```
HashProyect
 ├── src
 │   └── aplicaciones
 │       ├── Aplicacion.java
 │       └── Aplicacion.form
 ├── pom.xml
 └── README.md
```

## Autor

Ian Marcel Castrejón Cuevas
Ingeniería en Sistemas Computacionales
