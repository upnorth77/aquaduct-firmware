# Aquaduct Firmware Releases

Official binary firmware releases and user documentation for the Aquaduct
aquarium light controller.

> **Beta hardware:** Aquaduct Rev A is prototype hardware. Test updates while
> you can observe the controller and aquarium light. Do not install an untested
> controller over livestock.

## Download

Open the [Releases page](../../releases) and select the newest appropriate
version. Download:

- `aquaduct-firmware-<version>.bin` — controller firmware
- `Aquaduct-Quick-Start-Guide-<version>.pdf` — setup guide
- `Aquaduct-User-Manual-<version>.pdf` — complete manual
- `SHA256SUMS.txt` — file-integrity checksums

## Update an existing controller

1. Download the `.bin` file from the selected release.
2. Back up the controller from **Settings > Maintenance**.
3. Open **Settings > Firmware Update**.
4. Select the downloaded `.bin` file and start the update.
5. Keep the page open until the controller restarts.
6. Confirm the firmware version, time, selected schedule, group role, and actual
   light output.

Upload only the release's `aquaduct-firmware-<version>.bin` through the web
interface. Do not upload a bootloader, partition table, or merged factory image.

## Rev A power safety

Rev A uses **one power source at a time**. Disconnect the aquarium light from
Aquaduct before connecting a computer, charger, or programmer to the service
USB port. Never power Rev A from the light and service USB simultaneously.

Mount USB openings downward, provide cable strain relief, and use drip loops.

## Source availability

This repository distributes compiled firmware and documentation. Firmware
source files and build tooling are not included.
