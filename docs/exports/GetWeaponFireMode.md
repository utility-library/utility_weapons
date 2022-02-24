# GetWeaponFireMode
Return the fire mode of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash

??? success "Returns"
    | Data Type                            | Description
    | ------------------------------------ |-------------
    | number | The fire mode of the weapon (1 = single, 2 = burst, 3 = auto, 4 = safety)

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())

    local fireMode = exports["utility_weapons"]:GetWeaponFireMode(weapon)
    ```