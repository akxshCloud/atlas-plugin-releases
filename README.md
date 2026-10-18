# Atlas plugin for Jellyfin

The server side of the Atlas app. It keeps your server's service connections (Seerr, Kavita, Sonarr,
Radarr, Prowlarr, qBittorrent) with their keys on the server, and decides on the server what each
profile can use. Needs Jellyfin 10.11.

## Install

1. Jellyfin → Dashboard → Plugins → Manage Repositories → New Repository.
2. Repository Name: `Atlas`
   Repository URL: `https://raw.githubusercontent.com/akxshCloud/atlas-plugin-releases/main/manifest.json`
3. Back in Plugins, open **Atlas** and press Install.
4. Restart Jellyfin.

This repository holds only the install link and the releases.
