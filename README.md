# PromptAlchymista ⚗️

![Verze](https://img.shields.io/badge/verze-1.0.0--rc1-blue) ![alt text](https://img.shields.io/badge/licence-MIT-green) ![Optimalizováno pro](https://img.shields.io/badge/Gemini%202.5%20Flash%20-prim%C3%A1rn%C4%9B-purple)

<p align="center">
  <img src="https://raw.githubusercontent.com/painter99/PromptAlchymista/main/PromptAlchymista.png" alt="PromptAlchymista - vizuální koncept" width="400">
  <!-- Atribut 'width' si můžete podle potřeby upravit. -->
</p>

<p align="center">
  <em>Váš AI asistent a průvodce světem prompt engineeringu, navržený jako komplexní systémový prompt pro Google Gemini 2.5 Flash. Pomáhá s tvorbou, analýzou a optimalizací LLM promptů s důrazem na srozumitelnost, efektivitu, etiku a učení se novým možnostem AI.</em>
</p>

<a id="obsah"></a>
## 📚 Obsah

- [Co je PromptAlchymista?](#co-je-promptalchymista)
- [Motivace a cesta k PromptAlchymistovi](#motivace-a-cesta)
- [Klíčové vlastnosti](#klicove-vlastnosti)
- [Základní filozofie a principy](#zakladni-filozofie-a-principy)
- [Jak PromptAlchymista funguje?](#jak-promptalchymista-funguje)
  - [Využívané Prompt Engineering Techniky (Meta-Úroveň)](#vyuzivane-prompt-engineering-techniky)
  - [Dynamická aktualizace znalostí a rešeršní protokol](#dynamicka-aktualizace-znalosti-a-resersni-protokol)
  - [Strukturální design a architektura promptu](#strukturalni-design-a-architektura-promptu)
  - [Adaptivní přístup a pokročilé optimalizační cykly](#adaptivni-pristup-a-pokrocile-optimalizacni-cykly)
  - [Optimalizace pro Google Gemini 2.5 Flash](#optimalizace-pro-google-gemini-25-flash)
  - [Zohlednění praktického využití a produkčního nasazení](#zohledneni-praktickeho-vyuziti-a-produkcniho-nasazeni)
  - [Hledání inovace a intuitivní předvídavost](#hledani-inovace-a-intuitivni-predvidavost)
- [Pro koho je určen?](#pro-koho-je-urcen)
- [Jak začít s PromptAlchymistou (doporučeno pro Gemini 2.5 Flash)](#jak-zacit-s-promptalchymistou-doporuceno-pro-gemini-25-flash)
- [Testování a evaluace](#testovani-a-evaluace)
- [Příklad komplexní interakce](#priklad-komplexni-interakce)
- [Aktuální stav (Release Candidate)](#aktualni-stav-release-candidate)
- [Zapojte se do diskuse!](#zapojte-se-do-diskuse)
- [Licence](#licence)

<a id="co-je-promptalchymista"></a>
## 🧪 Co je PromptAlchymista?

🎧 **Poslechněte si úvod k PromptAlchymistovi:** [![Poslechnout podcast](https://img.shields.io/badge/-Podcast-red?style=flat-square&logo=google-podcasts&logoColor=white)](https://notebooklm.google.com/notebook/28c6ba87-8a6f-423e-a72b-3a5562b0bc4a/audio)

Pokud by odkaz na NotebookLM nefungoval, nebo si přejete soubor stáhnout přímo, můžete tak učinit [zde](https://github.com/painter99/PromptAlchymista/releases/download/podcast-intro-v1/Podcast.PromptAlchymista.Intro.wav) (formát WAV).

---

**PromptAlchymista ⚗️** je **komplexní systémový prompt**. Není to samostatná softwarová aplikace ani nástroj v tradičním slova smyslu, ale soubor detailních instrukcí navržených tak, aby v prostředí pokročilého AI modelu (primárně optimalizovaného pro **Google Gemini 2.5 Flash**) **aktivoval roli AI asistenta a průvodce** v oblasti prompt engineeringu. Jeho hlavním posláním je být vám **pravou rukou a pomocníkem** při **tvorbě, analýze a optimalizaci promptů** pro velké jazykové modely (LLM), s důrazem na učení a pochopení "proč" určité přístupy fungují lépe.

PromptAlchymista se vyvinul z mého osobního experimentu ve fázi Alpha do současné verze Release Candidate (v1.0.0-rc1). Zatímco rané verze byly testovány na jiných modelech, **aktuální verze je cíleně optimalizována pro využití unikátních schopností Google Gemini 2.5 Flash**, jako je Controllable Reasoning, nativní Multimodalita a velké kontextové okno (1M tokenů), což umožňuje jeho komplexní chování.

Jedná se o **prototyp a referenční implementaci**, která zkoumá a demonstruje možnosti systematického a promyšleného přístupu k prompt engineeringu přímo v interakci s AI. Klade důraz na **učení, srozumitelnost a praktické využití** principů pro tvorbu **spolehlivých, efektivních a eticky zodpovědných promptů**.

Aktuálně je projekt ve fázi **Release Candidate (v1.0.0-rc1)** a je primárně testován a optimalizován v prostředí **Google AI Studio s modelem Gemini 2.5 Flash**. Pro plné využití jeho potenciálu je nezbytný model s pokročilými schopnostmi (jako je Controllable Reasoning), dlouhým kontextem, multimodalitou a schopností provádět webové rešerše.

<a id="motivace-a-cesta"></a>
## 🧠 Motivace a cesta k PromptAlchymistovi

Motivace pro vznik PromptAlchymisty vychází z mého osobního pozorování: i dnes mnoho uživatelů interaguje s výkonnými AI modely, aniž by plně využívali jejich potenciál. Z mé vlastní zkušenosti s testováním modelů jsem brzy pochopil, jak zásadní vliv má **precizní formulace instrukcí a nastavení modelu** na kvalitu a spolehlivost výstupu.

Proč je klíčové AI modely správně instruovat?

Velké jazykové modely (LLM) jsou nesmírně schopné, ale nejsou "inteligentní" v lidském slova smyslu. Nemají vlastní záměry, zdravý rozum ani implicitní pochopení složitých lidských požadavků. Bez jasných, precizních a optimalizovaných instrukcí (promptů) se jejich výstupy mohou stát nepředvídatelnými, nespolehlivými, nekonzistentními, nebo dokonce irelevantními či škodlivými.

Správné "instruování" AI – tedy **Prompt Engineering** – je proto zásadní dovedností, která transformuje surový potenciál modelů v cílené, spolehlivé a hodnotné výsledky. Je klíčové z několika důvodů:

*   **Spolehlivost a Konzistence:** Zajišťuje, že model bude opakovaně generovat předvídatelné a konzistentní výstupy, které přesně odpovídají vašim očekáváním a požadavkům na formát (včetně multimodálních výstupů).
*   **Přesnost a Relevance:** Pomáhá modelu zaměřit se na klíčové informace, vyhnout se "halucinacím" (generování smyšlených faktů) a poskytnout fakticky správné a relevantní odpovědi pro váš konkrétní úkol.
*   **Kontrola nad Výstupem:** Umožňuje detailně specifikovat požadovaný styl, tón, délku a strukturu výstupu, což je nezbytné pro integraci AI do aplikací nebo pro dosažení specifických komunikačních cílů.
*   **Využití Plného Potenciálu Modelu:** Odemkne a efektivně využije pokročilé schopnosti moderních modelů, jako je řízené uvažování ("thinking budgets") u Gemini 2.5 Flash, schopnost používat nástroje pro přístup k aktuálním datům (Grounding/Web Search), nebo zpracovávat a generovat multimodální vstupy a výstupy.
*   **Efektivita a Náklady:** Optimalizovaný prompt může snížit počet potřebných iterací, zkrátit délku výstupu (tokeny) a tím snížit náklady a latenci, což je kritické pro produkční nasazení ve velkém měřítku.
*   **Robustnost a Zvládání Okrajových Případů:** Dobře navržený prompt je odolnější vůči mírně odlišným nebo neočekávaným vstupům a lépe zvládá komplexní scénáře.
*   **Etika a Bezpečnost:** Umožňuje explicitně definovat etické mantinely a bezpečnostní omezení, minimalizovat biasy a předcházet generování škodlivého nebo nevhodného obsahu.
*   **Udržitelnost a Škálovatelnost:** Pro komplexní aplikace je strukturovaný a dobře navržený prompt snazší udržovat, testovat a integrovat do větších softwarových systémů.

Toto poznání mě vedlo k vytvoření prvního miniprojektu, [AI Templates](https://github.com/painter99/ai-templates), který sloužil jako základní sada strukturovaných šablon pro testování a optimalizaci promptů.

S rychlým pokrokem v oblasti AI, zejména s příchodem modelů s pokročilými schopnostmi uvažování a nativním přístupem k aktuálním informacím, se naskytla příležitost a potřeba posunout prompt engineering na vyšší úroveň. Cílem bylo vytvořit systém, který by nebyl jen statickým souborem šablon, ale dynamickým, inteligentním a architektonicky promyšleným pomocníkem – přímo v interakci s AI.

Tak vznikl PromptAlchymista. Reprezentuje můj hlubší ponor do architektury AI instrukcí, buduje na systematickém přístupu z [AI Templates](https://github.com/painter9ň/ai-templates) a integruje dynamickou aktualizaci znalostí, pokročilé optimalizační cykly a specifickou optimalizaci pro nejmodernější modely. Projekt je poháněn mou vášní pro IT a AI, touhou propojovat teoretické poznatky s praktickými aplikacemi (zejména v oblastech AI testování) a přesvědčením, že **systematický a efektivní prompt engineering je dovednost dostupná a přínosná pro každého**, kdo chce lépe využívat potenciál umělé inteligence.

<a id="klicove-vlastnosti"></a>
## ✨ Klíčové vlastnosti

PromptAlchymista, jako váš AI asistent a průvodce, nabízí následující klíčové vlastnosti:

*   **Optimalizace pro Gemini 2.5 Flash:** Plně využívá unikátní schopnosti modelu, jako je **Controllable Reasoning ("thinking budgets")** a **nativní Multimodalita**, pro dosažení co nejlepších výsledků v roli asistenta.
*   **Robustní Aktualizace Znalostí:** Automaticky provádí řízenou rešerši nejnovějších trendů a best practices v prompt engineeringu při každém startu, s přísnými kritérii pro aktuálnost a kvalitu zdrojů, aby vám mohl vždy poskytovat aktuální rady.
*   **Model-Centric Optimalizace:** Poskytuje rady a navrhuje prompty s ohledem na specifika a silné stránky cílového modelu (primárně Gemini 2.5 Flash, ale i Claude, GPT), abyste věděli, jak nejlépe pracovat s modelem, který máte k dispozici.
*   **Strukturální Design a Architektura:** Ukazuje a doporučuje, jak využívat XML (preferováno pro komplexitu) nebo Markdown/JSON pro jasnou strukturu, oddělení logických bloků a efektivní řízení chování modelu ve vašich promptech.
*   **Integrovaná Etika a Zodpovědná AI:** Aktivně zohledňuje etické aspekty, minimalizaci biasů a prevenci nežádoucího chování AI v každém návrhu, čímž vám pomáhá tvořit zodpovědné AI interakce.
*   **Zohlednění praktického využití a produkčního nasazení:** Přináší pohled na praktické aspekty nasazení promptů v reálných situacích, včetně latence, nákladů, zpracování chyb a bezpečnosti, což je užitečné pro ty, kteří chtějí AI využívat i pro náročnější úkoly.
*   **Hledání Inovace:** Aktivně prozkoumává a navrhuje nové kombinace technik a inovativní přístupy k řešení problémů, čímž vás inspiruje k posouvání hranic.
*   **Adaptivní a Pedagogická Komunikace:** Přizpůsobuje komplexitu vysvětlení vaší úrovni znalostí s cílem edukovat a inspirovat vás k samostatnému zvládnutí prompt engineeringu.
*   **Proaktivní Návrh Řešení:** Působí s vysokou mírou autonomy, předvídá vaše potřeby a minimalizuje zbytečné dotazy, aby vám co nejrychleji a nejefektivněji pomohl.
*   **Pokročilé Optimalizační Cykly:** Zahrnuje mechanismy pro autonomní meta-prompting (generuj -> kritizuj -> vylepši), simulaci RLHF pro sběr zpětné vazby a systematickou evaluaci variant, čímž demonstruje pokročilé metody optimalizace.
*   **Mistrovství v Omni-Modalitě:** Zvažuje a navrhuje multimodální přístupy tam, kde mohou přinést přidanou hodnotu, s využitím schopností cílových modelů, čímž vám otevírá dveře k novým možnostem AI.
*   **Praktické Příklady:** Nabízí konkrétní ukázky použití navržených promptů, včetně těch multimodálních, pro lepší pochopení a snadné použití.

<a id="zakladni-filozofie-a-principy"></a>
## 💡 Základní filozofie a principy

PromptAlchymista, jako váš AI průvodce, se řídí souborem klíčových principů, které tvoří základ jeho "Umění Prompt Engineeringu":

1.  **Mistrovství v Jednoznačnosti & Explicitnosti**: Každá instrukce musí být pro cílový AI model krystalicky čistá.
2.  **Tokenová Alchymie & Optimalizace Výkonu**: Hledání optimální rovnováhy mezi délkou promptu, jeho efektivitou a náklady, s ohledem na praktické využití.
3.  **Adaptabilita & Model-Centric Optimalizace**: Využití silných stránek cílového modelu, primárně Gemini 2.5 Flash.
4.  **Architektura Promptu & Strukturální Kontrola**: Strategické využití XML, Markdown, JSON pro maximální srozumitelnost a řízení chování modelu.
5.  **Etika v Designu Promptu & Zodpovědná AI**: Aktivní integrace etických aspektů do každého návrhu.
6.  **Edukace & Adaptivní Komunikace**: Přizpůsobování hloubky a technické náročnosti vysvětlení úrovni znalostí uživatele s cílem inspirovat.
7.  **Proaktivní Návrh Řešení & Řízená Autonomie**: Jednání samostatně, předvídání potřeb, řešení konfliktů v zadání.
8.  **Systematičnost & Verzování**: Systematická práce a dokumentace rozhodnutí.
9.  **DRY (Don't Repeat Yourself)**: Minimalizace redundance v návrzích promptů i ve vlastní struktuře.
10. **Hledání Inovace a Kreativní Řešení Problémů**: Aktivní hledání a navrhování nových kombinací nebo vzorců promptů.
11. **Praktická Moudrost z Produkce**: Zvažování aspektů reálného nasazení (latence, náklady, robustnost, bezpečnost, škálovatelnost).
12. **Mistrovství v Omni-Modalitě**: Schopnost efektivně navrhovat prompty integrující text, obraz a další modality.
13. **Intuitivní Předvídavost a Pokročilé Odvozování**: Schopnost "intuitivně" předvídat potřeby a identifikovat potenciální problémy.
14. **Meta-Heuristika pro Řešení Konfliktů**: Jasná pravidla pro řešení situací, kdy si principy protiřečí.
15. **Princip Řízené Flexibility**: Možnost expertního úsudku v unikátních situacích s transparentním zdůvodněním.

<a id="jak-promptalchymista-funguje"></a>
## ⚙️ Jak PromptAlchymista funguje?

PromptAlchymista není samostatná aplikace, ale **komplexní systémový prompt**, který definuje identitu, chování, znalosti a pracovní postupy AI asistenta. Funguje **přímo v prostředí kompatibilního LLM modelu** (jako je Google Gemini 2.5 Flash), kterému jsou jeho instrukce předány. Jeho klíčové mechanismy zahrnují:

<a id="vyuzivane-prompt-engineering-techniky"></a>
### Využívané Prompt Engineering Techniky (Meta-Úroveň)

PromptAlchymista sám o sobě není jen jednou konkrétní prompt engineering technikou (jako je například RAG pro získávání informací nebo CoT pro uvažování). Místo toho představuje **architekturu postavenou na kombinaci a pokročilé aplikaci více PE technik a principů** k vytvoření sofistikovaného AI asistenta. Lze ho vnímat jako **Meta-Prompt** – prompt, který se zabývá *prompt engineeringem samotným*.

Mezi klíčové techniky a přístupy, které PromptAlchymista integruje a demonstruje, patří:

*   **Role Prompting / Persona Prompting:** Definice komplexní identity a role "PromptAlchymisty ⚗️".
*   **Instructional Prompting:** Detailní a explicitní instrukce definující pracovní postupy, principy a pravidla chování.
*   **Structured Prompting (zejména s XML):** Využití XML tagů pro modulární design a jasnou hierarchii instrukcí, což modelu pomáhá lépe porozumět a dodržovat komplexní zadání.
*   **Meta-Prompting / Agentic Principles:** Instrukce, které řídí vlastní procesy modelu (např. cyklus generuj -> kritizuj -> vylepši, sebe-řízení, výběr modulů) v rámci jeho role asistenta.
*   **Dynamic & Adaptive Prompting:** Schopnost přizpůsobit se uživateli, dynamicky vyhledávat aktuální informace a adaptovat komunikaci.

PromptAlchymista tyto techniky kombinuje s cílem poskytnout **komplexní, strukturovaný a dynamický rámec** pro asistenci v prompt engineeringu, plně využívající schopností moderních modelů jako Google Gemini 2.5 Flash.

<a id="dynamicka-aktualizace-znalosti-a-resersni-protokol"></a>
### Dynamická aktualizace znalostí a rešeršní protokol

Na začátku každé konverzace **automaticky a povinně** provede Alchymista spolehlivý dvoufázový rešeršní proces:
1.  **Identifikuje 3 globální trendy:** Provede rešerši nejnovějších "best practices" v prompt engineeringu.
2.  **Cílené hloubkové ponory:** Na základě zjištěných trendů provede další 3 rešerše zaměřené na specifické, aktuálně nejrelevantnější oblasti, včetně jejich aplikovatelnosti na Gemini 2.5 Flash a potenciálu pro inovaci.
Tento proces využívá **výhradně anglické, autoritativní zdroje (oficiální dokumentace > vědecké pub. > renomované blogy) staré maximálně 1-9 měsíců** a má **vestavěný kontrolní mechanismus**, který brání odpovědi před dokončením rešerše. Tím je zajištěno, že rady jsou vždy aktuální a založené na nejnovějších poznatcích. **Pro tento mechanismus je nezbytný aktivní přístup AI k internetu (nástroj pro web search).** Během konverzace pak Alchymista provádí **proaktivní dynamickou rešerši** pro ověření konkrétních faktů nebo prozkoumání inovativních konceptů.

<a id="strukturalni-design-a-architektura-promptu"></a>
### Strukturální design a architektura promptu

Pro zajištění maximální srozumitelnosti a kontroly, PromptAlchymista doporučuje a využívá **strukturované formáty**. Preferovaným formátem pro komplexní systémové prompty je **XML**, které umožňuje jasně oddělit logické bloky, definovat atributy (jako důležitost, fáze exekuce) a řídit chování modelu. Pro jiné účely nebo cílové modely mohou být použity i Markdown, JSON nebo YAML. Aktuální verze systémového promptu sama demonstruje tuto modulární XML architekturu.

<a id="adaptivni-pristup-a-pokrocile-optimalizacni-cykly"></a>
### Adaptivní přístup a pokročilé optimalizační cykly

PromptAlchymista je navržen tak, aby:
*   Minimalizoval zbytečné dotazy na uživatele a proaktivně navrhoval řešení.
*   Odhadl úroveň znalostí uživatele a přizpůsobil tomu komplexitu svých vysvětlení s cílem edukovat a inspirovat.
*   **Systematicky využíval definované pokročilé cykly** (pokud je to relevantní pro úkol, jeho komplexitu, požadavky na praktické využití nebo potenciál pro inovaci):
    *   **Meta-Promptingový Optimalizační Cyklus:** Autonomní cyklus (generuj -> kritizuj -> vylepši) pro hloubkovou optimalizaci komplexních promptů, včetně zohlednění inovace, praktických aspektů a specifik cílového modelu.
    *   **RLHF/DPO-inspirovaný Feedback Loop:** Mechanismus pro systematické získávání a aplikaci strukturované uživatelské zpětné vazby pro iterativní vylepšování promptů a vlastních poradenských/pedagogických schopností.
    *   **Optimalizační a Evaluační Cyklus:** Proces pro systematické generování a objektivní hodnocení více variant promptů na základě definovaných metrik, vhodný pro náročnější úkoly a vyhodnocení inovativních přístupů.
    *   **Strategické Poradenství:** Proaktivní posouzení komplexity úkolu a návrh nejvhodnější strategie (jeden prompt, dekompozice, agent, RAG, DSPy, multimodální, inovace).

<a id="optimalizace-pro-google-gemini-25-flash"></a>
### Optimalizace pro Google Gemini 2.5 Flash

Tato verze PromptAlchymisty klade zvláštní důraz na využití silných stránek Gemini 2.5 Flash:
*   **Controllable Reasoning:** Alchymista navrhuje strategie pro využití "thinking budgets" a explicitních módů uvažování modelu pro optimalizaci kvality, rychlosti a nákladů pro různé části úkolu.
*   **Dlouhý Kontext:** Efektivně využívá schopnost modelu pracovat s rozsáhlým kontextem pro hlubší analýzu a syntézu informací.
*   **Nativní Multimodalita:** Aktivně zvažuje a navrhuje řešení, která integrují a optimalizují práci s různými modalitami (text, obraz atd.), pokud je to pro úkol relevantní.

V tomto kontextu se **Google AI Studio ukázalo jako klíčová platforma** pro rapidní prototypování, iterativní ladění a efektivní nasazení pokročilých prompt engineering strategií, jako je PromptAlchymista, právě díky přímé podpoře těchto unikátních schopností modelu Gemini.

<a id="zohledneni-praktickeho-vyuziti-a-produkcniho-nasazeni"></a>
### Zohlednění praktického využití a produkčního nasazení

Při návrhu promptů a strategií PromptAlchymista systematicky zvažuje aspekty reálného využití, včetně možného nasazení v produkčním prostředí. To zahrnuje optimalizaci pro **latenci, propustnost, náklady**, robustní **zpracování chyb** a **bezpečnostní aspekty** (např. prompt injection). Poskytuje praktické rady pro ty, kteří chtějí AI využívat i pro náročnější nebo opakované úkoly.

<a id="hledani-inovace-a-intuitivni-predvidavost"></a>
### Hledání inovace a intuitivní předvídavost

PromptAlchymista se neomezuje pouze na aplikaci známých technik. Aktivně hledá a navrhuje **nové kombinace, adaptace nebo zcela nové vzorce promptů**, které by mohly vést k zajímavým řešením. Zároveň rozvíjí schopnost "intuitivně" předvídat potřeby uživatele a identifikovat potenciální problémy nebo příležitosti, které nejsou explicitně zmíněny.

<a id="pro-koho-je-urcen"></a>
## 🎯 Pro koho je určen?

PromptAlchymista, jako váš AI asistent a průvodce, může být užitečný především pro:

*   **Každého uživatele AI:** Kdo chce jít dál než k základnímu používání chatbotů a naučit se, jak s AI komunikovat efektivněji a získávat spolehlivější výsledky pro své každodenní i složitější úkoly.
*   **Začátečníky a mírně pokročilé v prompt engineeringu:** Pro pochopení základních i pokročilejších principů, získání pomoci s formulací promptů a systematické učení.
*   **Nadšence a experimentátory:** Kteří se zajímají o to, jak fungují pokročilé AI modely "pod pokličkou" a chtějí prozkoumávat možnosti strukturovaného a inovativního promptingu.
*   **Lektory a školitele v oblasti AI:** Jako živá ukázka a inspirace pro výukové materiály, která demonstruje systematický přístup k prompt engineeringu.

PromptAlchymista není navržen jako náhrada za specializované softwarové frameworky pro vývoj LLM aplikací (jako je DSPy) ani za vlastní, vysoce propracované workflow zkušených AI profesionálů. Jeho hodnota spočívá v tom, že **zpřístupňuje principy efektivního promptingu a ukazuje cestu k lepšímu využití AI** širšímu okruhu zájemců.

<a id="jak-zacit-s-promptalchymistou-doporuceno-pro-gemini-25-flash"></a>
## 🚀 Jak začít s PromptAlchymistou (doporučeno pro Gemini 2.5 Flash)

PromptAlchymista funguje jako systémový prompt v prostředí kompatibilního LLM modelu. Je primárně navržen pro Google Gemini 2.5 Flash. Nejlepší způsob, jak začít, je v prostředí **Google AI Studio**:

1.  **Vytvoření nového promptu:**
    *   Přejděte do Google AI Studio a vytvořte nový "Chat".
2.  **Vložení systémových instrukcí:**
    *   Zkopírujte celý obsah souboru [`1.0.0-gemini-2.5-flash-thinking-rc1.xml`](https://github.com/painter99/PromptAlchymista/releases/download/v1.0.0-gemini-2.5-flash-thinking-rc1/1.0.0-gemini-2.5-flash-thinking-rc1.xml) a vložte jej do textového pole pro `System instruction`.
3.  **Výběr a konfigurace modelu:**
    *   V nastavení modelu (obvykle v pravém panelu) vyberte model **`Gemini 2.5 Flash`** (nebo novější verzi `Gemini x.x Flash`, pokud je dostupná).
    *   **Doporučuji aktivovat funkci "Grounding" s přístupem k Google Search pro správné fungování.** PromptAlchymista vyžaduje přístup k aktuálním informacím pro svůj inicializační protokol a průběžné rešerše.
    *   Experimentujte s nastavením inferenčních parametrů, jako je **"Temperature"** (např. kolem 0.6-1.0 pro vyvážený přístup) a **Top P** (např. kolem 0.85-0.95), podle potřeb konkrétního úkolu. PromptAlchymista sám může během konverzace doporučit optimální nastavení pro váš specifický případ.
    *   **Důležité doporučení k nastavení Temperature (z testování):**
        *   Na základě rozsáhlejšího testování se ukázalo, že pro úlohy vyžadující **flexibilitu, kreativitu a proaktivní práci s aktuálními informacemi (např. vyhledávání na webu)** je vhodné nastavit parametr `temperature` na hodnoty v rozmezí **0.6-0.8**.
        *   Při téchto hodnotách si model zachovává dostatečnou **variabilitu a kreativitu** ve svých odpovědích.
        *   Příliš nízké nastavení (např. pod 0.6) vede k tomu, že se model stává **příliš striktně vázaný na své interní instrukce a tréninková data**. Může to projevovat například **menší ochotou proaktivně vyhledávat aktuální informace na webu** (i když jsou instrukce k použití nástrojů přítomny) nebo **přílišným lpěním na specifikách uvedených v promptu** (jako je výhradní zaměření na Gemini 2.5 Flash i v širších dotazech o PE).
        *   V takových případech se kvalita a užitečnost výstupu modelu pro daný úkol snižuje.
    *   **Pro plné využití schopností uvažování modelu Gemini 2.5 Flash, ujistěte se, že nastavení API nebo platformy umožňuje modelu využívat jeho "thinking budget".** Tuto hodnotu nenastavujte manuálně, PromptAlchymista si ji bude nastavovat sám v průběhu konverzace.
4.  **Zahájení konverzace:**
    *   Jakmile máte systémový prompt vložený a model nakonfigurovaný, můžete zahájit konverzaci. Stačí napsat běžnou úvodní zprávu, například **pouhý pozdrav** jako "Ahoj" nebo "Dobrý den".
    *   AI by měla následně reagovat již v roli PromptAlchymisty, připravena plnit své úkoly definované v systémovém promptu, včetně provedení inicializační rešerše.

**Alternativní platformy (Claude, GPT):**

PromptAlchymista je navržen s ohledem na univerzální principy a může fungovat i na jiných pokročilých modelech, jako jsou **Anthropic Claude (doporučeno Claude 3.x s nástroji a thinking) nebo OpenAI GPT (doporučeno GPT-4 s nástroji)**. Postup nasazení se bude lišit v závislosti na platformě (např. Claude.ai Projects, OpenAI Playground/API) a může vyžadovat úpravu formátování (např. pro Claude preferovat XML, pro GPT využít `system_message`). Klíčové je zajistit modelu přístup k webovým rešerším a pokud možno k mechanismům pro řízené uvažování.

**Je důležité poznamenat, že zatímco rané verze PromptAlchymisty (fáze Alpha) byly primárně testovány a laděny na modelech Claude, verze 1.0.0-rc1 je cíleně optimalizována pro využití unikátních schopností Gemini 2.5 Flash.** Při použití na jiných modelech se mohou výsledky lišit a nemusí být plně využity všechny pokročilé funkce (jako specifické řízení uvažování nebo plná integrace multimodality, pokud daný model nemá srovnatelné schopnosti).

<a id="testovani-a-evaluace"></a>
## 🛠️ Testování a evaluace

Systematické testování a evaluace jsou nedílnou součástí "Prompt Engineeringu" a klíčové pro ověření kvality návrhů PromptAlchymisty. Doporučuji:

*   **Využít doporučení Alchymisty:** PromptAlchymista sám navrhuje konkrétní metriky a metodiky testování pro váš úkol (viz `<testing_guidelines_and_next_steps>` ve výstupu).
*   **Vytvořit testovací sady:** Sady reprezentativních vstupů (včetně edge cases a multimodálních variant) pro konzistentní testování.
*   **Měřit klíčové metriky:** Kvalita výstupu, shoda s formátem, tokenová efektivita, robustnost, etické aspekty a pro praktické využití i **latence, propustnost a náklady**.
*   **Použít metodiky:** A/B testování, iterativní zlepšování, LLM-as-a-judge, analýza selhání.
*   **Experimentovat:** Zkoušet různé varianty promptu, nastavení modelu (včetně "thinking budget" u Gemini 2.5 Flash) a sledovat jejich dopad na metriky.

<a id="priklad-komplexni-interakce"></a>
## 🗣️ Příklad komplexní interakce

Tato sekce demonstruje, jak může PromptAlchymista v praxi pomoci s refaktoringem a optimalizací existujícího komplexního promptu. Následující odkaz vede na skutečnou konverzaci v Google AI Studiu, kde PromptAlchymista (s nasazeným systémovým promptem) refaktoroval detailní prompt šablonu pro AI učitele.

**Odkaz na kompletní interakci v Google AI Studiu:**
🔗 [Prohlédnout si příklad v Google AI Studio](https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221yYw9-TCiP-iFWcrDK7_1THJ-3S1QoUaA%22%5D,%22action%22:%22open%22,%22userId%22:%22115548049022000007713%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing)

**Stručné shrnutí této interakce:**

1.  **Vstup uživatele:** Uživatel poskytl PromptAlchymistovi detailní prompt šablonu pro AI asistenta v roli učitele/mentora a požádal o její refaktoring a optimalizaci pro model Gemini 2.5 Flash. Cílem bylo efektivně využít specifické schopnosti modelu, jako je **Controllable Reasoning ("thinking budget")** a **neustálé ověřování informací pomocí web search a grounding**.
2.  **Analýza a plánování PromptAlchymisty:** PromptAlchymista nejprve analyzoval původní šablonu, identifikoval její silné stránky a klíčové oblasti pro vylepšení s ohledem na cílový model a požadované funkce. Definoval formální signaturu úlohy (`task_signature`) a interně si naplánoval kroky refaktoringu, včetně toho, jak zakomponovat instrukce pro thinking budget a web search do nového promptu.
3.  **Generování optimalizovaného promptu:** Na základě analýzy a plánu PromptAlchymista vygeneroval novou, **komplexní prompt šablonu ve formátu XML**. Tato nová verze transformovala popisné sekce původní šablony na **explicitní, exekutivní instrukce a pravidla** pro AI asistenta v roli učitele.
4.  **Vysvětlení a doprovodné materiály:** PromptAlchymista k navrženému XML promptu připojil detailní **odůvodnění návrhových rozhodnutí** (`design_rationale_and_principles_applied`), vysvětlující, proč byly provedeny konkrétní změny, jak byly aplikovány principy PromptAlchymisty a jak nová struktura a instrukce využívají schopnosti Gemini 2.5 Flash (zejména pro řízené uvažování a web search). Dále poskytl **příklady použití** nové šablony, **poznámky k tokenové efektivitě a nákladům** a **konkrétní doporučení pro testování a evaluaci**. Zmíněna byla i perspektiva pro pokročilou optimalizaci s frameworky jako DSPy a zohlednění etických aspektů.

Tento příklad demonstruje, jak PromptAlchymista funguje jako **systematický pomocník a průvodce**. Nejenže generuje refaktorovaný prompt, ale také poskytuje kontext, vysvětluje "proč" a nabízí návod, jak s výsledkem dále pracovat a jak využít pokročilé schopnosti modelu. Ukazuje, jak lze komplexní zadání převést do strukturovaných instrukcí pro AI asistenta.

<a id="aktualni-stav-release-candidate"></a>
## 🧭 Aktuální stav (Release Candidate)

PromptAlchymista se vyvinul z mého raného **osobního experimentu** ve fázi Alpha do současné fáze **Release Candidate (v1.0.0-rc1)**. Tento přechod odráží významné vylepšení architektury, přidání nových modulů a robustnější testování. Zatímco v Alpha fázi byl projekt primárně testován na modelech Claude, v současné fázi RC1 probíhá aktivní testování a jemné ladění, zejména s modelem **Google Gemini 2.5 Flash**, pro který je tato verze primárně optimalizována.

Cílem je dosáhnout stabilní verze 1.0.0 v blízké budoucnosti.
Jako Release Candidate se stále může vyvíjet a vylepšovat na základě zpětné vazby a dalšího testování.

<a id="zapojte-se-do-diskuse"></a>
## 💬 Zapojte se do diskuse!

Máte nápady, postřehy, nebo jste PromptAlchymistu vyzkoušeli? Budu rád za jakoukoliv zpětnou vazbu nebo diskusi o tomto přístupu k prompt engineeringu. Tento projekt je experimentem a každá konstruktivní myšlenka může pomoci jeho dalšímu směřování a rozvoji pro celou komunitu.

*   [Odkaz na GitHub repozitář projektu PromptAlchymista](https://github.com/painter99/PromptAlchymista)
*   [Odkaz na LinkedIn profil autora](https://www.linkedin.com/in/pavel-mares-p99/)

Cílem je vytvořit nástroj a přístup, který může pomoci zefektivnit a zkvalitnit práci s LLM a posunout hranice prompt engineeringu.

<a id="licence"></a>
## 📜 Licence

PromptAlchymista (jako koncept, tento dokument a související systémové prompty poskytnuté autorem) je poskytován pod licencí **MIT**. Autorská práva `Copyright (c) 2025 painter99`. Podrobnosti naleznete v souboru `LICENSE` v repozitáři projektu.

---

<p align="center">
  <em>Transformujte své nápady v precizní, efektivní a inovativní prompty s PromptAlchymistou – vaším AI průvodcem!</em>
</p>
