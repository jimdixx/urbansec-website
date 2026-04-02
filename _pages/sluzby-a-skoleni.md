---
layout: single
title: "Služby a školení"
author_profile: true
permalink: /sluzby-a-skoleni/
lang: cs
toc: true
toc_sticky: true
last_modified_at: 2026-04-01T20:26
---

# Služby a školení v oblasti kybernetické bezpečnosti

Jsem na začátku své cesty v oblasti security consultingu a školení a postupně sbírám zkušenosti
nad rámec své hlavní práce v etickém hackingu a softwarovém vývoji.  
Neprovozuji velkou poradenskou firmu a těmto službám se zatím nevěnuji na plný úvazek, ale mám
praktické znalosti, které mohou být velmi užitečné pro organizace, které se kybernetické
bezpečnosti teprve začínají věnovat, nebo ještě nemají zavedené základní postupy a standardy.

Pokud jste menší firma nebo tým bez vlastního bezpečnostního oddělení, mohu:

- **sdílet praktické doporučení**,  
- **pomoci odhalit základní slabá místa**,  
- **představit vašim vývojářům či zaměstnancům základy kybernetické bezpečnosti**.

---

## Oblasti, ve kterých mohu pomoci

### 1. Bezpečnostní konzultace a základní posouzení

Mohu se s vámi podívat na vaše aplikace a procesy z pohledu bezpečnosti a upozornit na
zjevná rizika. Nejde o formální penetrační test nebo plnohodnotný audit, ale o praktický a
„developer‑friendly“ pohled na věc. Typické aktivity zahrnují:

- Vysokoúrovňový přehled webových aplikací a interních nástrojů se zaměřením na nejčastější problémy.
- Identifikaci typických slabin (např. injekční zranitelnosti, slabé ověřování, nebezpečné vzory ukládání dat).
- Základní přehled o stavu zabezpečení: patchování, řízení přístupu, vystavené služby.
- Konkrétní návrhy kroků ke zlepšení, které váš tým dokáže reálně zavést.

Mým cílem není jen „najít chyby“, ale hlavně vysvětlit, **proč** jsou problém a jak se jim
v budoucím vývoji vyhnout.

---

### 2. Bezpečný vývoj a architektura (úvodní úroveň)

Vyšel jsem ze softwarového inženýrství, takže mohu podpořit váš vývojový tým při
zabezpečení aplikací - zejména pokud zatím nemáte žádné formální bezpečnostní postupy.

Mohu například:

- Probrat a zhodnotit základní architektonická rozhodnutí z pohledu bezpečnosti.
- Představit základy bezpečného programování pro technologie jako  
  **Java Spring Boot, REST API, SQL (PostgreSQL, MySQL, MSSQL, Oracle), Python,
  PHP (Laravel, Nette, Symfony, „raw“ PHP) a JavaScript (React.js)**.
- Pomoci vývojářům pochopit typické vektory útoku a jak jim předcházet ve vlastním kódu.
- Navrhnout jednoduché kontroly, které lze zařadit do vašeho stávajícího vývojového procesu.

Soustředím se na **praktická, postupná zlepšení**, která odpovídají vaší aktuální technologii
a úrovni vyspělosti - ne na zavádění těžkých „enterprise“ rámců jen kvůli formě.

---

### 3. Školení zaměstnanců a bezpečnostní povědomí (základy)

Mohu pro vaše zaměstnance připravit a vést úvodní školení zaměřené na základy bezpečnosti.
Je vhodné zejména pro organizace, které dosud neměly systematické školení v této oblasti.

Obsah může zahrnovat například:

- Základní bezpečnostní povědomí pro netechnické zaměstnance.
- Úvod do bezpečného programování a nejčastějších zranitelností pro vývojáře.
- Povědomí o phishingu, krádeži přihlašovacích údajů, práci s hesly a sociálním inženýrství.
- Školení přizpůsobené vašemu prostředí a technické úrovni účastníků.

Materiály vychází z reálných příkladů a ukázek, ale školení je vždy prezentováno jako
**úvodní**, ne jako vysoce expertní kurz.

---

## Ukázkové školení: Základy kybernetické bezpečnosti

Jedním z typických formátů, který mohu nabídnout, je **úvodní školení základů kybernetické
bezpečnosti pro zaměstnance**.  
Je vhodné pro organizace, které s bezpečnostním povědomím začínají a chtějí postupně budovat
základní bezpečnostní kulturu.

### Proč je vzdělávání v kybernetické bezpečnosti důležité

Moderní útoky často zneužívají:

- Nezaplátované zranitelnosti v široce používaném softwaru (např. starší protokoly, chyby v enginech prohlížečů).
- Slabá nebo opakovaně používaná hesla, která lze uhodnout, hrubou silou prolomit nebo získat z předchozích úniků.
- Phishingové kampaně, které uživatele přimějí k prozrazení přihlašovacích údajů nebo schválení škodlivé akce.
- Návrhové nebo implementační chyby v aplikacích či prohlížečových doplňcích.

I drobná chyba v konfiguraci nebo jedno nepozorné kliknutí může vést k vážným dopadům:
krádeži dat, ransomwaru, převzetí účtu nebo dlouhodobému skrytému přístupu do interních systémů.

### Příklady témat, která mohou být pokryta

- Jak jsou v praxi zneužívány kritické zranitelnosti (např. chyby na úrovni protokolů nebo 0‑day v prohlížečích).
- Proč je důležité včasné patchování a jak někdy **stačí jeden nezaplátovaný systém** k úspěšnému útoku.
- Jak nastavení politik hesel ovlivňuje obtížnost hrubé síly:
  - `N` = velikost abecedy  
  - `L` = délka hesla  
  - celkový počet kombinací = `N^L`
- Proč prodlužování hesla a přidávání znaků výrazně zvyšuje náročnost prolomení.
- Realistické phishingové scénáře a jak je rozpoznat a správně nahlásit.
- Jak správně používat AI LLM modely bez nutnosti strachu, že budou Vaše data ukradena

Během školení využívám **interně hostované ukázky**, na kterých je vidět útok jak
z pohledu útočníka, tak oběti. Typicky jde o:

- SQL injection proti záměrně zranitelné aplikaci.
- Offline crackování hesel pomocí volně dostupných nástrojů.
- Cross‑Site Scripting (XSS) a jeho dopad na krádež session či dat.
- Získání vzdáleného shellu na chybně nakonfigurovaném systému.
- Porovnání nezašifrovaného a TLS šifrovaného síťového provozu.

Z bezpečnostních důvodů tyto zranitelné systémy a ukázkové datové sady **nejsou
veřejně přístupné**. Udržuji je pouze lokálně v kontrolovaném prostředí a využívám je
výhradně pro školení a demonstrace.

---

## Jak útočníci přemýšlejí a pracují

Při školení i konzultacích kladu důraz na **pohled útočníka** - pochopení toho,
**jak** útočník přemýšlí a postupuje, pomáhá správně prioritizovat obranu.

Útočníci mohou usilovat o:

- Krádež citlivých dat (osobní údaje, přihlašovací údaje, duševní vlastnictví, finanční informace).
- Úpravu nebo zničení dat s cílem narušit provoz.
- Vydírání organizace pomocí ransomwaru nebo hrozby zveřejnění dat.
- Zpeněžení přístupu - prodejem, nebo využitím jako „odrazový můstek“ na další cíle.

První krok bývá získání **počátečního přístupu**. Mezi časté vstupní body patří:

- Phishingové e‑maily se škodlivými přílohami nebo odkazy.
- Skenování internetu a hledání zranitelných, špatně nakonfigurovaných nebo nezaplátovaných služeb.
- Zneužití zranitelných webových aplikací a API.
- Využití chybné konfigurace v cloudu nebo v interní infrastruktuře.

Reálné útoky jsou často vícestupňové a mohou probíhat týdny či měsíce. Moderní útočníci
se většinou vyhýbají „hlučným“ metodám, které by rychle odhalily firewally, WAF či
monitoring. Naopak se snaží být **nenápadní a perzistentní** po celou dobu, co mají přístup.

Na školeních a workshopech tyto principy ilustruji na **anonymizovaných příkladech**
a kontrolovaných laboratorních scénářích, aby účastníci lépe pochopili jak technické
detaily, tak širší souvislosti.

---

## Materiály a demonstrační prostředí

Pro školení a workshopy udržuji sadu interních materiálů, například:

- Slidy pro úvodní i mírně pokročilé publikum (základy kybernetické bezpečnosti, bezpečnost webových aplikací apod.).
- Krátká videa demonstrující běžné útoky (SQL injection, XSS, crackování hesel, reverse shell).
- Síťové záznamy ukazující rozdíl mezi nezašifrovaným a TLS šifrovaným provozem.
- Záměrně zranitelnou webovou aplikaci provozovanou v kontrolovaném sandboxu.

Tyto materiály **nejsou volně ke stažení**, slouží však jako součást školení při
prezenčních nebo online setkáních.

---

## Spolupráce

Pokud máte zájem například o:

- základní bezpečnostní pohled na vaše aplikace nebo infrastrukturu,  
- zlepšení bezpečných návyků vašeho vývojového týmu,  
- nebo uspořádání školení kybernetické bezpečnosti pro vaše zaměstnance,  

jsem otevřený **spolupráci formou menších konzultací a přizpůsobených workshopů**.

Můžeme společně projít vaši situaci, cíle a očekávání a domluvit
takovou formu spolupráce, která pro vaši organizaci dává největší smysl - s důrazem
na praktičnost a srozumitelnost, ne na nadbytečnou „enterprise“ administrativu.