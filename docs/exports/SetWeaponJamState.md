# SetWeaponJamState
Set the weapon jam state of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash
| `state`                | boolean | :material-checkbox-blank-circle: | `-` | The jam state

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())

    exports["utility_weapons"]:SetWeaponJamState(weapon, true)
    ```