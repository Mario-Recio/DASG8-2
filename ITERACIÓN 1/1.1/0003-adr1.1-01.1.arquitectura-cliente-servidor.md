# ADR-01.Arquitectura cliente-servidor

* Status: deprecated
* Deciders: ASS,ASC
* Date: 2022-11-04

Technical Story: Architecture Decision

## Context and Problem Statement

Se requiere una pasarela para poder comunicar a los operarios que quieran consumir eventos o notificaciones, con la estructura que almacena la información.

## Decision Drivers

* Así se comunicaría el sistema interno con la base de datos, para poder acceder a toda la información que se quiera consultar.

## Considered Options

* ADR-01
* ADR-01.1

## Decision Outcome

Chosen option: "ADR-01", because Se ha escogido esta opción porque es conveniente para persistir datos dentro del sistema interno de recogida de información de los sensores.
