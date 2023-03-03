---
title: Risoluzione dei problemi del Pannello di controllo
description: Scopri come risolvere i problemi del Pannello di controllo.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
source-git-commit: dc31bc114b82eae4042562f292d5f52203c7e2b3
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 100%

---

# Risoluzione dei problemi del [!UICONTROL Control Panel]

## Login e homepage

### Sintomo: impossibile accedere a Experience Cloud

**Come procedere:**
L’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto “Campaign-xxx-Admins” per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Control Panel] non vengono visualizzati per un utente

**Causa:**
Gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Control Panel]

**Causa:**
Probabilmente l’utente deve essere aggiunto come *utente* al Profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l’istanza mancante

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Verificare Org ID IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Come aggiungere un amministratore al profilo di prodotto in modo che possa utilizzare il [!UICONTROL Control panel] (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni per il [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Allow listing] l’indirizzo IP da cui desideri connetterti al server SFTP
* Una coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Per connetterti direttamente al server SFTP, devi usare anche un software client SFTP.

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
