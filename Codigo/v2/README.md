En esta carpeta se halla el código necesario (librerías y sketch) para usar con la versión 2 del KiloMux Shield (la que parece de verdad).

El código Kilo_muxShield_v2 incorpora grandes mejoras con respecto a la versión anterior, entre ellas la posibilidad de usar hasta 5 páginas o bancos mediante el uso y la especificación de algunos botones como shifters. Esto permite, por ejemplo, si se usan 16 potenciómetros, controlar hasta 80 parámetros de un DAW. El número de shifters es a su vez expandible.

Otra mejora en el código es el mapeo dinámico de los componentes, mediante tablas, en lugar de los defines que usaba la versión 1. Esto simplifico y redujo mucho el código para lograr la correspondencia entre el identificador del canal del multiplexor, y el identificador MIDI que se requiere.

La "KiloMux lib" se encuentra en desarrollo, así como la carpeta "func RGB".