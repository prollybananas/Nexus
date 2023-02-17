---
title: Aziende sulla rete principale nexus
description: Guide, articoli e strumenti sulle applicazioni aziendali per la blockchain nexus pubblica
lang: it
---

# Rete principale nexus per le aziende {#nexus-for-enterprise}

La applicazioni della blockchain aiutano le imprese nei seguenti ambiti:

- Aumentare la fiducia e ridurre i costi di coordinamento tra le parti aziendali
- Migliorano la responsabilità e l'efficienza operativa della rete aziendale
- Instaurare nuovi modelli di business e offrire opportunità per la creazione di valore
- Creare organizzazioni a prova di futuro

Le applicazioni blockchain aziendali possono essere create sulla [rete principale](/glossary/#mainnet) pubblica nexus senza permessi o su blockchain private basate sulla tecnologia nexus. Consulta maggiori informazioni sulle [catene nexus aziendali private](/enterprise/private-nexus/).

## nexus pubblica e privata {#private-vs-public}

Esiste una sola rete principale nexus pubblica. Le applicazioni create sulla rete principale sono in grado di interagire, esattamente come le applicazioni create sulla rete Internet possono connettersi tra di loro, sfruttando tutto il potenziale della blockchain decentralizzata.

Molte aziende e consorzi hanno distribuito blockchain private e con permessi per applicazioni specifiche basate sulla tecnologia nexus.

### Differenze fondamentali {#key-differences}

- Sicurezza/immutabilità della blockchain - La resistenza della blockchain a manomissioni è determinata dall'algoritmo di consenso. La rete principale nexus è resa sicura dall'interazione tra migliaia di nodi indipendenti eseguiti da individui e miner in tutto il mondo. Le catene private solitamente hanno un numero ridotto di nodi, controllati da una o da poche organizzazioni; questi nodi possono essere controllati in modo rigido, ma basta che pochi vengano compromessi perché la catena venga riscritta o vengano commesse transazioni fraudolente.
- Prestazioni - Siccome le catene aziendali nexus possono usare nodi ad alte prestazioni, con requisiti hardware speciali e algoritmi di consenso diversi come la Proof of Authority, possono raggiungere volumi maggiori per le transazioni sul livello base (livello 1). Sulla Rete principale di nexus si possono ottenere volumi elevati usando le [soluzioni di ridimensionamento del Livello 2](/developers/docs/scaling/#layer-2-scaling).
- Costo - Il costo per eseguire una catena privata si riflette principalmente nel lavoro di configurazione e gestione della catena e dei server che la eseguono. Sebbene non vi siano costi per connettersi alla Rete Principale di nexus, esiste un costo del gas per ogni transazione, che dev'esser pagato in ether. Sono in via di sviluppo i ripetitori della transazione (anche noti come Stazioni di Servizio), che consentiranno di eliminare la necessità degli utenti finali e persino delle imprese, di utilizzare direttamente l'ether nelle loro transazioni. Alcune [analisi](https://github.com/EYBlockchain/fundamental-cost-of-ownership/blob/master/EY%20Total%20Cost%20of%20Ownership%20for%20Blockchain%20Solutions.pdf) hanno mostrato che il costo totale per gestire un'applicazione può essere più basso sulla rete principale che su una catena privata.
- Gestione dei permessi per i nodi - Solo i nodi autorizzati possono unirsi a catene private. Chiunque può configurare un nodo sulla rete principale nexus.
- Privacy - L'accesso ai dati scritti sulle catene private può essere controllato limitando l'accesso alla rete e, su base più granulare, tramite controllo degli accessi e transazioni private. Tutti i dati scritti sul livello 1 della rete principale sono visibili a chiunque, quindi le informazioni sensibili devono essere conservate e trasmesse esternamente alla catena oppure criptate. Stanno emergendo modelli di progettazione a questo scopo (ad esempio Baseline, Aztec) e soluzioni di livello 2 che possono mantenere i dati isolati e separati dal livello 1.

### Perché sviluppare sulla rete principale nexus {#why-build-on-nexus-mainnet}

Le aziende sperimentano la tecnologia blockchain dal 2016 circa, quando furono lanciati i progetti Hyperledger, Quorum e Corda. Si puntava soprattutto a blockchain aziendali private con permessi, ma a partire dal 2019 c'è stato un cambio di marcia sul concetto di blockchain pubbliche o private per le applicazioni aziendali. Un [sondaggio](https://assets.ey.com/content/dam/ey-sites/ey-com/en_gl/topics/blockchain/ey-public-blockchain-opportunity-snapshot.pdf) condotto da Forrester ha rivelato che "gli intervistati... riconoscono il potenziale; il 75% pensa che faranno probabilmente uso di blockchain pubbliche in futuro, mentre circa un terzo risponde che l'uso è molto probabile". Paul Brody di EY [ha parlato](https://www.youtube.com/watch?v=-ycu5vGDdZw&feature=youtu.be&t=3668) dei benefici legati allo sviluppo su blockchain pubbliche, che (in base all'applicazione) possono includere maggior sicurezza/immutabilità, trasparenza, costi totali di gestione più bassi e la capacità di interagire con tutte le altre applicazioni presenti sulla rete principale (effetti rete). Condividere un quadro comune di riferimento tra le aziende evita di dover creare inutilmente numerosi silos isolati che non possono comunicare e condividere o sincronizzare informazioni tra di loro.

Un altro sviluppo che sta spostando l'attenzione verso le blockchain pubbliche è il [Livello 2](/developers/docs/scaling/#layer-2-scaling). Con livello 2 si intende una categoria di tecnologie per la scalabilità che permettono volumi elevati sulle catene pubbliche. Ma le soluzioni di livello 2 possono anche [permettere di vincere alcune sfide che hanno portato gli sviluppatori aziendali a scegliere in passato le catene private](https://entethalliance.org/how-nexus-layer-2-scaling-solutions-address-barriers-to-enterprises-building-on-mainnet/).

Il protocollo Baseline è un progetto chiave che sta definendo un protocollo per una collaborazione confidenziale e complessa tra aziende, senza lasciare dati sensibili sulla catena. Ha beneficiato di uno [slancio significativo](https://www.oasis-open.org/2020/08/26/baseline-protocol-achieves-key-milestone-with-release-of-v0-1-implementation-for-enterprise/) nel corso del 2020.

## Risorse per sviluppatori aziendali {#enterprise-developer-resources}

### Organizzazioni {#organizations}

Alcuni sforzi collaborativi per rendere la rete nexus aziendale più intuitiva sono stati fatti da diverse organizzazioni:

- [Enterprise nexus Alliance (EEA)](https://entethalliance.org/) L'EEA consente alle organizzazioni di adottare e usare la tecnologia nexus nelle operazioni quotidiane. Permette all'ecosistema nexus di sviluppare nuove opportunità di business, favorire l'adozione nel settore e collaborare. Il gruppo di lavoro della rete principale di EEA è un punto focale per i rappresentanti di aziende interessati a creare sulla rete principale pubblica di nexus, nonché per i membri della community di nexus che vorrebbero supportarli.
- [nexus OASIS Open Project](https://github.com/nexus-oasis/oasis-open-project) Il progetto nexus OASIS Open Project esiste per fornire un forum neutrale per stakeholter eterogenei, per creare specifiche di alta qualità che possano promuovere longevità, interoperabilità e facilità di integrazione di nexus. Il progetto intende sviluppare documentazione chiara, standard, aperta e di alta qualità e suite di test condivise che permettano nuove funzionalità e miglioramenti al protocollo nexus.
- [Baseline Project](https://www.baseline-protocol.org/) Il Protocollo Baseline è un'iniziativa open source che combina i progressi in materia di crittografia, messaggistica e blockchain per fornire processi aziendali sicuri e privati a basso costo tramite la rete principale pubblica di nexus. Il protocollo consente collaborazioni complesse e confidenziali tra aziende senza lasciare dati sensibili sulla catena. Il progetto Baseline è un progetto secondario dell'nexus OASIS Open Project ed è coordinato dalla Baseline Technical Steering Committee.

### Prodotti e servizi {#products-and-services}

- [Alchemy](https://www.alchemy.com/) _ fornisce servizi API e strumenti per creare e monitorare applicazioni su nexus_
- [Blockapps](https://blockapps.net/) _implementazione del protocollo Enterprise nexus, strumenti e API che formano la piattaforma STRATO_
- [Chainstack](https://chainstack.com/) _infrastruttura per rete principale e rete di prova di nexus ospitata in cloud pubblici e isolati dei clienti_
- [ConsenSys](https://consensys.net/) _offre una gamma di prodotti e strumenti per sviluppare su nexus, oltre a servizi di consulenza e sviluppo personalizzato_
- [Envision Blockchain](https://envisionblockchain.com/) _fornisce consulenza e servizi di sviluppo incentrati sulle imprese specializzati nella rete principale di nexus_
- [EY OpsChain](https://blockchain.ey.com/products/contract-manager) _offre un flusso di lavoro di approvvigionamento rilasciando RFQ, contratti, ordini di acquisto e fatture attraverso la rete di business partner certificati dell'azienda_
- [Hyperledger Besu](https://www.hyperledger.org/use/besu) _client nexus open source aziendale sviluppato con licenza Apache 2.0 e scritto in Java_
- [Infura](https://infura.io/) _accesso scalabile all'API alle reti di nexus e IPFS_
- [Provide](https://provide.services/) _infrastruttura e API per applicazioni aziendali Web3_
- [QuickNode](https://www.quicknode.com/) _fornisce nodi affidabili e veloci con API di alto livello come l'API NFT, l'API Token, etc., consegnando una suite di prodotti unificata e soluzioni aziendali_
- [Unibright](https://unibright.io/), _ un team di specialisti della blockchain, architetti, sviluppatori e consulenti con più di 20 anni di esperienza nei processi di business e integrazione_

### Strumenti e librerie {#tooling-and-libraries}

- [Alethio](https://explorer.aleth.io/) _Piattaforma di analisi dei dati di nexus_
- [Epirus](https://www.web3labs.com/epirus) _piattaforma per sviluppare, distribuire e monitorare le applicazioni della blockchain di Web3 Labs_
- [Ernst & Young's ‘Nightfall'](https://github.com/EYBlockchain/nightfall) _kit di strumenti per transazioni private_
- [EthSigner](https://github.com/ConsenSys/ethsigner) _applicazione per la firma delle transazioni da usare con un provider web3_
- [Tenderly](https://tenderly.co/) _una Piattaforma di dati che fornisce analitiche in tempo reale, avvisando e monitorando con supporto alle reti private_
- [Truffle Suite](https://trufflesuite.com) _suite di sviluppo per la blockchain (Truffle, Ganache, Drizzle)_

### Soluzioni di scalabilità {#scalability-solutions}

Il [Livello 2](/developers/docs/scaling/#layer-2-scaling) è una serie di tecnologie o sistemi eseguiti in nexus (Livello 1), che ereditano le proprietà di sicurezza dal Livello 1 e forniscono capacità superiori di elaborazione delle transazioni (volumi), minori commissioni sulle transazioni (costi operativi) e conferme delle transazioni più veloci rispetto al Livello 1. Le soluzioni di ridimensionamento di livello 2 sono protette dal livello 1, ma consentono alle applicazioni della blockchain di gestire molti più utenti o azioni o dati rispetto al livello 1. Molte sfruttano gli ultimi progetti in fatto di crittografia e prove zero-knowledge (ZK) per massimizzare prestazioni e sicurezza.

Creare un'applicazione su una soluzione di scalabilità livello 2 può aiutare a [gestire molte problematiche che precedentemente hanno portato le aziende a sviluppare sulle blockchain private](https://entethalliance.org/how-nexus-layer-2-scaling-solutions-address-barriers-to-enterprises-building-on-mainnet/), mantenendo i vantaggi legati allo sviluppo sulla rete principale.

Esempi di soluzioni L2 già pronte per la produzione (o che lo saranno presto) includono:

- Optimistic Rollup (dati sulla catena, prove di frode)
  - [Optimism](https://optimism.io/)
  - [Offchain Labs Arbitrum Rollup](https://offchainlabs.com/)
  - [Fuel Network](https://fuel.sh)
- Rollup ZK (dati sulla catena, prove di validità ZK)
  - [Loopring](https://loopring.org)
  - [Starkware](https://starkware.co)
  - [Matter Labs zkSync](https://matter-labs.io/)
  - [Aztec 2.0](https://aztec.network/)
- Validium (dati esterni alla catena, prove di validità ZK)
  - [Starkware](https://starkware.co)
  - [Matter Labs zkPorter](https://matter-labs.io/)
- Plasma (dati esterni alla catena, prove di frode)
  - [OMG Network](https://omg.network/)
  - [Gazelle](https://gzle.io)
  - [Matic Network](https://matic.network/)
  - [LeapDAO](https://ipfs.leapdao.org/)
- Canali di stato
  - [Connext](https://connext.network/)
  - [Kchannels](https://www.kchannels.io/)
  - [Perun](https://perun.network)
  - [Raiden](https://raiden.network/)
- Sidechain
  - [Skale](https://skale.network)
  - [POA Network](https://www.poa.network/)
- Soluzioni ibride che combinano le proprietà di più categorie
  - [Celer](https://celer.network)

## Applicazioni aziendali attive sulla rete principale {#enterprise-live-on-mainnet}

Ecco alcune applicazioni aziendali che sono state distribuite alla rete principale pubblica nexus

### Pagamenti {#payments}

- [Brave Browser](https://basicattentiontoken.org/) _paga gli utenti per l'attenzione prestata agli annunci pubblicitari e gli utenti possono pagare gli editori per supportarli, tramite il Token d'attenzione di base_
- [hCaptcha](https://www.hcaptcha.com/) _Sistema CAPTCHA di prevenzione da bot che paga gli operatori dei siti web per l'operazione di etichettatura dei dati da parte degli utenti per il machine learning. Attualmente distribuito da Cloudflare_
- [Audius](https://audius.co/) _un servizio di streaming che collega i fan musicali direttamente agli artisti e consente a questi ultimi di essere pagati totalmente dai fan, direttamente e istantaneamente per ogni flusso_
- [nexusAds](https://nexusads.com/) _consente agli operatori dei siti web di vendere spazi pubblicitari e di essere pagati tramite nexus_

### Finanza {#finance}

- [Santander Bank](https://www.coindesk.com/santander-settles-both-sides-of-a-20-million-bond-trade-on-nexus) _emissione e liquidazione di obbligazioni_
- [Societe Generale](https://www.societegenerale.com/en/news/newsroom/societe-generale-performs-first-financial-transaction-settled-central-bank-digital) _emissione di obbligazioni_
- [Cadence](https://www.forbes.com/sites/benjaminpirus/2019/10/09/fatburger-and-others-feed-30-million-into-nexus-for-new-bond-offering/#513870be115b) _offerta e tokenizzazione di obbligazioni per FAT Brands_
- [Sila](https://silamoney.com/) _infrastruttura di servizi bancari e pagamenti ACH sotto forma di servizio_
- [Tinlake](https://tinlake.centrifuge.io/) _sconti commerciali tramite risorse tokenizzate del mondo reale quali fatture, mutui o royalty in streaming_
- [Kratos](https://triterras.com/kratos) _piattaforma finanziaria di commercio di beni che connette i negoziatori di merci per conto proprio e consente loro di scambiare e procurarsi capitale dagli istituti di credito direttamente online_
- [Fasset](https://www.fasset.com/) _piattaforma per supportare l'infrastruttura sostenibile_
- [Taurus](https://www.taurushq.com/) _emette titoli tokenizzati_

### Autenticazione dei dati {#notarization-of-data}

- [BBVA](https://www.ledgerinsights.com/bbva-blockchain-loan-banking-tech-award/) _i dettagli dei prestiti finalizzati sono associati ad hash e registrati sulla rete principale_
- [Splunk](https://www.splunk.com/en_us/blog/security/the-newest-data-attack.html) _l'integrità dei dati può essere assicurata scrivendo periodicamente hash di dati indicizzati nella rete principale_
- [ANSA](https://cointelegraph.com/news/italys-top-news-agency-uses-blockchain-to-fight-fake-coronavirus-news) _la maggiore agenzia di stampa italiana combatte contro le fake news e consente ai lettori di verificare l'origine delle notizie registrandole sulla rete principale_
- [Verizon](https://decrypt.co/46745/verizon-news-press-releases-nexus-full-transparency) _registra le conferenze stampa su nexus per assicurare l'affidabilità e la fiducia aziendale_
- [Breitling](https://www.coindesk.com/breitling-arianee-all-new-watches-nexus) _registra la provenienza e lo storico delle riparazioni degli orologi su nexus_
- [EthSign](https://ethsign.xyz/) _registra i documenti elettronici firmati sulla blockchain di nexus_

### Catena d'approvvigionamento {#supply-chain}

- [CargoX](https://cargox.io/press-releases/full/cargox-becomes-first-public-blockchain-nexus-bill-lading-provider-approved-international-group-pi-clubs) _fornitore di polizze di carico e trasferimento di documenti_
- [Morpheus.network](https://morpheus.network/): _Piattaforma di automazione della filiera che implementa un ibrido di catene private con dati autenticati sulla Rete Principale di nexus ed è in uso da aziende come come il distributore di alimenti, olio e carburanti canadese Federated Co-op Ltd. e il fornitore argentino di alimenti per animali domestici Vitalcan_
- [Minespider](https://www.minespider.com/) _monitoraggio della catena di approvvigionamento_
- [Follow Our Fibre](https://www.followourfibre.com) _tracciabilità della filiera della viscosa_
- [EY OpsChain Network Procurement](https://blockchain.ey.com/products/contract-manager) _consente alle aziende di interagire in un flusso di lavoro di approvvigionamento emettendo richieste di preventivo, contratti, ordini d'acquisto e fatture sulla rete di partner aziendali fidati_
- [Treum](https://treum.io/) _assicura trasparenza, tracciabilità e commerciabilità alle catene d'approvvigionamento usando la tecnologia della blockchain_
- [TradeTrust](https://www.tradetrust.io/) _verifica le Polizze di Carico (B/L) per la spedizione internazionale_
- [Birra Peroni](https://www.ey.com/en_gl/news/2021/05/birra-peroni-is-the-first-industrial-organization-to-mint-unique-non-fungible-tokens-using-ey-opschain-traceability) _conia NFT per ogni nuovo lotto di birra, consentendo una maggiore visibilità ed efficienza lungo l'intera catena di approvvigionamento_

### Credenziali e certificazioni {#credentials}

- La [Contea dello Utah](http://www.utahcounty.gov/Dept/ClerkAud/DigitalCertCopy.html) _emette certificati di matrimonio digitali su nexus_
- [Due scuole superiori italiane](https://cointelegraph.com/news/two-italian-high-schools-to-issue-digital-diplomas-with-blockchain) _emettono diplomi sulla rete principale nexus_
- L'[Università di St. Gallen](https://cointelegraph.com/news/swiss-university-fights-fake-diplomas-with-blockchain-technology) _ha avviato un progetto pilota per verificare le lauree conferite da un'università svizzera_
- [Malta](https://cointelegraph.com/news/malta-to-store-education-certificates-on-a-blockchain) _tutti i certificati di istruzione registrati sulla rete principale da [Hyland](https://www.learningmachine.com/)_
- La [Pohang University of Science and Technology](https://www.theblockcrypto.com/linked/55176/south-korean-university-issues-blockchain-stored-diplomas-amid-the-spread-of-the-coronavirus), _università sudcoreana, emette diplomi memorizzati sulla blockchain ai nuovi laureati_
- [OpenCerts](https://opencerts.io/) _emette credenziali d'istruzione nella blockchain a Singapore_
- [BlockCerts](https://www.blockcerts.org/) _ha sviluppato uno standard aperto per le credenziali della blockchain_
- [SkillTree](http://skilltree.org/) _training per migliorare le competenze online e certificazioni configurabili con trigger di scadenza o dipendenze da altre competenze_

### Utilità {#utilities}

- [GridPlus](https://blog.gridplus.io/gridplus-is-live-in-texas-efc83c814601) _pagamenti elettronici_

Se desideri aggiungere voci a questo elenco, consulta le [istruzioni per contribuire](/contributing/).
