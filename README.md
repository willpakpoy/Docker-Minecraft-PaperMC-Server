# Docker-Minecraft-PaperMC-Server

Starts a Minecraft PaperMC server 1.14.4 or 1.13.2

Tutorial (german) https://marc.tv/anleitung-stabiler-minecraft-server-synology-nas/

On GitHub https://github.com/mtoensing/Docker-Minecraft-PaperMC-Server

This server is live here: https://mc.marc.tv

Based on the the work of [Felix Klauke](https://github.com/FelixKlauke/paperspigot-docker) Thanks for your help!

## Volume

Local path: /your_local_folder
Mount path: /data

## Port Settings

Local Port: 25565 TCP
Container Port: 25565 TCP

Local Port: 25565 UDP
Container Port: 25565 UDP

## Environment variable

MEMORYSIZE = 1G 

Not more than 70% of your RAM for your Container! This is important! This is the RAM your Minecraft Server will use within the container WITHOUT the operating system.