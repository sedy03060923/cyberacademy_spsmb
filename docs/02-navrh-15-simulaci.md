# Bod 2 – Návrh 15 interaktivních simulací

**Projekt:** CyberAcademy – RP 43  
**Termín podle zadání:** 20. 11. 2026

## Jak chci simulace udělat

Připravil jsem 15 situací rozdělených do pěti kapitol. Nechci je udělat jako obyčejný test. Každá bude mít vlastní obrazovku, která bude připomínat skutečný e-mail, webovou stránku, chat, nastavení účtu nebo telefon.

Hráč si bude moct kliknout na konkrétní věc a hned uvidí, kam by ho to zavedlo. Například podezřelý odkaz otevře další krok simulace – falešné přihlášení. Když potom odešle **pouze předem připravené testovací údaje**, zobrazí se následek a vysvětlení. Při bezpečné volbě se zase ukáže správný postup.

Všechno poběží jen uvnitř aplikace. Pro falešné stránky používám smyšlené adresy a do simulací se nebudou psát skutečná hesla, čísla karet ani jiné citlivé údaje.

## Přehled všech misí

| # | Kapitola | Název mise |
|---:|---|---|
| 1 | 1 | Podezřelý školní e-mail |
| 2 | 1 | Falešné doručení balíku |
| 3 | 1 | Nebezpečná e-mailová příloha |
| 4 | 2 | Falešný internetový obchod |
| 5 | 2 | Podvržená přihlašovací stránka |
| 6 | 2 | Podezřelá platební brána |
| 7 | 3 | Falešná výhra na Instagramu |
| 8 | 3 | Podvodná SMS od banky |
| 9 | 3 | Zpráva od napadeného kamaráda |
| 10 | 4 | Výběr bezpečného hesla |
| 11 | 4 | Dvoufázové ověření |
| 12 | 4 | Podezřelé přihlášení k účtu |
| 13 | 5 | Nezabezpečená veřejná Wi-Fi |
| 14 | 5 | Stažení neznámého programu |
| 15 | 5 | Sdílení osobních údajů |

## Kapitola 1 – Phishing a nebezpečné e-maily

Cíl kapitoly: Naučit se poznat podvodný e-mail, kontrolovat odesílatele a nerozesílat svoje údaje.

### Mise 1 – Podezřelý školní e-mail

**Situace:** Ve školní poště mi přijde zpráva, že se mi za 24 hodin zablokuje účet.

**Co hráč uvidí:** E-mailová schránka s odesílatelem, předmětem a tlačítkem pro ověření účtu. Na obrazovce bude zpráva: „Váš školní účet bude za 24 hodin zablokován. Ověřte ho přes odkaz ve zprávě.“

**Co může udělat:**

- Bezpečně: zkontrolovat odesílatele a ověřit zprávu přes školní systém.
- Rizikově: kliknout na odkaz a vyplnit testovací heslo.

**Co se stane po rizikovém kliknutí:** Zobrazí se napodobenina školního přihlášení. Po odeslání testovacích údajů hra ukáže, že je mohl získat útočník.

**Správný postup:** Hráč nevyplní heslo, zprávu ověří jinou cestou a případně ji nahlásí.

**Na co si má dát pozor:** Cizí doména odesílatele, časový nátlak, výzva k zadání hesla.

**Přechod obrazovek:** E-mail → falešné přihlášení → výsledek.

### Mise 2 – Falešné doručení balíku

**Situace:** Přijde e-mail, že balík čeká na doručení, ale je potřeba zaplatit malý poplatek.

**Co hráč uvidí:** E-mail podobný zprávě od dopravce a odkaz na sledování zásilky. Na obrazovce bude zpráva: „Doručení se nezdařilo. Pro opakované doručení zaplaťte 39 Kč.“

**Co může udělat:**

- Bezpečně: ověřit zásilku přímo na oficiálním webu dopravce.
- Rizikově: otevřít platbu z e-mailu a zadat testovací údaje ke kartě.

**Co se stane po rizikovém kliknutí:** Otevře se falešná platební stránka a simulace vysvětlí riziko zneužití platebních údajů.

**Správný postup:** Hráč použije vlastní odkaz na dopravce nebo aplikaci dopravce, ne odkaz v podezřelé zprávě.

**Na co si má dát pozor:** Nejasný dopravce, nečekaný poplatek, podezřelá adresa a nátlak.

**Přechod obrazovek:** E-mail dopravce → falešná platba → důsledek.

### Mise 3 – Nebezpečná e-mailová příloha

**Situace:** Neznámý odesílatel posílá soubor označený jako faktura nebo důležitý dokument.

**Co hráč uvidí:** E-mail s přílohou „faktura.zip“ a tlačítky stáhnout a ověřit. Na obrazovce bude zpráva: „V příloze zasíláme důležitou fakturu. Otevřete ji ještě dnes.“

**Co může udělat:**

- Bezpečně: ověřit odesílatele a přílohu neotevírat.
- Rizikově: stáhnout a spustit neznámý soubor.

**Co se stane po rizikovém kliknutí:** Simulace ukáže možné spuštění škodlivého programu a nabídne bezpečný další postup.

**Správný postup:** Hráč si ověří, zda dokument očekává, a nepovolí spuštění neznámého souboru.

**Na co si má dát pozor:** Nečekaná příloha, archivovaný soubor, neurčitý odesílatel.

**Přechod obrazovek:** Pošta → dialog přílohy → varování.

## Kapitola 2 – Falešné weby a internetové podvody

Cíl kapitoly: Zkontrolovat webovou adresu, důvěryhodnost obchodu a bezpečně platit na internetu.

### Mise 4 – Falešný internetový obchod

**Situace:** Najdu e-shop s herní konzolí za podezřele nízkou cenu.

**Co hráč uvidí:** Ukázková stránka obchodu s produktem, košíkem a informacemi o prodejci. Na obrazovce bude zpráva: „Herní konzole se slevou 80 %. Poslední kusy. Kup hned.“

**Co může udělat:**

- Bezpečně: prověřit obchod, kontakty a nezávislé recenze.
- Rizikově: přejít do pokladny a zaplatit bez ověření obchodu.

**Co se stane po rizikovém kliknutí:** Simulace upozorní na možnost ztráty peněz nebo zneužití platebních údajů.

**Správný postup:** Hráč si nejprve ověří provozovatele a důvěryhodnost stránky.

**Na co si má dát pozor:** Podezřele nízká cena, chybějící kontakty, velký časový tlak.

**Přechod obrazovek:** Produkt → košík → pokladna → výsledek.

### Mise 5 – Podvržená přihlašovací stránka

**Situace:** Po kliknutí na odkaz se otevře stránka podobná známé službě.

**Co hráč uvidí:** Okno prohlížeče s adresním řádkem a přihlašovacím formulářem. Na obrazovce bude zpráva: „Pro pokračování zadej e-mail a heslo do účtu.“

**Co může udělat:**

- Bezpečně: porovnat doménu a otevřít službu přes známou adresu.
- Rizikově: odeslat testovací přihlašovací údaje do formuláře.

**Co se stane po rizikovém kliknutí:** Hra ukáže, jak falešná stránka může odchytit přihlašovací údaje.

**Správný postup:** Hráč pozná, že vzhled stránky nestačí, a ověří URL.

**Na co si má dát pozor:** Podobný design jako originál, ale jiné doménové jméno.

**Přechod obrazovek:** Prohlížeč → formulář → vysvětlení.

### Mise 6 – Podezřelá platební brána

**Situace:** Při objednávce mě e-shop přesměruje na neznámou stránku s požadavkem na platbu.

**Co hráč uvidí:** Nákupní košík a napodobenina platební brány s testovacími políčky. Na obrazovce bude zpráva: „Pro dokončení objednávky vyplňte údaje o kartě.“

**Co může udělat:**

- Bezpečně: zastavit platbu a ověřit platební stránku.
- Rizikově: pokračovat a odeslat modelové údaje o kartě.

**Co se stane po rizikovém kliknutí:** Simulace ukáže riziko úniku platebních údajů a nutnost ověřit poskytovatele platby.

**Správný postup:** Hráč nevyplňuje citlivé údaje na neověřené stránce.

**Na co si má dát pozor:** Nečekaná doména, nesoulad s obchodem, nejasné údaje o platbě.

**Přechod obrazovek:** Košík → platební stránka → výsledek.

## Kapitola 3 – Podvodné zprávy a sociální sítě

Cíl kapitoly: Nenechat se zmanipulovat zprávou nebo naléhavou žádostí od neznámého účtu.

### Mise 7 – Falešná výhra na Instagramu

**Situace:** V soukromé zprávě mi přijde informace, že jsem vyhrál hodnotnou cenu.

**Co hráč uvidí:** Simulované zprávy sociální sítě s odkazem na převzetí ceny. Na obrazovce bude zpráva: „Gratulujeme! Vyhráváš telefon. Potvrď svoji výhru přes odkaz.“

**Co může udělat:**

- Bezpečně: zkontrolovat profil a soutěž, zprávu nahlásit.
- Rizikově: kliknout na odkaz a zadat osobní údaje.

**Co se stane po rizikovém kliknutí:** Hra vysvětlí, jak podvodník získává informace nebo peníze za falešné doručení.

**Správný postup:** Hráč si ověří soutěž a neposkytne údaje neověřenému profilu.

**Na co si má dát pozor:** Nečekaná výhra, kopie známého účtu, požadavek na údaje.

**Přechod obrazovek:** Soukromá zpráva → formulář výhry → výsledek.

### Mise 8 – Podvodná SMS od banky

**Situace:** SMS tvrdí, že mám zablokovaný bankovní účet a musím rychle reagovat.

**Co hráč uvidí:** Simulovaný telefon se SMS zprávou a odkazem. Na obrazovce bude zpráva: „Váš účet byl dočasně omezen. Obnovte přístup ihned.“

**Co může udělat:**

- Bezpečně: otevřít bankovní aplikaci samostatně a ověřit stav účtu.
- Rizikově: kliknout na odkaz ze sms a vyplnit údaje.

**Co se stane po rizikovém kliknutí:** Vysvětlení rizika podvodného přihlášení a ztráty peněz.

**Správný postup:** Hráč nekoná podle nátlakové SMS a situaci ověří přes oficiální kanál.

**Na co si má dát pozor:** Naléhavost, cizí odkaz, obecné oslovení.

**Přechod obrazovek:** SMS → falešné bankovnictví → důsledek.

### Mise 9 – Zpráva od napadeného kamaráda

**Situace:** Účet spolužáka mi píše, že hned potřebuje půjčit peníze.

**Co hráč uvidí:** Chat se známým kontaktem a žádostí o převod. Na obrazovce bude zpráva: „Ahoj, nutně mi pošli 1 000 Kč, večer vrátím. Teď nemůžu volat.“

**Co může udělat:**

- Bezpečně: zavolat kamarádovi nebo se ho zeptat osobně.
- Rizikově: poslat peníze bez dalšího ověření.

**Co se stane po rizikovém kliknutí:** Simulace ukáže, že účet mohl být převzat útočníkem a peníze by odešly jemu.

**Správný postup:** Hráč ověří skutečnou totožnost odesílatele jiným způsobem.

**Na co si má dát pozor:** Neobvyklý styl zprávy, naléhání, odmítnutí hovoru.

**Přechod obrazovek:** Chat → žádost o převod → výsledek.

## Kapitola 4 – Ochrana účtů a hesel

Cíl kapitoly: Používat bezpečná hesla, vícefaktorové ověření a reagovat na podezřelé přístupy.

### Mise 10 – Výběr bezpečného hesla

**Situace:** Při založení účtu si mám nastavit nové heslo.

**Co hráč uvidí:** Ukázkový formulář registrace a porovnání tří hesel. Na obrazovce bude zpráva: „Vyber bezpečné heslo pro svůj nový účet.“

**Co může udělat:**

- Bezpečně: zvolit dlouhé jedinečné heslo nebo heslovou frázi.
- Rizikově: použít jednoduché nebo opakovaně používané heslo.

**Co se stane po rizikovém kliknutí:** Hra ukáže, proč se běžné heslo snáz uhodne a proč opakování ohrožuje více účtů.

**Správný postup:** Hráč použije jedinečné a dostatečně dlouhé heslo.

**Na co si má dát pozor:** Krátká hesla, osobní údaje, opakování hesel.

**Přechod obrazovek:** Registrace → výběr hesla → bezpečnostní vysvětlení.

### Mise 11 – Dvoufázové ověření

**Situace:** Na telefonu dostanu žádost o potvrzení přihlášení, které jsem nezačal.

**Co hráč uvidí:** Přihlašovací obrazovka a mobilní oznámení o potvrzení. Na obrazovce bude zpráva: „Schválit přihlášení z nového zařízení?“

**Co může udělat:**

- Bezpečně: zamítnout neočekávanou žádost a prověřit účet.
- Rizikově: schválit žádost jen proto, aby zmizela.

**Co se stane po rizikovém kliknutí:** Hra ukáže, že útočník by mohl dokončit přihlášení, pokud má i další potřebné údaje.

**Správný postup:** Hráč schvaluje jen vlastní pokusy o přihlášení.

**Na co si má dát pozor:** Neznámé zařízení, nečekaná notifikace.

**Přechod obrazovek:** Oznámení 2FA → schválit/zamítnout → důsledek.

### Mise 12 – Podezřelé přihlášení k účtu

**Situace:** Služba mě upozorní na přihlášení z neznámého místa.

**Co hráč uvidí:** Bezpečnostní centrum účtu se seznamem zařízení. Na obrazovce bude zpráva: „Nové přihlášení k účtu z neznámého zařízení.“

**Co může udělat:**

- Bezpečně: zkontrolovat relace, změnit heslo a odhlásit neznámé zařízení.
- Rizikově: ignorovat upozornění bez ověření.

**Co se stane po rizikovém kliknutí:** Hra vysvětlí, že cizí přístup může zůstat aktivní.

**Správný postup:** Hráč provede kontrolu účtu přes oficiální službu.

**Na co si má dát pozor:** Neznámé zařízení a nečekaná aktivita.

**Přechod obrazovek:** Bezpečnostní centrum → správa zařízení → výsledek.

## Kapitola 5 – Bezpečnost zařízení a soukromí

Cíl kapitoly: Chránit zařízení a soukromí při používání internetu.

### Mise 13 – Nezabezpečená veřejná Wi-Fi

**Situace:** V kavárně se potřebuji připojit k internetu a vidím několik podobných sítí.

**Co hráč uvidí:** Seznam dostupných Wi-Fi sítí a okno pro připojení. Na obrazovce bude zpráva: „Vyber síť Wi-Fi, přes kterou se připojíš.“

**Co může udělat:**

- Bezpečně: ověřit název sítě a používat zabezpečené připojení.
- Rizikově: připojit se k podezřelé síti a zadat údaje na neověřené stránce.

**Co se stane po rizikovém kliknutí:** Simulace názorně vysvětlí možné riziko falešného hotspotu a podvodného přihlášení.

**Správný postup:** Hráč ověří síť a nevyplňuje citlivé údaje do neznámých formulářů.

**Na co si má dát pozor:** Dvě podobné sítě, nečekaná přihlašovací obrazovka.

**Přechod obrazovek:** Seznam Wi-Fi → připojení → výsledek.

### Mise 14 – Stažení neznámého programu

**Situace:** Na stránce se nabízí placený program zdarma z neoficiálního zdroje.

**Co hráč uvidí:** Stránka ke stažení souboru a systémové upozornění. Na obrazovce bude zpráva: „Plná verze zdarma. Stáhni soubor a hned ho spusť.“

**Co může udělat:**

- Bezpečně: použít oficiální stránku autora a zkontrolovat stažený soubor.
- Rizikově: spustit neověřený instalační soubor.

**Co se stane po rizikovém kliknutí:** Hra ukáže možné následky, například instalaci nežádoucího softwaru.

**Správný postup:** Hráč nestahuje programy z neznámých stránek.

**Na co si má dát pozor:** Neoficiální zdroj, slib zdarma, požadavek na spuštění souboru.

**Přechod obrazovek:** Web → stažení → upozornění → důsledek.

### Mise 15 – Sdílení osobních údajů

**Situace:** Soutěžní formulář požaduje adresu, datum narození a další zbytečné údaje.

**Co hráč uvidí:** Ukázkový formulář pro registraci do soutěže. Na obrazovce bude zpráva: „Vyplň všechna pole a získej šanci vyhrát.“

**Co může udělat:**

- Bezpečně: zvážit, jaké údaje jsou nutné, a formulář odmítnout.
- Rizikově: odeslat všechny požadované testovací údaje.

**Co se stane po rizikovém kliknutí:** Hra vysvětlí riziko zneužití osobních informací a cílených podvodů.

**Správný postup:** Hráč nesdílí nadbytečné osobní údaje.

**Na co si má dát pozor:** Nesouvisející osobní informace, nejasný pořadatel, chybějící pravidla.

**Přechod obrazovek:** Formulář → odeslání → vysvětlení.

## Co bude mít každá mise společné

- **Úvod:** hráč krátce zjistí, do jaké situace se dostal.
- **Simulované prostředí:** e-mail, web, zpráva, přihlášení nebo nastavení zařízení.
- **Klikací volby:** hráč se rozhodne přímo v prostředí; nebude odpovídat jen na otázku A/B/C.
- **Následek:** po kliknutí se změní obrazovka a ukáže se, co by se mohlo stát.
- **Vysvětlení:** hráč dostane konkrétní důvody, proč byla volba bezpečná nebo riziková.
- **Opakování:** v hotové verzi půjde misi zopakovat, zvlášť když hráč udělal chybu.

## Co už je hotové a co budu dělat dál

V této etapě mám **vymyšlené a popsané všechny scénáře** a ve složce `navrh` je klikací náhled jejich základního principu. Zatím to není všech 15 kompletně naprogramovaných herních misí. Detailní interakce, důsledky rozhodnutí, bodování, ukládání a testování budu vytvářet postupně v bodech 3–10 podle harmonogramu.
