---
layout: page
title: Il Progetto
---

# Il progetto

Nella pratica, questo progetto può consistere nella creazione di un servizio che:

* permetta di segnalare contenuti open data evidenziandone la licenza
* vada a recuperare i contenuti segnalati e, periodicamente, eventuali aggiornamenti, conservandone la storia
* corredi tutti i contenuti di metadati recuperandoli o chiedendoli alla segnalatrice
* (opzionale) renda accessibili i contenuti attraverso API generiche

## Segnalazione dei contenuti

La segnalazione dei contenuti può essere analoga a quella che si può verificare su [transit.land](transit.land), che appunto consente agli utenti di inserire
fonti dati (in questo caso GTFS) che poi verranno scaricate periodicamente.

## Recupero dei contenuti

Occorre un servizio o più servizi che abbiano il compito di verificare periodicamente lo stato della risorsa monitorata, scarichino eventuali aggiornamenti e tengano traccia delle modifiche.

## Metadati

Ogni dato scaricato verrà corredato del più ampio possibile numero di metadati, andandoli a recuperare all'origine (nel caso di dati catalogati, vedi DCAT), oppure chiedendo a chi segnala di fornire le informazioni.

