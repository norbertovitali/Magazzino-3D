# Magazzino FDM

Apri `magazzino-fdm.html` con un browser moderno (Edge, Chrome o Firefox). Non richiede installazione né connessione Internet.

## Funzioni

- Inserimento e modifica bobine: marca, materiale, colore, diametro, peso iniziale e residuo, costo, posizione, note e soglia riordino.
- Registrazione consumi con motivo e controllo della disponibilità.
- Registro di carichi, consumi, rettifiche e rimozioni.
- Ricerca, filtro materiale e filtro delle bobine da riordinare.
- Calcolo del filamento disponibile e del valore residuo proporzionale al peso.
- Backup JSON con ripristino e inventario CSV compatibile con Excel.

I pesi si riferiscono al solo filamento: sottrai la tara quando pesi una bobina. Una bobina è da riordinare quando il residuo è minore o uguale alla soglia.

## Conservazione dei dati

I dati risiedono nel localStorage del browser. Usa sempre lo stesso browser e percorso del file. La navigazione privata, la cancellazione dei dati del browser o lo spostamento del file possono rendere l'inventario indisponibile. Esporta regolarmente un backup JSON e conservalo separatamente. Il ripristino sostituisce l'inventario e il registro dopo conferma.

Questa versione è per un singolo dispositivo e utente. Non include sincronizzazione, autenticazione o database condiviso.