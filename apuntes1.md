### Apuntes 2 avaliación

## Particións
# MBR Master Boot Record (antigo)
Disco divide en sectores de 512B
O primeiro sector denominase MBR
(Para discos analóxicos, non SSD)

2 tipos de partición en MBR: (Max 4 en total Extendidas 1 en total) 
Primarias: 
Extendidas: sirve para añadir particiones lóxicas

# Sistema particionado GPT
Se crean hasta 128 particiones
Ya o hay ni logicas ni primarias
Discos con capacidad superior a 2 TB

Tamen existe MBR herdado
# Memoria Swap
Memoria de intercambio
Utiliza parte del disco para intercambiar datos con la RAM
(pseudoRAM)

En windows se utiliza otra forma de memoria auxiliar como swapfile.sys o hiberfile.sys

## RAID
Aumenta la intrgridad de datos en los discos
Prevención frente a errores

# RAID 0
 Repartir la información entre dos discos
 No proporciona seguridad. Solo rendimiento.
 Si cae uno de los discos pierdes toda a información

 # RAID 1
 Duplica la información. Pierdo el 50% de la capacidad de almacenamiento

 # RAID 3
 Algoritmos de Paridade. 3 discos, permite la caída de uno de ellos.

 # RAID 5
 Paridade Distribuída. Se recupera toda la información

 # RAID 6
  Doble Paridad. Soporta 2 caídas simultáneas de discos
  Mínimo 4 Discos

  # RAID 1+0
  Literal RAID 1 + RAID 0

  # RAID 0+1
  Literal RAID 0 + RAID 1

  De la misma forma existen RAID 50 y RAID 60

  # JBOD
  Juntar todos los discos en un volumen único.
  Concepto contrario a partición
