# OSINT Investigation Chart

Sito pubblicato: https://osint-investigation-chart.vercel.app

Aprire `index.html` per usare anche la versione locale. Le librerie del grafo sono incluse; i font web usano caratteri di sistema come alternativa.

## Modifiche
- Menu iniziale ridisegnato e adattato a desktop e smartphone. L’apertura avviene sempre dal menu.
- Otto disposizioni delle entità, spaziatura regolabile e rispetto delle entità fissate.
- Nomi con ritorno a capo misurato e testo completo nel suggerimento al passaggio del mouse.
- Etichette dei collegamenti sul percorso delle frecce, aggiornate durante trascinamenti singoli e multipli. Doppio clic per modificare una relazione.
- Cerchi opachi: le linee che passano dietro non attraversano visivamente l’entità.
- Correzioni a importazione, verifica delle entità ed esportazione SVG.

## Salvataggio
Save memorizza i casi nel browser del dispositivo. Export salva una copia JSON da conservare o importare su un altro dispositivo o indirizzo. I casi del file locale non vengono trasferiti automaticamente al sito Vercel: usare Export e Import.

## Pubblicazione
Il sito è statico, senza database o backend. Sono pubblicati soltanto HTML e configurazione Vercel; i file di indagine adiacenti all’originale non sono inclusi.

## Verifiche
Provati gli otto layout su un caso sintetico con 30 entità e 28 relazioni, senza sovrapposizioni dei nodi nel test. Verificati salvataggio e ripristino, entità fissate, home mobile a 390 px, nomi lunghi, tema scuro ed esportazione SVG. Le etichette mantengono la posizione sul percorso durante il trascinamento; verificati rete e collegamenti ortogonali. Verificato anche trascinamento multiplo.

## Foto delle entità
Selezionare un’entità, aprire Entities e usare Upload photo. Formati: JPG, PNG e WebP, fino a 10 MB. La foto viene ritagliata al centro e ridimensionata a un massimo di 320 × 320 pixel. Per un’entità esistente scegliere Apply photo change; per una nuova usare Add. Save ed Export includono la foto nel caso. Sono disponibili sostituzione, rimozione e annullamento. Le foto rimangono nei dati locali del caso e non vengono inviate a un servizio fotografico.
