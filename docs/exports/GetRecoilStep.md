# GetRecoilStep
Return the current recoil step of the specified weapon (every time the weapon is fired, the recoil step is increased), the recoil step can be setted in <span style="color: var(--md-accent-fg-color)">Config.Patterns</span>

| Argument              | Data Type                            | Nedeed                    | Default         | Description
| ----------------------| ------------------------------------ | ------------------------- |-----------------|-------------
| `weapon`                | number | :material-checkbox-blank-circle: | `-` | The weapon hash

??? success "Returns"
    | Data Type                            | Description
    | ------------------------------------ |-------------
    | number | The recoil step of the weapon

---
??? example
    ```
    local weapon = GetCurrentPedWeapon(PlayerPedId())
    
    local recoilStep = exports["utility_weapons"]:GetRecoilStep(weapon)
    ```