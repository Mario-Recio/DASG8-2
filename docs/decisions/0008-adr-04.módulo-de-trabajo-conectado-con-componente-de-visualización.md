# ADR-04.Módulo de ordenes de trabajo conectado con componente de visualización

* Status: deprecated
* Deciders: ASS,ASC
* Date: 2022-11-23

Technical Story: Architecture Decision

## Context and Problem Statement

Se requiere un módulo de órdenes de trabajo para gestionar toda la operativa de cada trabajador y máquina.

## Decision Drivers

* Dentro de los usuarios que consumen las notificaciones enviadas por el sistema interno, habrá un apartado específico para gestionar las necesidades de cada operador.

## Considered Options

* ADR-04
* ADR-04.1

## Decision Outcome

Chosen option: "ADR-04", because Se tomará esta opción como válida ya que se realizará un MVC donde se incluirán el componente de visualización para los operarios, de forma que se utilice dicho componente desde el módulo de órdenes.
