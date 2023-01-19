# ADR-05.Patrón Singleton para almacenar inventario y órdenes

* Status: accepted
* Deciders: ASS,ASC
* Date: 2022-11-09

Technical Story: Architecture Decision

## Context and Problem Statement

Se necesita implementar una base de datos SQL en el sistema que tenga conexión con el módulo de ordenes de trabajo, para almacenar la información de estas, así como el estado de los dispositivos físicos y el inventario.

## Decision Drivers

* Ya que solo se tiene una instancia de la base de datos, y se quiere controlar el acceso a esta, de forma que haya una única forma de acceso global, se implementa un patrón singleton.

## Considered Options

* ADR-05

## Decision Outcome

Chosen option: "ADR-05", because La decisión se acepta, ya que no consideramos otra forma mejor de afrontar la incorporación de la base de datos
