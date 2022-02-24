# SetWeaponFireMode
Set the weapon fire mode of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash
| `mode`                | number | :material-checkbox-blank-circle: | `-` | The weapon firemode (1 = single, 2 = burst, 3 = auto, 4 = safety)

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())

    exports["utility_weapons"]:SetWeaponFireMode(weapon, 1)
    ```