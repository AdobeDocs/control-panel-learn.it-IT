---
title: Aggiungere certificati SSL
description: Scopri come aggiungere certificati SSL per proteggere i sottodomini.
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: d12902547ffde67838b326c93162d0937ff438a6
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 38%

---

# Aggiungere certificati SSL

 Il [!UICONTROL Control Panel] di Adobe Campaign consente di aggiungere certificati SSL per proteggere i sottodomini.

## Accesso alla gestione dei sottodomini del Pannello di controllo Campaign

Per accedere alla gestione dei sottodomini nel Pannello di controllo Campaign, vai a:

* [Home di Experience Cloud](https://experience.adobe.com/#/home) > Selezione soluzioni: **[!DNL Campaign]** > scheda **[!UICONTROL Control Panel]** > scheda **[!UICONTROL Subdomains & Certificates]**

   o
* Direttamente dall’URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Passaggi per aggiungere certificati SSL

Occorrono tre passaggi per aggiungere certificati SSL:

### 1. Generare le richieste di firma del certificato

La richiesta di firma del certificato (CSR, Certificate Signing Request) è necessaria per l’acquisto di un certificato SSL. Deve essere generato per l’istanza e i sottodomini che intendi proteggere.

Il video seguente descrive come generare una richiesta di firma del certificato nel Pannello di controllo Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Generate Certificate Signing Requests (02:36 min)*

>[!NOTE]
>
>Sono stati apportati diversi miglioramenti al processo di generazione della RSI:
>
>* Quando generi una CSR, ora puoi selezionare uno dei sottodomini inclusi come Nome comune.
>* Ora puoi copiare il riepilogo CSR prima di generare la CSR.
>* Una volta generata una CSR, puoi scaricarla nuovamente dai registri di lavoro. Questa funzionalità non si applica ai certificati generati prima di questa versione.
>
>![Scarica CSR](/help/assets/download-csr.gif)
>
>Consulta la sezione [documentazione del prodotto](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) per saperne di più.

### 2. Acquistare il certificato SSL

Dopo aver ottenuto la CSR, devi acquistare il certificato SSL da un’autorità di certificazione approvata dalla tua organizzazione.

### 3. Installare i certificati SSL

Una volta ottenuto il certificato SSL, devi installarlo per i sottodomini che intendi proteggere.

Il video seguente spiega come installare i certificati SSL nel [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Install SSL Certificates (01:25 min)*


