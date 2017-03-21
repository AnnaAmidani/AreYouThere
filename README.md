Are You There

Customization of an XMPP server and implementation of a plugin for Openfire for managing the server part of a Car pooling  Apple Iphone application (with APNS support)

Dev environment

* Scaricare e decomprimere i sorgenti di openfire (http://www.igniterealtime.org/downloads/source.jsp)
* Copia/scarica il progetto nella cartella openfire/src/plugins e rinomina (se necessario) la root del progetto in motayt

Build

(procedura in ambiente linux con ant, a Java based make tool, preinstalllato)

* cd openfire/build
* ant

Run

(procedura in ambiente linux)

* cd openfire/target/openfire/bin
* sh openfire.sh

Ambiente di produzione
Preparazione
* Scaricare e decomprimere la versione binary di openfire (http://www.igniterealtime.org/downloads/index.jsp)

Run Server

(procedura in ambiente linux)

* cd openfire
* ./bin/openfire

Load motayt

* Una volta avviato il server andare su http://localhost:9090/ e dalla sezione plugin caricare il file motayt.jar (il jar viene creato durante la build della versione di sviluppo nel percorso openfire/target/openfire/plugins/motayt.jar)

