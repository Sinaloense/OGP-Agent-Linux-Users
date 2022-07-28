# OGP-Agent-Linux-Users
Basado y probado con https://github.com/OpenGamePanel/OGP-Agent-Linux/commit/2fe49c642b8c7c59e94eee2f4e1495fafd45aad8

# Creación de usuarios manualmente
Falta automatizar la creación automatica del usuario al crear el servidor y asignación de permisos de archivos.
## Agregar usuarios linux manualmente
        useradd -d /home/ogp_agent/servers/servers-cstrike/counter-strike/1 OGP_HOME_000000001
## Cambiar dueño y grupo de archivos manualmente
    chown -R OGP_HOME_000000001:ogp_agent /home/ogp_agent/servers/servers-cstrike/counter-strike/1