# RemoveWeaponExperience
Remove experience from a weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash
| `experience`            | number | :material-checkbox-blank-circle: | `-` | The experience

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())

    exports["utility_weapons"]:RemoveWeaponExperience(weapon, 100)
    ```