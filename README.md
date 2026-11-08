# VeloceX

**Beyond Minecraft.** An independent launcher for Minecraft: Java Edition on Windows and Linux, written in Rust.

## What it does

- Installs every Java Edition version from Mojang's official version list, with the matching Java runtime, every file verified.
- Fabric, Quilt, Forge and NeoForge.
- Independent instances with backups.
- Modpacks, mods, resource packs and shaders from Modrinth and CurseForge, with dependency checks.
- A mod manager that finds conflicts and mods for the wrong version or loader.
- Diagnostics for crashes – everything stays on the player's computer.

## Sign-in and security

- Sign-in uses Microsoft's official flow in the player's own browser (OAuth with PKCE, personal Microsoft accounts). VeloceX never sees passwords.
- Game ownership is verified before the game can start. There is no offline or cracked mode.
- Only the Microsoft refresh token is stored, in the operating system's credential store.
- VeloceX uses its own Azure application ID and does not borrow another launcher's.

## Status

Version 0.1.0 is a preview in active development. Minecraft sign-in is waiting for Mojang's approval of VeloceX's application ID.

VeloceX is an independent project. It is not affiliated with or endorsed by Mojang Studios or Microsoft.
