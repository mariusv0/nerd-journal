---
title: CMS i 2022
slug: cms-i-2022
---
### Hvad er CMS?

CMS (Content Management System) er software der kører på en server, som bruges til at udgive og redigere content som vises på deres eksempelvis hjemmeside. Det vil altså sige at du som udvikler kan lave en hjemmeside uden måske at have alle tekster og billeder på plads, og i stedet  bruge dit CMS API til at udfylde siden med content. Det gør det altså utroligt nemt for kunden at redigere indhold hvis man ligepludselig vil ændre en tekst, indsætte nogle andre billeder eller flytte rundt på menuerne - hvilket gør at du som udvikler ikke skal til at gå ind i koden og rette tekster frem og tilbage.

Der er mange forskellige måder at bruge et CMS på, men de to primære typer for CMS er **Headless CMS** og **traditionelt/coupled CMS**

**Traditionelt/Coupled CMS** betyder i bund og grund at det er samme system der bruges i både backend og frontend. Det er altså sammen system der bliver vist til de besøgende på siden som bruges af administratorerne til at ændre indholdet, hvilket i de fleste tilfælde er sikret bag et login til et kontrolpanel.

**Headless CMS** vil sige at det er forskellige systemer der er brugt til slutbrugeren og administratorerne. Du har altså et system på en server hvor du kan redigere indhold og styre alt din content - og så kan du på din frontendløsning lave API calls dertil og hente indholdet. Det er meget fleksibelt da frontenden ikke afhænger af hvilket CMS du bruger og omvendt. Du kan altså have både en app og en hjemmeside - og hente din content fra samme CMS.

### 3 populære CMS i forskellige kategorier

En generel ting som skal siges er at i rigtig mange af de traditionelle CMS, er der integrationer og udvidelser man kan installere, så man kan bruge det som et headless CMS

**WordPress**

[WordPress](https://wordpress.org) er det mest udbredte CMS i verden og er skrevet i PHP - dertil er det open-source. Det er oprindeligt bygget til at lave blogs, men er blevet meget populært at bruge til helt almindelige hjemmesider og endda også webshops med udvidelser som WooCommerce. Der er udviklet mange temaer som man frit kan benytte til at bygge sin hjemmeside uden at kunne en linje kode. WordPress har en rigtig god REST API så du kan bruge WordPress systemet som Headless CMS, hvis du vil læse mere om dette kan du gå ind på den officielle dokumentation [her](https://developer.wordpress.org/rest-api/).

**Shopify**

[Shopify](https://www.shopify.com/) er et CMS system bygget direkte til at udvikle webshops - hvor du bruger open-source templating sproget Liquid i din frontend til at kommunikere med CMS’et. Shopify er meget populært for deres skalerbare platform og er et mere intuitivt alternativ til løsninger som WooCommerce på WordPress, da det er bygget direkte til e-commerce. I Shopify har du også muligheden for at bruge deres API til at lave en headless løsning, så du eksempelvis kan lave hele din frontend i Vue eller React, men bruge Shopify platformen til at håndtere ordre, produkter mm.

**Strapi**

[Strapi](https://strapi.io/) er et open-source headless CMS, der gør det lynhurtigt at designe API’er. Det er opbygget i JavaScript, og hvis du dertil bruger GraphQL integrationen har du lynhurtigt en rigtig fin API, som du kan bruge til dit projekt.