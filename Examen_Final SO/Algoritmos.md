# Tipos de Algoritmos

### Algoritmo First-come First-Served

El algoritmo "First Come First Served" (FCFS) es uno de los algoritmos de planificación de procesos más simples y directos. Funciona de la siguiente manera:

#### Llegada de Procesos:

Cuando un proceso llega al sistema, se coloca en la cola de espera.
La cola de espera sigue el orden de llegada de los procesos al sistema.

#### Ejecución:

El proceso que está en la parte frontal de la cola de espera es seleccionado para ejecutarse.
Este proceso se ejecuta hasta que termina su tiempo asignado (quantum) o hasta que completa su ejecución.

#### Siguiente Proceso:

Una vez que un proceso ha terminado de ejecutarse, el siguiente proceso en la cola de espera es seleccionado para ejecutarse.
Repetición:

Este proceso se repite continuamente, seleccionando y ejecutando los procesos en el orden en que llegaron al sistema.

### Algoritmo de SJF

El algoritmo SJF (Shortest Job First), también conocido como "Shortest Job Next" o "SRTF" (Shortest Remaining Time First), es un algoritmo de planificación de procesos que selecciona el proceso más corto disponible para ejecutarse a continuación. El objetivo principal es minimizar el tiempo de espera total y mejorar la eficiencia del sistema.

#### Llegada de Procesos:

Cuando un nuevo proceso llega al sistema, se agrega a la cola de procesos listos.

#### Selección del Proceso:

El algoritmo selecciona el proceso de la cola de procesos listos que tiene el tiempo de ejecución más corto. Este proceso se ejecutará a continuación.

#### Ejecución del Proceso:

El proceso seleccionado se ejecuta hasta que se completa su tiempo de ejecución o hasta que es interrumpido por un proceso con un tiempo de ejecución más corto que llega mientras está en ejecución.

#### Llegada de Nuevos Procesos:

Si llega un nuevo proceso mientras otro está en ejecución, se compara el tiempo de ejecución del nuevo proceso con el tiempo restante del proceso en ejecución. Si el nuevo proceso tiene un tiempo de ejecución más corto, se interrumpe el proceso actual y se ejecuta el nuevo.

#### Repetición:

Este proceso de selección y ejecución se repite hasta que todos los procesos hayan sido atendidos.

### Algoritmo de Round Robin 

El algoritmo Round Robin (RR) es un algoritmo de planificación de procesos diseñado para sistemas de tiempo compartido, donde varios procesos compiten por el tiempo de CPU. Es un enfoque simple y equitativo que asigna un pequeño intervalo de tiempo, conocido como "quantum" o "ciclo de tiempo", a cada proceso en turno. El algoritmo funciona de la siguiente manera:

#### Asignación de Quantum:

Se asigna un quantum de tiempo a cada proceso en la cola de procesos listos.

#### Ejecución de Proceso:

El proceso actual en ejecución tiene permitido ejecutarse durante el quantum asignado.

#### Interrupción por Quantum Agotado:

Cuando se agota el quantum asignado a un proceso, este se interrumpe, y se coloca nuevamente al final de la cola de procesos listos.

#### Selección del Siguiente Proceso:

Se selecciona el siguiente proceso en la cola de procesos listos para ejecutarse. Este proceso recibe un nuevo quantum y comienza su ejecución.

#### Repetición:

Este proceso se repite continuamente. Cada proceso obtiene la oportunidad de ejecutarse durante un quantum antes de pasar al siguiente proceso en la cola.




