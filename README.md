# 💻 Sistema de Gestión de Servicios Tecnológicos

## 📌 Descripción del proyecto

Este proyecto consiste en desarrollar un sistema de gestión de servicios tecnológicos utilizando Python. Permite registrar diferentes tipos de servicios, consultar su información y calcular sus costos mediante un menú interactivo.

El sistema fue desarrollado para la materia **PFU-111 Programación Fundamental**, correspondiente a la Semana 11, Grupo 2, con el tema de **herencia y polimorfismo**.

## 🎯 Objetivos

- Aplicar los conceptos de programación orientada a objetos.
- Implementar herencia mediante una clase base y clases derivadas.
- Utilizar el polimorfismo para calcular los costos de diferentes servicios.
- Validar los datos ingresados por el usuario.
- Organizar el programa mediante funciones y clases.

## ⚙️ Funcionalidades

El sistema cuenta con las siguientes opciones:

1. **Registrar mantenimiento:** permite registrar servicios de mantenimiento de equipos.
2. **Registrar instalación:** permite registrar instalaciones de dispositivos tecnológicos.
3. **Registrar soporte técnico:** permite registrar servicios de soporte por horas.
4. **Mostrar servicios registrados:** muestra la información de los servicios guardados.
5. **Calcular costos individuales:** calcula el costo de cada servicio registrado.
6. **Calcular costo total:** suma los costos de todos los servicios.
7. **Salir:** finaliza la ejecución del programa.

## 🧱 Estructura del programa

El proyecto utiliza una clase base y tres clases derivadas:

- **`Servicio`:** contiene los atributos comunes, como código, cliente, descripción y precio base.
- **`Mantenimiento`:** calcula el costo según la cantidad de equipos y el costo por equipo.
- **`Instalacion`:** calcula el costo según la cantidad de dispositivos y el costo por dispositivo.
- **`SoporteTecnico`:** calcula el costo según las horas de atención y la tarifa por hora.

### Conceptos aplicados

- **Herencia:** las clases derivadas reutilizan los atributos y métodos de la clase `Servicio`.
- **Polimorfismo:** cada tipo de servicio implementa su propia versión del método `calcular_costo()`.
- **Encapsulamiento:** se utilizan atributos protegidos con el prefijo `_` y métodos para acceder a ellos.
- **Validación de datos:** se comprueba que los campos de texto no estén vacíos, que los códigos no se repitan y que los valores numéricos sean válidos.

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Python.
- **Paradigma:** programación orientada a objetos.
- **Interfaz:** menú interactivo por consola.
- **Control de versiones:** Git y GitHub.

## ▶️ Requisitos e instalación

Para ejecutar el proyecto necesitas tener instalado Python 3.10 o una versión superior, debido al uso de `match-case`.

### 1. Clonar el repositorio

```bash
git clone URL_DE_TU_REPOSITORIO
```

### 2. Entrar en la carpeta del proyecto

```bash
cd nombre-del-repositorio
```

### 3. Ejecutar el programa

```bash
python servicios_tecnologicos.py
```

Si tu sistema utiliza el comando `python3`, puedes ejecutar:

```bash
python3 servicios_tecnologicos.py
```

## 📋 Ejemplo de funcionamiento

Al ejecutar el programa, aparecerá el siguiente menú:

```text
===== SISTEMA DE GESTIÓN DE SERVICIOS TECNOLÓGICOS =====
1. Registrar un servicio de mantenimiento
2. Registrar un servicio de instalación
3. Registrar un servicio de soporte técnico
4. Mostrar los servicios registrados
5. Calcular y mostrar el costo de cada servicio
6. Mostrar el costo total de todos los servicios
7. Salir
```

El usuario puede seleccionar una opción e introducir los datos solicitados para registrar servicios y calcular sus costos.

## 📂 Archivo principal

- `servicios_tecnologicos.py`: contiene las clases, las funciones de validación, el menú principal y la lógica de registro y cálculo de costos.

## 👨‍🎓 Información académica

- **Materia:** PFU-111 Programación Fundamental.
- **Semana:** 11.
- **Grupo:** 2.
- **Proyecto:** Sistema de Gestión de Servicios Tecnológicos.
- **Tema:** Herencia y polimorfismo.


