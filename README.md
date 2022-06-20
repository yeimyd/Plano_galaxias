# Plano galaxias

Archivos iniciales:
Galaxies.dat------------------> Archivo con todas las galaxias con masa diferente de 0 de la simulación TNG300-1
GalaxiesCentral.dat-----------> Archivo con todas las galaxias centrales con masa diferente de 0 de la simulación TNG300-1
GalaxiesSat.dat---------------> Archivo con todas las galaxias satelite con masa diferente de 0 de la simulación TNG300-1

Columnas: 

Las columnas y unidades de cada archivo son:

# IDH,IDG,Mass,x,y,z,Vx,Vy,Vz,VelDisp,VelMax

IDH: Id de halo que contiene a la galaxia.

ID:Id de la galaxia en la base de datos.

Mass:Masa de la galaxia en $10^{10}𝑀_\odot/ℎ$ (sum of masses of all particles/cells (split by type) within twice the stellar half mass radius.).

x,y,z: Posición x,y,z de cada galaxia en $𝑐𝑘𝑝𝑐/ℎ$.

Vx,Vy,Vz: Velocidades x,y,z de cada galaxia en $km/s$ (Peculiar velocity of the group, computed as the sum of the mass weighted velocities of all particles/cells in this group, of all types. No unit conversion is needed).

VelDisp: One-dimensional velocity dispersion of all the member particles/cells (the 3D dispersion divided by $\sqrt{3}$) en $km/s$.

SubhaloVmax: Maximum value of the spherically-averaged rotation curve en $km/s$.


