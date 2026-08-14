Nota: Cliente ya registrado
```mermaid
flowchart TD
    A([Inicio]) --> B[Se pide al cliente id y password]
    B --> C{Datos validos?}
    C -->|Si| D[Acceso exitoso]
    C -->|No| E[Mostrar error y volver]
    E --> B
    D --> H([Fin])
```