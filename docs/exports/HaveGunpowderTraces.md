# HaveGunpowderTraces
Return true if the player has a gunpowder trace.

| Argument | Data Type | Nedeed                                   | Default | Description             |
|----------|-----------|------------------------------------------|---------|-------------------------|
| `source` | number    | :material-checkbox-blank-circle-outline: | `-`     | Only in the server side |

??? info
    This export can be called also from the server-side.

---
??? example
    The following example shows how to use the export in the client-side, for the server side you need to use the `source` argument.
    ```    
    exports["utility_weapons"]:HaveGunpowderTraces()
    ```