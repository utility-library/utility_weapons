# IsWeaponJammed
Return the jammed state of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash

??? success "Returns"
    | Data Type                            | Description
    | ------------------------------------ |-------------
    | boolean | The jammed state of the weapon

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())
    
    local jammed = exports["utility_weapons"]:IsWeaponJammed(weapon)
    ```