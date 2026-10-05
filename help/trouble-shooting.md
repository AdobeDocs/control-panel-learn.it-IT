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
TQID: 'https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: e4a8e51ee4016895090eb90d528d0a2707fd0225
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 92%
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
 L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ciascuna istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Pannello di controllo]

**Causa:**
Probabilmente l’utente deve essere aggiunto come *utente* al Profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l’istanza mancante

**Come procedere:** L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Verifica ID organizzazione IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Come aggiungere un amministratore al profilo di prodotto per poter utilizzare [!UICONTROL Pannello di controllo] (01:03 min)*

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
