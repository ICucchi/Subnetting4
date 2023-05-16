# Subnetting4
Creare il piano di indirizzamento per una rete così composta:
- la rete principale è la 172.130.20.0/24
- si vuole fare subnetting in modo da ottenere 4 sottoreti della stessa dimensione

- 1 router con 4 porte
- 8 PC
- 4 switch
- Ciascuna sottorete ha 1 switch e 2 PC, il router permette la comunicazione tra le 4 sottoreti

Nella configurazione della rete è importante inserire gli indirizzi ip in maniera corretta sapendo che il primo ip di una sottorete è l'indirizzo di rete mentre l'ulitmo è riservato brodcast, quindi saranno ip che non potranno essere utilizzati.
Avendo 4 sottoreti la subnet mask è 255.255.255.192 mentre nel caso avessimo avuto due sottoreti sarebbe stato 255.255.255.128, bisogna inserire il gateway giusto in base alla sottorete di appartenenza.
