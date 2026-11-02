# Dunas Launcher (TizenBrew)

Lanzador para Samsung Tizen: saludo, tiempo (Open-Meteo), reloj, fondo aleatorio y
fila de apps: Prime Video, Netflix, Disney+, Plex y DIRECTV GO.

## Instalar
1. Sube esta carpeta a un repositorio de GitHub (p. ej. `tuusuario/dunas-launcher`).
2. En la TV abre TizenBrew > Module Manager > añade `gh/tuusuario/dunas-launcher`.
3. Abre el modulo desde la lista de TizenBrew.

## Mando
- Izq/Der moverse, OK abrir, Abajo barra inferior, Back salir
- Barra: Samsung (salir al Smart Hub), Ordenar (mueve con Izq/Der, OK guarda), Fondo (otro fondo al azar)

## Fondo aleatorio
- BG_MODE = "online": foto al azar de picsum.photos.
- BG_MODE = "local": pon tus fotos en app/fondos/ y listalas en LOCAL_BGS.

## IDs de apps (appId)
Prime, Netflix, Disney+ vienen con ID habitual. Plex y DIRECTV GO estan vacios:
busca su ID real con Tizen Studio: `sdb shell 0 applist` (con la app instalada en la TV).
