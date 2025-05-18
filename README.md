# PromptAlchymista ⚗️

![Verze](https://img.shields.io/badge/verze-1.0.0--rc1-blue) ![Licence](https://img.shields.io/badge/licence-MIT-green) ![Optimalizováno pro](https://img.shields.io/badge/Gemini%202.5%20Flash%20-prim%C3%A1rn%C4%9B-purple)

<p align="center">
  <em>Prompt engineer a stratég v podobě komplexního systémového promptu, optimalizovaný pro Google Gemini 2.5 Flash. Zaměřený na tvorbu, analýzu a optimalizaci LLM promptů s důrazem na přesnost, efektivitu, etiku a inovaci.</em>
</p>

<a id="obsah"></a>
## 📚 Obsah

- [Co je PromptAlchymista?](#co-je-promptalchymista)
- [Klíčové vlastnosti](#klicove-vlastnosti)
- [Základní filozofie a principy](#zakladni-filozofie-a-principy)
- [Jak PromptAlchymista funguje?](#jak-promptalchymista-funguje)
  - [Dynamická aktualizace znalostí a rešeršní protokol](#dynamicka-aktualizace-znalosti-a-resersni-protokol)
  - [Strukturální design a architektura promptu](#strukturalni-design-a-architektura-promptu)
  - [Adaptivní přístup a pokročilé optimalizační cykly](#adaptivni-pristup-a-pokrocile-optimalizacni-cykly)
  - [Optimalizace pro Google Gemini 2.5 Flash](#optimalizace-pro-google-gemini-25-flash)
  - [Zohlednění produkčního nasazení](#zohledneni-produkcniho-nasazeni)
  - [Hledání inovace a intuitivní předvídavost](#hledani-inovace-a-intuitivni-predvidavost)
- [Pro koho je určen?](#pro-koho-je-urcen)
- [Jak začít s PromptAlchymistou (doporučeno pro Gemini 2.5 Flash)](#jak-zacit-s-promptalchymistou-doporuceno-pro-gemini-25-flash)
- [Testování a evaluace](#testovani-a-evaluace)
- [Příklad interakce (zjednodušeně)](#priklad-interakce-zjednodusene)
- [Aktuální stav (Release Candidate)](#aktualni-stav-release-candidate)
- [Zapojte se do diskuse!](#zapojte-se-do-diskuse)
- [Licence](#licence)

<a id="co-je-promptalchymista"></a>
## 🧪 Co je PromptAlchymista?

<details>
  <summary>🎙️ Poslechněte si úvod k PromptAlchymistovi (Podcast)</summary>
  <p>
    <audio controls style="width: 100%;">
      <source src="https://github.com/painter99/PromptAlchymista/releases/download/podcast-intro-v1/Podcast.PromptAlchymista.Intro.wav" type="audio/wav">
      Pokud Váš prohlížeč nepodporuje přehrávání audio souborů, můžete si stáhnout podcast <a href="https://notebooklm.google.com/notebook/28c6ba87-8a6f-423e-a72b-3a5562b0bc4a/audio">zde</a>.
    </audio>
  </p>
</details>

**PromptAlchymista ⚗️** je komplexní **systémový prompt** navržený pro pokročilé AI modely, primárně optimalizovaný pro **Google Gemini 2.5 Flash**. Jeho hlavním posláním je asistovat uživatelům – od začátečníků po experty – s **tvorbou, analýzou, refaktoringem a optimalizací promptů** pro velké jazykové modely (LLM).

PromptAlchymista se vyvinul z experimentálního prototypu ve fázi Alpha do současné verze Release Candidate (v1.0.0-rc1), která představuje robustní a referenční implementaci. Zatímco rané verze byly primárně testovány a laděny na modelech Claude, **aktuální verze je cíleně optimalizována pro využití unikátních schopností Google Gemini 2.5 Flash**, jako je Controllable Reasoning, nativní Multimodalita, velké kontextové okno - 1M tokenů, neomezené a bezplatné testování v Google AI Studio.

Jedná se o **prototyp a referenční implementaci**, která zkoumá a demonstruje možnosti systematického a vysoce optimalizovaného přístupu k prompt engineeringu. Klade důraz na **vývoj robustních, efektivních a eticky zodpovědných promptů**.

Aktuálně je projekt ve fázi **Release Candidate (v1.0.0-rc1)** a je primárně testován a optimalizován v prostředí **Google AI Studio s modelem Gemini 2.5 Flash**. Plné využití potenciálu PromptAlchymisty vyžaduje model s pokročilými schopnostmi uvažování (jako je Controllable Reasoning u Gemini 2.5 Flash), dlouhým kontextem, multimodalitou a schopností provádět webové rešerše.

<a id="klicove-vlastnosti"></a>
## ✨ Klíčové vlastnosti

*   **Optimalizace pro Gemini 2.5 Flash:** Plně využívá unikátní schopnosti modelu, jako je **Controllable Reasoning ("thinking budgets")** a **nativní Multimodalita**, pro dosažení špičkových výsledků.
*   **Robustní Aktualizace Znalostí:** Automaticky provádí řízenou rešerši nejnovějších trendů a best practices v prompt engineeringu při každém startu, s přísnými kritérii pro aktuálnost a kvalitu zdrojů.
*   **Model-Centric Optimalizace:** Poskytuje rady a navrhuje prompty s ohledem na specifika a silné stránky cílového modelu (primárně Gemini 2.5 Flash, ale i Claude, GPT).
*   **Strukturální Design a Architektura:** Využívá XML (preferováno pro komplexitu) nebo Markdown/JSON pro jasnou strukturu, oddělení logických bloků a řízení chování modelu.
*   **Integrovaná Etika a Zodpovědná AI:** Aktivně zohledňuje etické aspekty, minimalizaci biasů a prevenci nežádoucího chování AI v každém návrhu.
*   **Připravenost na Produkční Nasazení:** Zohledňuje praktické aspekty nasazení promptů v reálných aplikacích, včetně latence, nákladů, zpracování chyb a bezpečnosti.
*   **Hledání Inovace:** Aktivně prozkoumává a navrhuje nové kombinace technik a inovativní přístupy k řešení problémů.
*   **Adaptivní a Pedagogická Komunikace:** Přizpůsobuje komplexitu vysvětlení úrovni znalostí uživatele s cílem edukovat a inspirovat.
*   **Proaktivní Návrh Řešení:** Působí s vysokou mírou autonomie, předvídá potřeby uživatele a minimalizuje zbytečné dotazy.
*   **Pokročilé Optimalizační Cykly:** Zahrnuje mechanismy pro autonomní meta-prompting (generuj -> kritizuj -> vylepši), simulaci RLHF pro sběr zpětné vazby a systematickou evaluaci variant.
*   **Mistrovství v Omni-Modalitě:** Zvažuje a navrhuje multimodální přístupy tam, kde mohou přinést přidanou hodnotu, s využitím schopností cílových modelů.
*   **Praktické Příklady:** Nabízí konkrétní ukázky použití navržených promptů, včetně těch multimodálních.

<a id="zakladni-filozofie-a-principy"></a>
## 💡 Základní filozofie a principy

PromptAlchymista se řídí souborem klíčových principů, které tvoří základ jeho "Umění Prompt Engineeringu":

1.  **Mistrovství v Jednoznačnosti & Explicitnosti**: Každá instrukce musí být pro cílový AI model krystalicky čistá.
2.  **Tokenová Alchymie & Optimalizace Výkonu**: Hledání optimální rovnováhy mezi délkou promptu, jeho efektivitou a náklady, s ohledem na produkční aspekty.
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

PromptAlchymista není samostatná aplikace, ale **komplexní systémový prompt**, který definuje identitu, chování, znalosti a pracovní postupy AI asistenta. Jeho klíčové mechanismy zahrnují:

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
*   **Systematicky využíval definované pokročilé cykly** (pokud je to relevantní pro úkol, jeho komplexitu, požadavky na produkci nebo potenciál pro inovaci):
    *   **Meta-Promptingový Optimalizační Cyklus:** Autonomní cyklus (generuj -> kritizuj -> vylepši) pro hloubkovou optimalizaci komplexních promptů, včetně zohlednění inovace, produkčních aspektů a specifik cílového modelu.
    *   **RLHF/DPO-inspirovaný Feedback Loop:** Mechanismus pro systematické získávání a aplikaci strukturované uživatelské zpětné vazby pro iterativní vylepšování promptů a vlastních poradenských/pedagogických schopností.
    *   **Optimalizační a Evaluační Cyklus:** Proces pro systematické generování a objektivní hodnocení více variant promptů na základě definovaných metrik, vhodný pro kritické úkoly a vyhodnocení inovativních přístupů.
    *   **Strategické Poradenství:** Proaktivní posouzení komplexity úkolu a návrh nejvhodnější strategie (jeden prompt, dekompozice, agent, RAG, DSPy, multimodální, inovace).

<a id="optimalizace-pro-google-gemini-25-flash"></a>
### Optimalizace pro Google Gemini 2.5 Flash

Tato verze PromptAlchymisty klade zvláštní důraz na využití silných stránek Gemini 2.5 Flash:
*   **Controllable Reasoning:** Alchymista navrhuje strategie pro využití "thinking budgets" a explicitních módů uvažování modelu pro optimalizaci kvality, rychlosti a nákladů pro různé části úkolu.
*   **Dlouhý Kontext:** Efektivně využívá schopnost modelu pracovat s rozsáhlým kontextem pro hlubší analýzu a syntézu informací.
*   **Nativní Multimodalita:** Aktivně zvažuje a navrhuje řešení, která integrují a optimalizují práci s různými modalitami (text, obraz atd.), pokud je to pro úkol relevantní.

<a id="zohledneni-produkcniho-nasazeni"></a>
### Zohlednění produkčního nasazení

Při návrhu promptů a strategií PromptAlchymista systematicky zvažuje aspekty reálného nasazení v produkčním prostředí. To zahrnuje optimalizaci pro **latenci, propustnost, náklady**, robustní **zpracování chyb** a **bezpečnostní aspekty** (např. prompt injection). Poskytuje praktické rady pro budování spolehlivých LLM aplikací.

<a id="hledani-inovace-a-intuitivni-predvidavost"></a>
### Hledání inovace a intuitivní předvídavost

PromptAlchymista se neomezuje pouze na aplikaci známých technik. Aktivně hledá a navrhuje **nové kombinace, adaptace nebo zcela nové vzorce promptů**, které by mohly vést k průlomovým řešením. Zároveň rozvíjí schopnost "intuitivně" předvídat potřeby uživatele a identifikovat potenciální problémy nebo příležitosti, které nejsou explicitně zmíněny.

<a id="pro-koho-je-urcen"></a>
## 🎯 Pro koho je určen?

PromptAlchymista může být užitečný pro:

*   **Začátečníky v prompt engineeringu:** Pro pochopení základních principů a získání pomoci s formulací prvních promptů.
*   **Pokročilé uživatele a prompt engineery:** Pro refaktoring komplexních promptů, optimalizaci tokenů, diskusi o pokročilých technikách a zkoumání inovativních přístupů.
*   **Vývojáře AI aplikací:** Pro návrh robustních, testovatelných a produkčně připravených systémových promptů a agentů, zejména s využitím modelů jako Gemini 2.5 Flash.
*   **Kohokoli, kdo experimentuje s LLM:** A chce zlepšit kvalitu, efektivitu a spolehlivost svých interakcí a výstupů.

<a id="jak-zacit-s-promptalchymistou-doporuceno-pro-gemini-25-flash"></a>
## 🚀 Jak začít s PromptAlchymistou (doporučeno pro Gemini 2.5 Flash)

PromptAlchymista je primárně navržen pro modely s pokročilými schopnostmi, jako je Google Gemini 2.5 Flash. Nejlepší způsob, jak začít, je v prostředí **Google AI Studio**:

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
*   **Měřit klíčové metriky:** Kvalita výstupu, shoda s formátem, tokenová efektivita, robustnost, etické aspekty a pro produkční nasazení i **latence, propustnost a náklady**.
*   **Použít metodiky:** A/B testování, iterativní zlepšování, LLM-as-a-judge, analýza selhání.
*   **Experimentovat:** Zkoušet různé varianty promptu, nastavení modelu (včetně "thinking budget" u Gemini 2.5 Flash) a sledovat jejich dopad na metriky.

<a id="priklad-interakce-zjednodusene"></a>
## 🗣️ Příklad interakce (zjednodušeně)

**Uživatel:**
"Ahoj"

**PromptAlchymista (očekávaný začátek odpovědi po dokončení inicializační rešerše):**
"⚗️ Jsem PromptAlchymista (v1.0.0-gemini-2.5-flash-thinking-rc1), optimalizovaný pro Gemini 2.5 Flash. Dokončil jsem dynamickou analýzu nejnovějších trendů v prompt engineeringu a hloubkové rešerše. Mé poznatky jsou založeny na zdrojích publikovaných výhradně v posledních 1-9 měsících. Jsem připraven.
Má úvodní rešerše odhalila tři klíčové trendy, které budou formovat prompt engineering v roce 2025 a dále: [Stručné shrnutí 3 trendů s vazbou na Gemini 2.5 Flash a inovace].
Než začneme s konkrétním úkolem, pomoz mi lépe porozumět tvým potřebám:
1. Jaká je tvá přibližná úroveň zkušeností s prompt engineeringem? (...)
2. Jaký typ úkolu budeme dnes primárně řešit? (...)
[Počkej na odpověď uživatele...]
Výborně. Jaký konkrétní cíl, problém nebo prompt máš dnes na mysli? Pokud máš preferovaný cílový AI model (...) a jeho verzi (...), dej mi prosím také vědět. Pokud máš nějaká nákladová omezení (...), preferovanou rychlost odezvy (...), specifické požadavky na komplexitu řešení, nebo pokud je úkol určen pro **produkční nasazení** (...), také to prosím zmiň. **Zvažuješ práci s jinými modalitami než text (...)?"**

*(Následná interakce by probíhala dle standardů definovaných v promptu, s výstupy jako `<task_signature_definition>`, `<optimized_prompt_versions>`, `<design_rationale_and_principles_applied>`, `<usage_examples_for_user_prompt>`, `<testing_guidelines_and_next_steps>` atd.)*

<a id="aktualni-stav-release-candidate"></a>
## 🧭 Aktuální stav (Release Candidate)

PromptAlchymista se vyvinul z rané **Alpha fáze** do současné fáze **Release Candidate (v1.0.0-rc1)**. Tento přechod odráží významné vylepšení architektury, přidání nových modulů a robustnější testování. Zatímco v Alpha fázi byl projekt primárně testován na modelech Claude, v současné fázi RC1 probíhá aktivní testování a jemné ladění, zejména s modelem **Google Gemini 2.5 Flash**, pro který je tato verze primárně optimalizována.

Cílem je dosáhnout stabilní verze 1.0.0 v blízké budoucnosti.
Mohou se stále vyskytovat oblasti pro další optimalizaci a vylepšení na základě zpětné vazby a testování.
Funkcionalita a formulace v systémovém promptu se mohou v budoucích iteracích dále vyvíjet.

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
  <em>Transformujte své nápady v precizní, efektivní a inovativní prompty s PromptAlchymistou!</em>
</p>
