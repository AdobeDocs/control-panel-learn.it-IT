---
title: Risoluzione dei problemi del Pannello di controllo
description: Scopri come risolvere i problemi del Pannello di controllo.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
source-git-commit: 9b8483fbaa7dce7f908c79e929d3b9628fd8fa44
workflow-type: tm+mt
source-wordcount: 353
ht-degree: 70%

---

# Risoluzione dei problemi del [!UICONTROL Pannello di controllo]

## Login e homepage

### Sintomo: impossibile accedere a Experience Cloud

**Come procedere:**
L’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto “Campaign-xxx-Admins” per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Pannello di controllo] non vengono visualizzati per un utente

**Causa:**
Gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
L&#39;amministratore deve aggiungere l&#39;utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Pannello di controllo]

**Causa:**
Probabilmente l&#39;utente deve essere aggiunto come *utente* al profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l&#39;istanza mancante

**Come procedere:**
L&#39;amministratore deve aggiungere l&#39;utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Verificare l’ID organizzazione IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Come aggiungere un amministratore agli amministratori di profilo di prodotto per poter utilizzare [!UICONTROL Pannello di controllo] (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni per il [!UICONTROL Pannello di controllo]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* Aggiungere all’[!UICONTROL elenco Consentiti] l’indirizzo IP per la connessione al server SFTP
* Una coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Per connetterti direttamente al server SFTP, devi usare anche un software client SFTP.

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
