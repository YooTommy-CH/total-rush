# Installare Total Rush

**La 0.2.3 è in preparazione e non è ancora scaricabile.** I pacchetti attualmente presenti sono le versioni storiche PITCHONE. Le istruzioni seguenti valgono per Total Rush quando la nuova release sarà pubblicata.

Al rilascio, scarica la build del tuo sistema da [GitHub Releases](https://github.com/YooTommy-CH/total-rush/releases/latest).

## macOS Apple Silicon

1. Scarica il pacchetto macOS ARM64 ed estrailo.
2. Sposta l’app in Applicazioni o in una cartella in cui puoi scrivere.
3. Apri l’app: il gioco si presenta come **Total Rush**.

La build è nativa ARM64 e usa Metal. Firma e notarizzazione Apple della build finale sono ancora da completare prima del rilascio. Non serve Rosetta. Il nome del pacchetto e della cartella `.app` può conservare PITCHONE per compatibilità con gli aggiornamenti precedenti; puoi rinominare l’app Total Rush.app dopo l’estrazione.

## Windows 10/11 x64

1. Scarica il pacchetto Windows ed estrailo in una cartella dedicata.
2. Mantieni insieme eseguibile, cartella dei dati e tutte le librerie.
3. Avvia `PITCHONE.exe`: il nome visualizzato dal gioco è **Total Rush**.

Non estrarre i singoli file direttamente sul Desktop. La build usa Direct3D 11 ed è compilata per x64; non è ancora stata provata su un PC Windows in questa sessione di rilascio.

## Aggiornare dal gioco

All’apertura viene controllata l’ultima versione stabile. Premi **Aggiorna ora**, attendi la verifica e lascia che l’app si chiuda e si riapra. Il pulsante **Aggiornamenti** nel menu permette di avviare un controllo manuale.

La copia precedente viene conservata per il ripristino. I file delle carriere della vecchia simulazione restano separati dalle carriere Rush. La libreria della soundtrack non viene sostituita.

Le versioni PITCHONE precedenti alla 0.2.1 richiedono un primo download manuale. Anche le 0.2.1 e 0.2.2 richiederanno un download manuale di Total Rush: il vecchio repository è in dismissione.

## Soundtrack personale

La raccolta personale viene letta dalla libreria del dispositivo e funziona offline. MP3 e copertine non sono inclusi nei pacchetti pubblici. Le nuove installazioni possono usare i suoni originali del gioco senza quella raccolta.
