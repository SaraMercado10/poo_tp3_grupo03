# Trabajo Práctico 3 - Clases y Objetos

## Programación Orientada a Objetos

**Carrera:** Analista Programador Universitario  
**Extensión Áulica:** San Pedro  
**Materia:** Programación Orientada a Objetos  
**Trabajo Práctico:** N.º 3 - Clases y Objetos  
**Lenguaje:** Java

---

# 👥 Integrantes

Este proyecto fue desarrollado por un **grupo de 4 integrantes**.

| N.º | Integrante |
|---:|---|
| 1 | BITANCUR ERIKA GINA |
| 2 | MERCADO SARA DENISE |
| 3 | ROMERO CELESTE AYELEN |
| 4 | URZAGASTI ALEJANDRA MARIELA |

> **Importante:** Este proyecto está conformado por cuatro integrantes, quienes participan en las diferentes etapas de análisis, diseño, implementación, pruebas y gestión del repositorio.

---

# 📌 Descripción del Proyecto

Este repositorio contiene el desarrollo del **Trabajo Práctico N.º 3 de Programación Orientada a Objetos**, correspondiente a la carrera **Analista Programador Universitario**, Extensión Áulica San Pedro.

El objetivo del trabajo es aplicar los conceptos fundamentales de la **Programación Orientada a Objetos** mediante el análisis, diseño e implementación de diferentes situaciones problemáticas utilizando el lenguaje **Java**.

El trabajo se divide en las siguientes etapas:

- Análisis.
- Diseño.
- Implementación.
- Pruebas.
- Gestión del código mediante Git y GitHub.

Los casos planteados permiten trabajar con conceptos fundamentales de POO, como:

- Clases.
- Objetos.
- Atributos.
- Operaciones.
- Métodos.
- Constructores.
- Encapsulamiento.
- Sobreescritura del método `toString()`.
- Clases de prueba.

---

# 📚 Casos del Trabajo Práctico

El enunciado presenta tres situaciones diferentes para analizar, diseñar e implementar.

---

## 🧮 Caso 1 - Cálculo del IMC

### Contexto

Un médico nutricionista desea automatizar el cálculo del **Índice de Masa Corporal (IMC)** de sus pacientes a partir de su altura en metros y peso en kilogramos.

### Datos

- Altura en metros.
- Peso en kilogramos.

### Fórmula

`IMC = peso / (altura * altura)`

El objetivo del caso es identificar los elementos necesarios para representar la información del paciente y realizar el cálculo correspondiente mediante una clase.

---

## 💰 Caso 2 - Simulador de Plazo Fijo

### Contexto

Una entidad financiera desea desarrollar un simulador de plazo fijo que permita calcular y visualizar la rentabilidad obtenida al depositar un capital durante un determinado plazo.

### Condiciones

Según el enunciado:

- El capital debe ser mayor a `$1000`.
- El plazo debe ser mayor a `30 días`.
- La tasa de interés TNA por defecto es del `33%`.

### Fórmula

`rentabilidad = capital * (tasa de interés / 100 * plazo / 365)`

### Ejemplo

**Entrada:**

- Capital: `$1.000.000`
- Plazo: `30 días`

**Salida:**

- Rentabilidad: `$27.123,29`

---

## 🏎️ Caso 3 - Auto de Carrera

### Contexto

Una empresa de videojuegos desea modelar un **auto de carrera**.

El auto se caracteriza por los siguientes atributos:

- `id`
- `marca`
- `color`
- `velocidad`
- `temperatura del motor`
- `combustible`
- `estado`

### Estados posibles

El estado del auto puede ser:

- `STOPPED`
- `RUNNING`
- `IN_BOX`

### Operaciones principales

El auto debe soportar las siguientes operaciones:

- Encender.
- Acelerar.
- Frenar.
- Apagar.
- Mostrar estado.

Al mostrar el estado se debe poder visualizar información relacionada con:

- Velocidad.
- Temperatura.
- Combustible.

### Reglas de comportamiento

El enunciado establece las siguientes reglas:

1. Cuando se acelera, la velocidad aumenta en `10`.
2. Solo se puede acelerar si el auto está encendido.
3. Cuando se frena, la velocidad disminuye en `10`.
4. Cuando la velocidad está en `0 km/h`, el auto se encuentra detenido y puede apagarse.

---

# 🔎 Etapa de Análisis

Para cada uno de los casos se deben identificar los elementos necesarios para modelar la solución.

## Historias de Usuario

Se deben especificar las **Historias de Usuario (HU)** correspondientes a cada caso, teniendo en cuenta las necesidades planteadas en cada contexto.

## Componentes

Se deben identificar los principales componentes involucrados en cada situación.

## Atributos

Se deben determinar los atributos necesarios para representar la información de cada objeto.

## Operaciones

Se deben identificar las operaciones y comportamientos que cada objeto debe soportar.

---

# 📐 Etapa de Diseño

Para cada caso se debe realizar un **diagrama de clases UML** que represente la solución propuesta.

Los diagramas deben permitir identificar los principales elementos de cada clase, entre ellos:

- Clases.
- Atributos.
- Operaciones.
- Constructores.
- Visibilidad de los elementos.
- Relaciones que correspondan.

El diseño UML constituye la base para la posterior implementación de las clases en Java.

---

# ☕ Etapa de Implementación

Las soluciones correspondientes a los casos planteados se implementan utilizando el lenguaje **Java**.

Para cada caso se deben implementar las clases correspondientes, contemplando:

- Atributos.
- Métodos.
- Constructores.
- Reglas de comportamiento.
- Sobreescritura de `toString()`.
- Clases de prueba.

---

# 🏗️ Constructores

Se implementan los constructores que se consideren necesarios para realizar una **inicialización segura y rápida de los objetos**.

Los constructores permiten establecer los valores iniciales de los atributos al momento de crear cada instancia.

---

# 📝 Método `toString()`

Las clases implementadas deben sobreescribir el método `toString()` para mostrar información relevante de los objetos.

Esto permite representar los datos de una instancia de manera clara y facilita las pruebas y la visualización de resultados.

---

# 🧪 Clases de Prueba

Para cada caso se deben implementar las correspondientes **clases de prueba**.

Las clases de prueba permiten verificar el correcto funcionamiento de:

- Constructores.
- Creación de objetos.
- Métodos.
- Cálculos.
- Cambios de estado.
- Reglas de comportamiento.
- Método `toString()`.

---

# 📁 Estructura del Proyecto

La estructura del proyecto puede organizarse de la siguiente manera:

    poo_tp3_grupo999/
    │
    ├── src/
    │   ├── caso1/
    │   │   ├── ...
    │   │   └── ...
    │   │
    │   ├── caso2/
    │   │   ├── ...
    │   │   └── ...
    │   │
    │   └── caso3/
    │       ├── ...
    │       └── ...
    │
    ├── .gitignore
    ├── README.md
    └── ...

> La estructura definitiva de paquetes y clases dependerá de la organización adoptada por el grupo durante la implementación.

---

# 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| **Java** | Implementación de las soluciones |
| **Git** | Control de versiones |
| **GitHub** | Repositorio y trabajo colaborativo |
| **UML** | Modelado y diseño de clases |

---

# 🔀 Git y GitHub

El proyecto utiliza **Git y GitHub** para facilitar el control de versiones y el trabajo colaborativo entre los **cuatro integrantes** del grupo.

El repositorio debe tener el nombre:

`poo_tp3_grupo999`

donde `999` corresponde al número asignado al grupo.

Todos los integrantes deben clonar el repositorio para disponer de una copia local del proyecto.

## Flujo de trabajo

    Repositorio GitHub
           │
           ├───────────────┐
           │               │
           ▼               ▼
     Integrante 1     Integrante 2
           │               │
           │               │
           ▼               ▼
     Integrante 3     Integrante 4
           │               │
           └───────┬───────┘
                   │
                   ▼
            Repositorio GitHub

Los cambios realizados durante el desarrollo deben registrarse mediante commits y posteriormente enviarse al repositorio remoto.

---

# 📦 Práctico 2

Como parte del trabajo práctico también se debe compartir en el repositorio el proyecto correspondiente al **Práctico 2**.

Sobre dicho proyecto se solicita:

- Implementar los constructores que se consideren necesarios para la inicialización segura y rápida de los objetos.
- Sobreescribir el método `toString()`.
- Subir las actualizaciones correspondientes al repositorio.

---

# 🎯 Objetivos

Los principales objetivos del trabajo son:

- Comprender y aplicar los fundamentos de la Programación Orientada a Objetos.
- Identificar clases y objetos a partir de diferentes problemáticas.
- Identificar atributos y operaciones.
- Diseñar soluciones mediante diagramas de clases UML.
- Implementar las soluciones utilizando Java.
- Utilizar constructores.
- Sobreescribir el método `toString()`.
- Implementar clases de prueba.
- Aplicar las reglas de comportamiento de los objetos.
- Utilizar Git y GitHub.
- Desarrollar un proyecto de manera colaborativa entre cuatro integrantes.

---

# 👥 Trabajo Colaborativo

Este proyecto es desarrollado por un **grupo de 4 integrantes**.

El trabajo colaborativo contempla las siguientes etapas:

    Análisis
       ↓
    Diseño UML
       ↓
    Implementación
       ↓
    Pruebas
       ↓
    Control de versiones
       ↓
    Repositorio GitHub

El uso de Git y GitHub permite mantener un historial de cambios y facilitar la integración del trabajo realizado por los diferentes integrantes.

---

# 📋 Requisitos del Trabajo

- [ ] Crear el repositorio de GitHub correspondiente al grupo.
- [ ] Crear el proyecto Java.
- [ ] Compartir el proyecto en el repositorio.
- [ ] Clonar el repositorio por parte de los cuatro integrantes.
- [ ] Realizar las Historias de Usuario.
- [ ] Identificar componentes, atributos y operaciones.
- [ ] Elaborar los diagramas de clases UML.
- [ ] Implementar las clases en Java.
- [ ] Implementar los constructores necesarios.
- [ ] Sobreescribir `toString()`.
- [ ] Implementar las clases de prueba.
- [ ] Subir las implementaciones al repositorio.
- [ ] Incorporar el proyecto correspondiente al Práctico 2.
- [ ] Implementar los constructores necesarios en el Práctico 2.
- [ ] Sobreescribir `toString()` en el Práctico 2.
- [ ] Subir las actualizaciones al repositorio.

---

# 📄 Información Académica

| Campo | Información |
|---|---|
| **Carrera** | Analista Programador Universitario |
| **Materia** | Programación Orientada a Objetos |
| **Extensión Áulica** | San Pedro |
| **Trabajo Práctico** | TP3 - Clases y Objetos |
| **Lenguaje** | Java |
| **Control de versiones** | Git |
| **Plataforma** | GitHub |
| **Cantidad de integrantes** | **4** |
| **Repositorio** | `poo_tp3_grupo999` |

---

# ✨ Autores

## Grupo de 4 integrantes

- **Sara Mercado**
- **Nombre del integrante 2**
- **Nombre del integrante 3**
- **Nombre del integrante 4**

---

# 📚 Contenido del Trabajo

El repositorio contiene las diferentes etapas correspondientes al Trabajo Práctico N.º 3:

| Etapa | Contenido |
|---|---|
| 🔎 **Análisis** | Historias de Usuario, componentes, atributos y operaciones |
| 📐 **Diseño** | Diagramas de clases UML |
| ☕ **Implementación** | Clases Java, atributos, métodos y constructores |
| 🧪 **Pruebas** | Clases de prueba y verificación del funcionamiento |
| 🔀 **Git/GitHub** | Control de versiones y trabajo colaborativo |

---

# 🏁 Conclusión

El presente proyecto tiene como finalidad aplicar los conocimientos adquiridos en **Programación Orientada a Objetos**, desarrollando soluciones en Java a partir de diferentes situaciones problemáticas.

A través del análisis, diseño UML, implementación y pruebas, se busca comprender el proceso completo de construcción de una solución orientada a objetos.

El proyecto se desarrolla de manera colaborativa mediante **Git y GitHub**, contando con la participación de **cuatro integrantes**.

---

> **Trabajo Práctico N.º 3 - Clases y Objetos**
>
> **Programación Orientada a Objetos**
>
> **Analista Programador Universitario**
>
> **Extensión Áulica San Pedro**
>
> **Proyecto desarrollado por un grupo de 4 integrantes.**
