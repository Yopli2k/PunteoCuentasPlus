# Cambio de subcuenta

Permite trasladar uno o varios movimientos de una subcuenta a otra del mismo ejercicio, por ejemplo cuando se registraron en una subcuenta equivocada.

## 🔄 Pasos para cambiar la subcuenta

1. Abre la ficha de la subcuenta donde están los movimientos y, en la lista de movimientos de la pestaña **Asientos**, marca la casilla de los que quieres trasladar.
2. Pulsa el botón rojo **Cambiar**.
3. En la ventana **Cambio de Subcuenta**, escribe en el campo **Nueva Subcuenta** el código o la descripción y elige la subcuenta en la lista que aparece.
4. Pulsa **Aceptar**.

Los movimientos trasladados dejan de aparecer en la lista, porque ya pertenecen a la nueva subcuenta.

## ⚠️ Antes de confirmar

- El cambio se aplica al momento y no se puede cancelar. Para devolver los movimientos a su subcuenta original hay que repetir el proceso desde la nueva subcuenta.
- También se cambian los movimientos de asientos generados desde facturas u otros documentos, que normalmente no se pueden modificar a mano. El asiento se desbloquea solo para hacer el cambio y se vuelve a bloquear después. El documento de origen no se modifica.
- Solo se trasladan los movimientos seleccionados que pertenecen a la subcuenta que estás consultando.

## 🚫 Qué impide el cambio

- **Permisos**: hace falta permiso de modificación en la ficha de subcuentas. Sin él se muestra un aviso y no se cambia nada.
- **Datos incompletos**: hay que seleccionar al menos un movimiento e indicar la nueva subcuenta.
- **Subcuenta inexistente**: la nueva subcuenta tiene que existir en el mismo ejercicio que la subcuenta original. Si no existe, ese movimiento se salta con un aviso y el resto se trasladan igualmente, así que conviene darla de alta antes.
- **Ejercicio cerrado o periodo bloqueado**: no se pueden cambiar movimientos de un ejercicio cerrado ni de asientos con fecha dentro de una regularización de impuestos bloqueada.
