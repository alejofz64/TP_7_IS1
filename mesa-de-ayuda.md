# Sistema de mesa de ayuda

# Requerimiento

El área de soporte atiende reclamos de los clientes y se asegura que los mismos son
gestionados por el área que necesite estar involucrada en su solución hasta lograr el
cierre de los mismos.
El reclamo del cliente empieza con el mismo ingresando a la página web y generando
un reclamo al que se denomina “ticket” donde especifica sus datos de contacto y la
naturaleza del problema o petitorio que realiza, luego de algunas validaciones
estándar realizadas por la herramienta el mismo es almacenado otorgándosele al
cliente un número de ticket que deberá utilizar para cualquier seguimiento ulterior del
mismo.
Los tickets abiertos son analizados por un analista de soporte de primer nivel
perteneciente al área de soporte quien revisa si el mismo se corresponde con algún
problema repetitivo al cual se conoce la solución o que la naturaleza del reclamo
permite su solución mediante acciones que el analista pueda realizar.
De poder abordar el problema se actualiza la información en el ticket y se informa al
cliente, en caso que el cliente tenga alguna consulta ulterior se repite el ciclo de
responder.
Cuando el analista de soporte de primer nivel concluye que no puede hacer nada mas,
da por contestada la consulta y cierra el ticket; lo mismo hace si pasan 24 horas sin
contacto ulterior del cliente.
Cuando el analista de soporte de primer nivel no puede resolver el problema termina el
proceso informándole al cliente que su problema no puede ser resuelto.

---

# Diagramas de Actividad
- [Acceso Nuevo Cliente](01-Actividad_AccesoNuevoCliente.md)
- [Cambio de Password](02-Actividad_CambioPassword.md)
- [Ingreso Nuevo Cliente](03-Actividad_IngresoNuevoCliente.md)
- [Nuevo Ticket](04-DiagramaActividad_NuevoTicket.md)
- [Registro Nuevo Cliente](05-Actividad_RegistroNuevoCliente.md)

---

# Diagrama de Estado
- [Estado Activo-Registrado de Cliente](06-Estado_ActivoRegistradoCliente.md)
- [Estados de Ticket](07-Estado_EstadosTicket.md)

---

# Diagrama de Secuencia
- [AbrirNuevoTicket](08-Secuencia_IS1_AbrirNuevoTicket.md)
- [AccesoCliente](09-Secuencia_IS1_AccesoCliente.md)
- [ActualizacionDeDatosDeCliente](10-Secuencia_IS1_ActualizacionDeDatosDeCliente.md)
- [ActualizarTicket](11-Secuencia_IS1_ActualizarTicket.md)
- [CambioDePassword](12-Secuencia_IS1_CambioDePassword.md)
- [ConsultarTiketsExistentes](13-Secuencia_IS1_ConsultarTiketsExistentes.md)
- [IngresoNuevoCliente](14-Secuencia_IngresoNuevoCliente.md)
- [Secuencia_RegistroNuevoCliente](15-Secuencia_RegistroNuevoCliente.md)