# ADR-09.Arquitectura por capas para la comunicación de sensores

* Status: accepted
* Deciders: ASS,ASC
* Date: 2022-11-16

Technical Story: Architecture Decision

## Context and Problem Statement

Se necesita implementar una comunicación entre 3 sensores, de forma que el primero envía información al segundo y este al tercero que finalmente lo envía al centro de notificaciones.

## Decision Drivers

* Ya que los sensores se conectan solo con otro o con el centro de notificaciones, en una única dirección, y aquel con el que se comunican lo hace de igual forma con el “nivel inferior”, puede verse como un intercambio de datos de desde capas superiores a inferiores.

## Considered Options

* ADR-09
* ADR-09.1

## Decision Outcome

Chosen option: "ADR-09", because Se ha tomado esta decisión como válida, ya que permite representar la comunicación individual y unidireccional, de los distintos sensores.
