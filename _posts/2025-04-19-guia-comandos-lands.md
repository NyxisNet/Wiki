---
layout: post
title: Guía de Comandos Lands
description: Guía detallada de comandos Lands para empezar en el servidor.
date: 2025-04-19 12:31 -0600
authors: [carlosvg7]
---
# Guía Avanzada de Comandos para el Plugin **Lands**

Esta guía proporciona una visión detallada de los comandos disponibles para la gestión de terrenos **Lands**, incluyendo administración de zonas, economía, comunicación y guerra (si está activado en el servidor).

---

## Comandos Generales para Jugadores

| Comando                        | Descripción                                                              |
| ------------------------------ | ------------------------------------------------------------------------ |
| `/lands rename <nuevo_nombre>` | Cambia el nombre de tu land.                                             |
| `/lands leave`                 | Abandona la land actual.                                                 |
| `/lands spawn <land>`          | Teletranspórtate al punto de aparición de otra land (si está permitido). |
| `/lands setspawn`              | Define el punto de aparición de tu land.                                 |
| `/lands trust <jugador> -a`    | Otorga permisos globales a un jugador en toda la land.                   |
| `/lands claim auto`            | Reclama automáticamente varios chunks alrededor tuyo.                    |
| `/lands claim fill`            | Reclama los chunks dentro del perímetro que rodea tus tierras.           |

---

## Gestión de Zonas y Subáreas

Las lands pueden dividirse en **áreas** o **subzonas**, permitiendo una administración más precisa.

| Comando                         | Descripción                                           |
| ------------------------------- | ----------------------------------------------------- |
| `/lands selection`              | Inicia el modo de selección (similar a WorldEdit).    |
| `/lands assignarea <nombre>`    | Crea una nueva subzona dentro de la selección actual. |
| `/lands deletearea <nombre>`    | Elimina una subzona específica.                       |
| `/lands trust <jugador> <área>` | Otorga permisos a un jugador solo en una subzona.     |
| `/lands area menu`              | Abre el menú gráfico para administrar subzonas.       |

---

## Sistema de Guerra (Opcional)

Estos comandos estarán disponibles solo si el administrador del servidor habilita el sistema de guerra.

| Comando                     | Descripción                              |
| --------------------------- | ---------------------------------------- |
| `/lands war declare <land>` | Declara la guerra a otra land.           |
| `/lands war surrender`      | Te rindes en una guerra en curso.        |
| `/lands war info`           | Consulta el estado actual de una guerra. |
| `/lands war gui`            | Abre el menú visual de guerra.           |

> ⚠️ *El sistema de guerra puede estar deshabilitado por el administrador del servidor.*

---

## Comandos de Chat y Comunicación

| Comando                        | Descripción                                            |
| ------------------------------ | ------------------------------------------------------ |
| `/lands chat`                  | Cambia al chat exclusivo de tu land.                   |
| `/lands chat <Nombre de land>` | Alterna entre el chat de land y el global.             |
| `/lands nation chat`           | Envía mensajes a toda tu nación (si perteneces a una). |

---

## Configuraciones y Protección

| Comando  | Descripción                                    |
| -------- | ---------------------------------------------- |
| `/lands` | Muestra todas las configuraciones disponibles. |

| `/lands deny <jugador>`             | Niega la entrada de un jugador (sin banearlo).                 |


---

## Banco y Economía

| Comando                      | Descripción                                         |
| ---------------------------- | --------------------------------------------------- |
| `/lands balance`             | Consulta el saldo actual del banco de la land.      |
| `/lands deposit <cantidad>`  | Deposita dinero en el banco de la land.             |
| `/lands withdraw <cantidad>` | Retira dinero del banco.                            |
| `/lands taxes`               | Consulta los impuestos que debes pagar por tu land. |

---

## Otros Comandos Útiles

| Comando                         | Descripción                               |
| ------------------------------- | ----------------------------------------- |
| `/lands invites`                | Visualiza y acepta invitaciones a lands.  |
| `/lands setdescription <texto>` | Agrega una descripción pública a tu land. |

| `/lands list`            | Muestra una lista de todos las lands en el servidor.            |


---

## Acceso a Todos los Comandos

Para visualizar todos los comandos disponibles en el servidor, puedes utilizar:

```bash
/lands help 1
/lands help 2
/lands help 3
...
```

> También puedes escribir `/lands` y presionar **TAB** para acceder a la función de autocompletado de comandos.
{: .prompt-tip }

---
