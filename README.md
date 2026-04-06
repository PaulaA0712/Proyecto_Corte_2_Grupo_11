# Proyecto_Corte_2_Grupo_11
Sistema logístico Ruta Óptima con POO y SQLite Public 

## Descripción General

Ruta Óptima App es una solución tecnológica diseñada para optimizar la gestión logística de envíos, permitiendo administrar clientes, paquetes y procesos de entrega de manera estructurada y eficiente.

El sistema implementa una arquitectura escalable basada en Programación Orientada a Objetos (POO) y una base de datos relacional en SQLite, garantizando organización, reutilización de código y eficiencia en el manejo de datos.

### Arquitectura del Sistema

El proyecto está estructurado en dos componentes principales:

1. Capa Lógica (POO)

Se implementan clases que representan las entidades del sistema:

Clases Padre:
Cliente
Paquete
Envio
Clases Hijo (Herencia):
ClientePremium
PaqueteLigero
PaquetePesado
EnvioExpress

Se aplican conceptos de:

Encapsulamiento (atributos privados + métodos get/set)
Herencia
Reutilización de código

2. Capa de Datos (Base de Datos)

Se utiliza SQLite con un modelo relacional compuesto por:

clientes
paquetes
envios

Relaciones:

Un cliente puede tener múltiples paquetes (1)
Un paquete puede generar múltiples envíos (1)

Funcionalidades Principales
CRUD completo de clientes
Registro y gestión de paquetes
Asociación de envíos
Consultas con JOIN entre tablas
Manejo de errores con try-except

## Integrantes: 
- Paula Andrea Arciniegas Cárdenas
- Valeria Morales
- Isabella Carranza Tapiero
