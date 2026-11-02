# Introducción para el plugin PunteoCuentasPlus

PunteoCuentasPlus amplía el punteo de subcuentas que incluye FacturaScripts. El punteo permite marcar como comprobados los movimientos de una subcuenta a medida que se revisan, y este plugin añade herramientas para controlar ese proceso y para corregir movimientos registrados en una subcuenta equivocada.

## 🧩 Qué incluye FacturaScripts y qué añade el plugin

FacturaScripts ya permite, desde la ficha de una subcuenta, marcar sus movimientos como comprobados o no comprobados y distinguirlos por color en la lista. Sobre esa base, el plugin añade:

- **Totales de comprobados y no comprobados**: dos indicadores en la ficha de la subcuenta con el saldo de los movimientos comprobados y el de los pendientes.
- **Filtro por estado**: muestra solo los movimientos comprobados, solo los pendientes o todos.
- **Impresión de la lista de movimientos**: activa el botón Imprimir en la lista de movimientos de la subcuenta.
- **Cambio de subcuenta**: traslada los movimientos seleccionados a otra subcuenta del mismo ejercicio.
- **Archivos adjuntos**: permite guardar en la ficha de la subcuenta documentos como extractos o justificantes.

## 📋 Requisitos

- FacturaScripts 2026.6 o superior.
- PHP 8.1 o superior.

## ⚖️ Conciliación de cuentas

El punteo sirve para conciliar a mano una subcuenta, por ejemplo la de un banco o la de caja, comparando sus movimientos con el extracto o con el arqueo.

Flujo de trabajo sugerido:

- Abre la ficha de la subcuenta y revisa su lista de movimientos, usando el filtro **No comprobado** para ver solo lo pendiente. Se explica en [Gestión de movimientos en subcuentas](https://facturascripts.com/publicaciones/gestion-de-movimientos-en-subcuentas).
- Marca como comprobados los movimientos que coinciden con el extracto.
- Consulta los totales de comprobados y no comprobados. Ten en cuenta que suman todos los movimientos de la subcuenta, sin tener en cuenta los filtros aplicados a la lista.
- Si algún movimiento está en una subcuenta que no le corresponde, trasládalo con el [cambio de subcuenta](https://facturascripts.com/publicaciones/cambio-de-subcuenta).
- Si quieres conservar el extracto o el documento con el que has conciliado, adjúntalo a la subcuenta como se indica en [Gestión de archivos adjuntos](https://facturascripts.com/publicaciones/gestion-de-archivos-adjuntos).
