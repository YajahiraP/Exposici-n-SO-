## Jerarquia de Memoria 

Cada nivel de la jerarquía tiene características específicas que afectan la velocidad, capacidad y costo. La idea principal es aprovechar las ventajas de diferentes tipos de memoria para optimizar el rendimiento general del sistema. La jerarquía de memoria típicamente se organiza en varios niveles, desde los más rápidos y costosos hasta los más lentos y económicos.

#### Registro:

Los registros son la forma más rápida y más cercana a la unidad de procesamiento de la CPU. Cada CPU tiene un conjunto de registros internos para almacenar datos temporalmente durante las operaciones el uso es almacenar temporalmente los datos para la ejecución inmediata de instrucciones.

#### Memoria Caché:

La caché es una memoria de acceso rápido que almacena datos e instrucciones utilizadas con frecuencia. Hay varios niveles de caché (L1, L2, L3) con L1 siendo la más cercana a la CPU y más rápida.
Uso: Almacenamiento temporal de datos para mejorar la velocidad de acceso a la memoria principal.

#### Memoria Principal (RAM - Random Access Memory):

La memoria principal es más grande que la caché y más lenta, pero sigue siendo más rápida que el almacenamiento a largo plazo. Es volátil, lo que significa que pierde su contenido cuando se apaga la computadora.
Uso: Almacenamiento temporal de datos y programas en ejecución.

#### Memoria Virtual:

Es la parte del disco duro o SSD que se utiliza como extensión de la memoria principal. Se utiliza para almacenar datos cuando la RAM está llena.
Uso: Proporciona más espacio de almacenamiento temporal cuando la memoria principal está llena, pero a un costo de velocidad más lento.

#### Almacenamiento Secundario (Disco Duro, SSD, etc.):

Almacenamiento no volátil utilizado para almacenar datos de forma permanente, incluso cuando la computadora está apagada.
Uso: Almacenamiento de datos a largo plazo, incluyendo el sistema operativo, aplicaciones y archivos del usuario.