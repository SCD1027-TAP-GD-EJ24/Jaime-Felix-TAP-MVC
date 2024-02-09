# Proyecto: Facturación MVC

Elaborar una aplicación de Facturación en entorno Windows usando la arquitectura MVC. La aplicación debe tener catálogo de Artículos, catálogo de Clientes y la opción de Ventas (Facturación)

## Diagrama de clases
[Editor en línea](https://mermaid.live/)
```mermaid
---
title: MVC
---
classDiagram
      direction LR
      class Principal
      class Modelo
      class Controlador
      class Vista
      Modelo -- Controlador
      Controlador -- Vista
```
[Referencia-Mermaid](https://mermaid.js.org/syntax/classDiagram.html)


## Comandos Git-Cambios y Actualizaciones

### Por cada cambio importante que haga, actualice su historia usando los comandos:
```
git add .
git commit -m "Descripción del cambio"
git push origin main
```
