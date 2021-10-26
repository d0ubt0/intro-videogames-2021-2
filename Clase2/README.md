# Clase #2

## Taller

### Fecha de entrega
> Miércoles 27 de Octubre, 11:59 pm (media noche).

  - Cuál es la diferencia entre `Input.GetAxis` y `Input.GetAxisRaw`?
  - R/ Input.GetAxis toma valores decimales hasta -1 o 1, en cambio, GetAxisRaw comienza directamente desde 1 o -1.
  - Cuál se deberia usar? (Pregunta capciosa...).
  - R/Depende de la situacion, en algunas ocasion se necesita un movimiento mas suavizado perfecto para los mandos de consolas y en otras ocasiones un movimiento mas directo.
  - Qué hace `input.magnitude`? Por qué es util?
  - R/ Magnitude evalua el valor de la variable input.En este caso es util para determinar cuando se presiona una tecla de movimiento, si es mayor que 0, alguien presiono las teclas y el objeto se empieza a mover, y si el valor es 0, la velocidad empieza a desacelerar hasta llegar a 0.
  - Que significa normalizar un Vector (`Normalize`)? Por qué es util cuando se trabaja con movimiento?
  - R/ Convierte la magnitud del vector en 1, para no tener valores decimales innecesarios.
- **Reto (Opcional):** Implementar una mécanica de dash en base al código dado.



