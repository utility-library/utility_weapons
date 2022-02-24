# AddWeaponExperience
Add experience to a weapon.

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash
| `experience`            | number | :material-checkbox-blank-circle: | `-` | The experience

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())

    exports["utility_weapons"]:AddWeaponExperience(weapon, 100)
    ```