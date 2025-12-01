```
winget configure --accept-configuration-agreements https://github.com/Team-4536/Onboarding/raw/refs/heads/main/winget/programming.winget
```

*Open a new shell to pick up System Path changes*

```
nipkg feed-add --name=ni-frc-2025-game-tools-2025-released https://download.ni.com/support/nipkg/products/ni-f/ni-frc-2025-game-tools/25.0/released
nipkg feed-add --name=ni-frc-2025-game-tools-2025-released-critical  https://download.ni.com/support/nipkg/products/ni-f/ni-frc-2025-game-tools/25.0/released-critical
nipkg feed-update

nipkg install --accept-eulas -y ni-frc-2025-game-tools
```
