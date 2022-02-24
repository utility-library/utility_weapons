# SetWeaponExperience
Set the weapon experience of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash
| `experience`            | number | :material-checkbox-blank-circle: | `-` | The experience

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())
    
    exports["utility_weapons"]:SetWeaponExperience(weapon, 100)
    ```