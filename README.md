# Yoda Runners provider

Supplies one Ubuntu machine to the existing Runners fleet. Fleet Provider owns replenishment; the target is `MACHINE_COUNT=1`.

Machine and capacity workflows use the shared agent from [hetp4401/runner](https://github.com/hetp4401/runner). The fleet join token is stored only as the `JOIN_TOKEN` Actions secret.
