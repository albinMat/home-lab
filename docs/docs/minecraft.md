# Minecraft Server

## Environment

- Ubuntu Server
- Java 21
- Minecraft Java Edition 1.21.1
- Fabric mod loader

## Server Design

I configured separate Minecraft server directories so different worlds and
configurations can be managed independently.

One server is intended as a stable server while another is used for
modded multiplayer.

## Modded Server

The modded server uses Fabric and a matching Modrinth client profile.

I learned that some mods must exist on both the server and client while
others are client-side only.

## Networking

The Minecraft service listens on a specific TCP port.

I used PowerShell's `Test-NetConnection` to verify whether the server port
was reachable before troubleshooting Minecraft itself.

## Remote Access

I configured a tunnel so approved players outside my home network can
connect without being on the local LAN.

## What I Learned

- Client/server architecture
- TCP ports
- Java server processes
- Mod dependencies
- Server configuration files
- Local vs remote network access
- Basic troubleshooting methodology
