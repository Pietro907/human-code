## 10. Attraversare la strada
 Look left / look right
<!-- Semafori, rotonde e precedenze… al test per la patente, la domanda sugli incroci manda sempre un po’ in confusione! Per stavolta ci concentriamo solamente sugli step da fare per attraversare la strada, sapendo che ogni passo deve essere ben misurato altrimenti potrebbe costarci caro!
 -->

Contesto: Sono appena uscito dalla stazione del treno e devo andare in ufficio. Per arrivarci devo attraversare una strada statale.

Guardo davanti a me e girando la testa da destra verso sinistra
    - controllo se ci sono una serie di oggetti ['semaforo','semaforo-pedonale','incroci','rotonde','corsie']
? Ci sono incroci
    - si
    - no
? Ci sono corsie
    - una
        * strada piccola
    - più di una
        *strada grande
? C'è una rotonda nelle vicinanze
    - si
        * controllo prima di attraversa
    - no

Verifico se è presente un semaforo
    - se è un semaforo pedonale:
        * aspetto che si accenda la luce colorata
            - se è rossa
                * aspetto
            - se è arancione
                - valuto
                    * se aspettare
                    * se attraversare la strada di corsa
            - se è verde
                * attraverso
                    - se c'è un incrocio
                        * valuto
                            - se aspettare
                            - se attraversare
        * attraverso sulle strisce pedonali
    - se è un semaforo:
        * controllo se c'è un semaforo pedonale intorno a me
        * aspetto che si accenda la luce colorata rossa
        * controllo che le eventuali macchine per strada siano ferme al semaforo
Mi posiziono in punta al marciapiede
Guardo
    - controllo entrambe le corsie della strada
        - se le macchine sono ferme
            * continuo attraverso
        - se le macchine sono in movimento
            * mi fermo ed aspetto
                - che il passaggio sia libero per attraversare
                - che le macchine vedendo si fermino e mi lasciano passare
Attraverso
Salgo sul marciapiede
Vado via

