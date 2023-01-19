# ADR-02.Arquitectura dirigida por eventos para notificaciones

* Status: accepted
* Deciders: ASS,ASC
* Date: 2022-11-06

Technical Story: Architecture Decision

## Context and Problem Statement

Se necesita un sistema de gestión y envío de notificaciones, que reaccione a las modificaciones detectadas por los sensores, enviando las señales pertinentes.

## Decision Drivers

* Se necesita una arquitectura con emisores de eventos, consumidores y canales para transmitir los eventos, donde los consumidores son responsables de reaccionar a los eventos.

## Considered Options

* ADR-02
* ADR-02.1

## Decision Outcome

Chosen option: "ADR-02", because Se ha escogido esta opción porque es la más conveniente al esquema presentado en el problema, permitiendo detectar y gestionar cambios en el entorno mediante mensajes de eventos.
