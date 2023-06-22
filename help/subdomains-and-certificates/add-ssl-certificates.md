---
title: Aggiungere certificati SSL
description: Scopri come aggiungere certificati SSL per proteggere i sottodomini.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: af05bde1295913c93388dd014462e32afb081669
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 100%

---

# Aggiungere certificati SSL

 Il [!UICONTROL Control Panel] di Adobe Campaign consente di aggiungere certificati SSL per proteggere i sottodomini.

## Accesso alla gestione dei sottodomini del Pannello di controllo

Per accedere alla gestione dei sottodomini nel Pannello di controllo, vai a:

* [Home di Experience Cloud](https://experience.adobe.com/#/home) > Selezione soluzioni: **[!DNL Campaign]** > scheda **[!UICONTROL Control Panel]** > scheda **[!UICONTROL Subdomains & Certificates]**

  o
* Direttamente dall’URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Passaggi per aggiungere certificati SSL

Occorrono tre passaggi per aggiungere certificati SSL:

### 1. Generare le richieste di firma del certificato

La richiesta di firma del certificato (CSR) è necessaria per l’acquisto di un certificato SSL. Deve essere generata per l’istanza e i sottodomini che desideri proteggere.

Il video seguente descrive come generare una richiesta di firma del certificato nel Pannello di controllo.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12&learn=0n)

*Generazione di una richiesta di firma del certificato (02:36 min)*

>[!NOTE]
>
>Sono stati apportati diversi miglioramenti al processo di generazione della CSR:
>
>* Quando generi una CSR, ora puoi selezionare uno dei sottodomini inclusi come Nome comune.
>* Ora puoi copiare il riepilogo CSR prima di generare la CSR.
>* Una volta generata una CSR, puoi scaricarla nuovamente dai registri dei lavori. Questa funzionalità non si applica ai certificati generati prima di questa versione.
>
>![Scarica CSR](/help/assets/download-csr.gif)
>
>Per ulteriori informazioni, consulta la [documentazione del prodotto](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=it).
>

### 2. Acquistare il certificato SSL

Dopo aver ottenuto la CSR, dovrai acquistare il certificato SSL da un’autorità di certificazione approvata dall’organizzazione.

### 3. Installare i certificati SSL

Una volta ottenuto il certificato SSL, dovrai installarlo per i sottodomini che desideri proteggere.

Il video seguente spiega come installare i certificati SSL nel [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12&learn=0n)

*Installare i certificati SSL (01:25 min)*


