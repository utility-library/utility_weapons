# GetWeaponExperience
Return the experience of the specified weapon

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash

??? success "Returns"
    | Data Type                            | Description
    | ------------------------------------ |-------------
    | number | The experience that the player has with the weapon

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())
    local experience = exports["utility_weapons"]:GetWeaponExperience(weapon)

    print(experience)
    ```