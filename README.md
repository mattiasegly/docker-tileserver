# rpi-tileserver

Raspberry Pi Docker Container for MapTiler's TileServer GL Light (https://github.com/maptiler/tileserver-gl)

Multiarch build using balena's Raspberry Pi image and docker's official Debian image.<BR>
Running with tag :latest should work on all Raspberry Pi models and standard 32/64-bit hardware.

Run with:<BR>
docker run --rm -d \\\
-v $(pwd):/data \\\
-p 8080:8080 \\\
mattiasegly/rpi-tileserver:latest

I know nothing about code, so assume that everything here sets the world on fire.<BR>
Use at your own peril.

20201123
