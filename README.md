# Proyecto de Calculadora de Amortización en C# con .NET Framework y SQL

## Descripción del Proyecto

Este proyecto es una aplicación en C# desarrollada con .NET Framework que se encarga de calcular la amortización de préstamos. Utiliza una base de datos SQL para almacenar la información de los préstamos y LINQ para acceder y manipular los datos.

## Funcionalidades Principales

1. **Registro de Préstamos:**
   - Permite ingresar la información de los préstamos, como el monto, la tasa de interés y el plazo.

2. **Cálculo de Amortización:**
   - Implementa algoritmos para calcular el cronograma de amortización, desglosando los pagos mensuales en capital e intereses.

3. **Visualización de Datos:**
   - Proporciona interfaces de usuario para ver el resumen de los préstamos y sus cronogramas de amortización.

4. **Base de Datos SQL:**
   - Utiliza una base de datos SQL para almacenar y gestionar la información de los préstamos.

5. **LINQ para Acceso a Datos:**
   - Implementa LINQ (Language Integrated Query) para realizar consultas y manipular los datos almacenados en la base de datos SQL.

## Requisitos del Sistema

- **Visual Studio:** Se requiere el entorno de desarrollo Visual Studio para abrir y compilar el proyecto.

- **.NET Framework:** El proyecto está desarrollado utilizando .NET Framework, asegúrate de tener la versión adecuada instalada.

- **SQL Server:** Se utiliza una base de datos SQL, por lo tanto, es necesario tener un servidor SQL disponible para la conexión.

## Configuración y Uso

1. Clona o descarga el repositorio en tu máquina local.

2. Abre el proyecto en Visual Studio.

3. Asegúrate de tener la conexión a la base de datos configurada en el archivo de configuración (`app.config`).

4. Compila el proyecto y ejecútalo.

5. Utiliza la interfaz de usuario para ingresar información de préstamos, calcular amortizaciones y visualizar los resultados.

## Estructura del Proyecto

- **AmortizacionCalculator:** Contiene la lógica principal de la aplicación.
  - **Models:** Define las clases de modelos para representar la información de los préstamos.
  - **DataAccess:** Contiene las clases para el acceso a la base de datos utilizando LINQ.
  - **Calculators:** Implementa los algoritmos de cálculo de amortización.

- **AmortizacionCalculator.UI:** Interfaz de usuario para interactuar con la aplicación.

## Contribuciones y Problemas

Si encuentras algún problema o tienes sugerencias para mejorar el proyecto, por favor, abre un issue en el repositorio. ¡Las contribuciones son bienvenidas!
