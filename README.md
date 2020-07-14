# Calibre - Docker mod for calibre-web

This mod adds the calibre binary to calibre-web (**x86-64 only**) for ebook conversions.

In calibre-web docker arguments, set an environment variable `DOCKER_MODS=linuxserver/calibre-web:calibre` to enable.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/calibre-web:calibre|linuxserver/mods:other-mod`
