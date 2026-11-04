# ⚡ Automatización Industrial | Lógica Cableada – Práctica 02

<img width="1412" height="886" alt="circuito cadesimu" src="https://github.com/user-attachments/assets/52319796-0b61-4dc4-8a68-5f708352142a" />

<p align="center">
  <strong>Diseño y simulación de un circuito de automatización mediante lógica cableada</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CADe--SIMU-Circuit%20Design-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Industrial%20Automation-Control-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Electrical%20Engineering-Practice-success?style=for-the-badge" />
</p>

---

## 📌 Descripción del proyecto

Este repositorio contiene el desarrollo de una práctica de **automatización industrial mediante lógica cableada**, realizada utilizando CADe_SIMU.

El proyecto consiste en el diseño de un circuito eléctrico de mando y potencia, incorporando diferentes elementos de control, maniobra y protección para gestionar el funcionamiento de un motor trifásico.

Se trabaja con contactores, contactos auxiliares, elementos de protección y temporización, aplicando los principios fundamentales de los sistemas de automatización electromecánica.

El objetivo es comprender la interacción entre los componentes eléctricos y la lógica de funcionamiento del sistema, así como desarrollar criterios de diseño, control y seguridad industrial.

## 🎯 Objetivos técnicos

- Diseñar un circuito de potencia y mando mediante lógica cableada.
- Comprender el funcionamiento de los contactores y sus contactos auxiliares.
- Implementar elementos de temporización en una secuencia de control.
- Aplicar criterios de protección eléctrica.
- Analizar las relaciones entre las señales de entrada y las salidas de maniobra.
- Familiarizarse con el diseño y la simulación de instalaciones de automatización industrial.

## ⚙️ Componentes del sistema

| Referencia | Componente | Función |
|---|---|---|
| U1 | Motor trifásico | Elemento receptor del sistema |
| KM1 | Contactor | Maniobra eléctrica |
| KM2 | Contactor | Maniobra eléctrica |
| KM3 | Contactor | Maniobra eléctrica |
| T1 | Temporizador | Control temporal |
| K2 / K3 | Relés auxiliares | Gestión de señales de control |
| S1 | Interruptor / selector | Entrada de mando |
| F | Elementos de protección | Protección del circuito |

*La identificación funcional se basa en las referencias visibles en el esquema CADe_SIMU.*

## 🧠 Arquitectura del circuito

El diseño se estructura en dos partes principales:

### 1. Circuito de potencia

Encargado de gestionar la alimentación del motor trifásico y la maniobra de potencia mediante los contactores correspondientes.

### 2. Circuito de mando

Gestiona las condiciones de funcionamiento mediante:

- Señales de entrada.
- Contactos auxiliares.
- Relés de control.
- Temporización.
- Activación y desactivación de los contactores.

Esta separación permite distinguir claramente la alimentación de la carga y la lógica responsable de controlar su funcionamiento.

## 🛠️ Software y tecnologías

| Herramienta | Aplicación |
|---|---|
| CADe_SIMU | Diseño y simulación de circuitos eléctricos |
| Lógica cableada | Implementación del sistema de control |
| Automatización industrial | Aplicación de maniobras electromecánicas |

## 📁 Estructura del repositorio

```text
Practica-02-Logica-Cableada/
│
├── README.md
│
├── circuitos/
│   └── Practica_Logo_2_Logica_Cableada.cad
│
└── documentacion/
    └── memoria_tecnica.pdf
```

*La estructura representa la organización recomendada del repositorio. La memoria técnica puede añadirse si se publica junto al proyecto.*

## 🚀 Cómo abrir el proyecto

1. Clonar o descargar este repositorio.
2. Instalar CADe_SIMU.
3. Abrir el archivo `.cad` incluido en la carpeta `circuitos`.
4. Revisar la distribución de los componentes y las conexiones.
5. Ejecutar la simulación para analizar el comportamiento del circuito.

## 🔍 Competencias desarrolladas

- Diseño de esquemas eléctricos industriales.
- Interpretación de circuitos de potencia y mando.
- Control electromecánico.
- Identificación de componentes eléctricos.
- Aplicación de lógica cableada.
- Comprensión de sistemas temporizados.
- Documentación técnica de instalaciones.

## 📚 Contexto académico

**Ciclo formativo:** Grado Medio – Técnico en Instalaciones de Telecomunicaciones  
**Especialidad aplicada:** Automatización y sistemas de control  
**Proyecto:** Práctica 02 – Lógica Cableada  
**Software:** CADe_SIMU

---

<p align="center">
  <strong>Desarrollado como parte del aprendizaje práctico en instalaciones y automatización industrial.</strong>
  <br/>
  <sub>Engineering · Industrial Automation · Electrical Control Systems</sub>
</p>
