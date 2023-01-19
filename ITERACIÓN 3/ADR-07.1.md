# ADR-07.1.Suscripción por tópicos al gestor de eventos

* Status: rejected
* Deciders: ASS,ASC
* Date: 2022-11-16

Technical Story: Architecture Decision

## Context and Problem Statement

Se requiere un sistema que sea capaz de gestionar usuarios que se suscriban a distintos mensajes de su interés.

## Decision Drivers

* Se propone implementar la lógica de suscripción a eventos en el gestor de eventos ya existente.

## Considered Options

* ADR-07
* ADR-07.1

## Decision Outcome

Chosen option: "ADR-07", because La decisión se rechaza, ya que su uso no sería óptimo ya que tiende a ser monolítico. Por otro lado, optamos por usar el patrón pub-sus (ver ADR .7)
