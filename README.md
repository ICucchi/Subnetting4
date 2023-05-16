# Subnetting4
Creare il piano di indirizzamento per una rete così composta:
- la rete principale è la 172.130.20.0/24
- si vuole fare subnetting in modo da ottenere 4 sottoreti della stessa dimensione

- 1 router con 4 porte
- 8 PC
- 4 switch
- Ciascuna sottorete ha 1 switch e 2 PC, il router permette la comunicazione tra le 4 sottoreti

Il subnetting è importante perchè migliora la gestione delle risorse: Il subnetting consente di suddividere una rete IP in sotto-reti più piccole, permette di assegnare indirizzi IP in modo più efficiente, evitando sprechi di indirizzi IP e consente di ottimizzare l'utilizzo della larghezza di banda di rete.

Aumentano le prestazioni di rete perchè suddividere una rete in subnet più piccole può ridurre il traffico di rete e migliorare le prestazioni complessive della rete, avviene perché i dispositivi possono comunicare direttamente all'interno della stessa subnet senza dover passare attraverso router o altri dispositivi di rete.

Migliora la sicurezza di rete: Il subnetting consente di creare segmenti di rete separati, ovvero subnet, che possono essere separati e isolati l'uno dall'altro. Ciò fornisce un livello di sicurezza aggiuntivo.

Supporto per la scalabilità: Quando la rete cresce e sono necessarie nuove subnet, è possibile aggiungere facilmente nuove subnet senza dover ridisegnare l'intera architettura di rete.

Migliora l'amministrazione di rete: Il subnetting semplifica l'amministrazione di rete, facilita la localizzazione e la risoluzione dei problemi di rete poiché il traffico di rete è suddiviso in segmenti più gestibili.
Nella configurazione della rete è importante inserire gli indirizzi ip in maniera corretta sapendo che il primo ip di una sottorete è l'indirizzo di rete mentre l'ulitmo è riservato brodcast, quindi saranno ip che non potranno essere utilizzati.
Avendo 4 sottoreti la subnet mask è 255.255.255.192 mentre nel caso avessimo avuto due sottoreti sarebbe stato 255.255.255.128, bisogna inserire il gateway giusto in base alla sottorete di appartenenza.
