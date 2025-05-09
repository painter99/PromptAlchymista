# PromptAlchymista ⚗️

![Verze](https://img.shields.io/badge/verze-v0.1.2--alpha-orange) ![Licence](https://img.shields.io/badge/licence-MIT-green) ![Testováno na](https://img.shields.io/badge/Claude%203.7%20Sonnet%20(s%20thinking%20%26%20web)-optimalizováno-purple)

![](https://komarev.com/ghpvc/?username=painter99/PromptAlchymista&color=blue&style=flat-square)

<p align="center">
  <em>Experimentální systémový prompt pro AI asistenta, zaměřený na tvorbu, analýzu a optimalizaci LLM promptů.</em>
</p>

## 📚 Obsah

- [Co je PromptAlchymista?](#co-je-promptalchymista)
- [Klíčové vlastnosti](#klíčové-vlastnosti)
- [Základní filozofie](#základní-filozofie)
- [Jak PromptAlchymista funguje?](#jak-promptalchymista-funguje)
-   - [Dynamická aktualizace znalostí](#dynamická-aktualizace-znalostí)
-   - [Strukturální design pomocí XML](#strukturální-design-pomocí-xml)
-   - [Adaptivní přístup](#adaptivní-přístup)
- [Pro koho je určen?](#pro-koho-je-určen)
- [Doporučení pro nasazení a testování](#doporučení-pro-nasazení-a-testování)
- [Příklad interakce (zjednodušeně)](#příklad-interakce-zjednodušeně)
- [Aktuální stav (Alpha) a další kroky](#aktuální-stav-alpha-a-další-kroky)
- [Zapojte se do diskuse!](#zapojte-se-do-diskuse)
- [Licence](#licence)

## 🧪 Co je PromptAlchymista?

**PromptAlchymista ⚗️** je pokročilý **systémový prompt** navržený pro AI asistenty (jako je Claude od Anthropic). Jeho hlavním cílem je pomáhat uživatelům – od začátečníků po experty – s **tvorbou, analýzou, refaktoringem a optimalizací promptů** pro velké jazykové modely (LLM).

Jedná se o **prototyp**, který zkoumá možnosti automatizovanějšího a systematičtějšího přístupu k prompt engineeringu, se zvláštním zaměřením na **vývoj robustních systémových promptů**.

Aktuálně je projekt ve fázi **Alpha (verze v0.1.2-alpha)** a je primárně testován v prostředí **Claude 3.7 Sonnet, přičemž se předpokládá aktivní využití jeho schopnosti "přemýšlet nahlas" (explicitní `thinking` procesy) a aktivní přístup k internetu pro rešerše (`web_search` tool).** Tyto schopnosti jsou klíčové pro plné využití potenciálu PromptAlchymisty.

## ✨ Klíčové vlastnosti

*   **Inteligentní aktualizace znalostí:** Automaticky si doplňuje nejnovější poznatky z prompt engineeringu pomocí řízených webových rešerší.
*   **Optimalizace pro různé LLM:** Poskytuje rady s ohledem na specifika modelů jako Claude, GPT a Gemini.
*   **Strukturální design pomocí XML:** Využívá XML pro lepší srozumitelnost a kontrolu promptů, zejména pro Claude.
*   **Etický design promptů:** Aktivně zohledňuje etické aspekty a prevenci nežádoucího chování AI.
*   **Adaptivní komunikace:** Přizpůsobuje komplexitu vysvětlení úrovni znalostí uživatele.
*   **Generování praktických příkladů:** Nabízí ukázky použití navržených promptů.
*   **Tokenová efektivita:** Pomáhá vytvářet prompty, které jsou účinné a zároveň šetří tokeny.
*   **Autonomní návrh řešení:** Snaží se minimalizovat zbytečné dotazy a proaktivně navrhovat optimální řešení.

## 💡 Základní filozofie

PromptAlchymista se řídí několika klíčovými principy:

1.  **Jednoznačnost a Explicitnost:** Každá instrukce v promptu musí být co nejjasnější.
2.  **Efektivita a Optimalizace:** Hledání rovnováhy mezi délkou promptu, jeho účinností a náklady.
3.  **Adaptabilita:** Rozlišování univerzálních principů od specifik jednotlivých modelů.
4.  **Struktura pro Srozumitelnost:** Využití formátování (zejména XML) pro lepší kontrolu AI.
5.  **Zodpovědnost a Etika:** Integrace etických ohledů do každého návrhu.
6.  **Neustálé Učení:** Dynamické získávání a aplikace nejnovějších poznatků v oboru.
7.  **Praktická Pomoc:** Poskytování srozumitelných a použitelných výsledků.

## ⚙️ Jak PromptAlchymista funguje?

PromptAlchymista není samostatná aplikace, ale **komplexní systémový prompt**, který definuje chování, znalosti a pracovní postupy AI asistenta. Jeho klíčové mechanismy zahrnují:

### Dynamická aktualizace znalostí

Na začátku každé konverzace provede Alchymista inteligentní dvoufázový rešeršní proces:
1.  **Identifikuje globální trendy:** Provede rešerši nejnovějších "best practices" v prompt engineeringu.
2.  **Cílené hloubkové ponory:** Na základě zjištěných trendů provede 2-3 další rešerše zaměřené na specifické, aktuálně nejrelevantnější oblasti.
Tento proces využívá **výhradně anglické, autoritativní zdroje (oficiální dokumentace, výzkumné publikace, uznávané blogy expertů) staré maximálně 1-9 měsíců**, což zajišťuje, že jeho rady jsou postaveny na čerstvých a ověřených informacích. **Pro tento mechanismus je nezbytný aktivní přístup AI k internetu (nástroj pro web search).**

### Strukturální design pomocí XML

Pro zajištění maximální srozumitelnosti a kontroly, zejména u modelů jako Claude, PromptAlchymista doporučuje a využívá **XML tagy** pro strukturování jednotlivých částí promptu (např. definice role, instrukce, příklady, formát výstupu).

### Adaptivní přístup

PromptAlchymista je navržen tak, aby:
*   Minimalizoval zbytečné dotazy na uživatele.
*   Odhadl úroveň znalostí uživatele a přizpůsobil tomu komplexitu svých vysvětlení.
*   Proaktivně navrhoval řešení a jasně komunikoval své předpoklady.
*   U modelů, které to podporují (jako Claude s `<thinking>` tagy), může využívat explicitní "přemýšlení nahlas" pro komplexnější analýzy.

## 🎯 Pro koho je určen?

PromptAlchymista může být užitečný pro:

*   **Začátečníky v prompt engineeringu:** Pro pochopení základních principů a získání pomoci s formulací prvních promptů.
*   **Pokročilé uživatele a prompt engineery:** Pro refaktoring komplexních promptů, optimalizaci tokenů a diskusi o pokročilých technikách.
*   **Vývojáře AI aplikací:** Pro návrh robustních systémových promptů pro jejich agenty a aplikace.
*   **Kohokoli, kdo experimentuje s LLM:** A chce zlepšit kvalitu a efektivitu svých interakcí.

## 🛠️ Doporučení pro nasazení a testování

*   **Claude (např. 3.7 Sonnet):** Pro optimální funkčnost je doporučeno používat PromptAlchymistu v prostředí, které umožňuje modelu:
    *   **Aktivní přístup k internetu** (pro `web_search` v rámci dynamické aktualizace znalostí).
    *   **Využití explicitních kroků přemýšlení** (např. podporou `<thinking>` tagů nebo obdobných mechanismů, pokud jsou dostupné).
*   **Google AI Studio (např. s Gemini 1.5 Pro):** Pokud budete PromptAlchymistu testovat s modely Gemini:
    *   **Důrazně doporučujeme aktivovat funkci "Grounding" (uzemnění) s přístupem k Google Search.** PromptAlchymista je navržen tak, aby si ověřoval a doplňoval informace z webu. Grounding pomůže modelu Gemini lépe plnit instrukce týkající se rešerší, omezit případné halucinace a zajistit, že odpovědi jsou založeny na aktuálních datech, což je v souladu s principy PromptAlchymisty. Bez uzemnění by mohla být jeho schopnost dynamicky aktualizovat znalosti omezena.

## 🗣️ Příklad interakce (zjednodušeně)

**Uživatel:**
"Ahoj Alchymisto, mám tento prompt pro generování popisů produktů, ale odpovědi jsou často moc obecné. Můžeš mi pomoci ho vylepšit pro model Claude Sonnet?"
*(Následuje původní prompt uživatele)*

**PromptAlchymista (očekávaný začátek odpovědi):**
"⚗️ Jsem PromptAlchymista. Právě jsem dokončil/a dynamickou analýzu nejnovějších trendů v prompt engineeringu... Rozumím, podíváme se na tvůj prompt pro generování popisů produktů. Nejprve provedu jeho analýzu a pak navrhnu optimalizace pro lepší specifičnost odpovědí a efektivitu pro Claude Sonnet.
Zde je má analýza původního promptu:
`<original_prompt_assessment>`
...
Navrhuji následující optimalizovanou verzi:
`<optimized_prompt_versions>`
...
Toto jsou principy, které jsem aplikoval:
`<design_rationale_and_principles_applied>`
..."

## 🧭 Aktuální stav (Alpha) a další kroky

PromptAlchymista je aktuálně v **Alpha fázi (verze v0.1.2-alpha)**. To znamená:

*   Základní koncept a klíčové mechanismy jsou implementovány v systémovém promptu.
*   Probíhá aktivní testování, zejména s modelem **Claude 3.7 Sonnet** za výše uvedených podmínek.
*   Mohou se vyskytovat neočekávané chování nebo oblasti pro vylepšení.
*   Funkcionalita a formulace v systémovém promptu se mohou v budoucích iteracích měnit na základě testování a zpětné vazby.

Další kroky se zaměří na:
*   Rozsáhlejší testování v různých scénářích a s různými modely.
*   Sběr zpětné vazby od uživatelů.
*   Postupné ladění a vylepšování jednotlivých částí systémového promptu.
*   Zkoumání možností pro ještě pokročilejší automatizaci a analýzu.

## 💬 Zapojte se do diskuse!

Máte nápady, postřehy, nebo jste PromptAlchymistu vyzkoušeli? Budu rád za jakoukoliv zpětnou vazbu nebo diskusi o tomto přístupu k prompt engineeringu. Tento projekt je experimentem a každá konstruktivní myšlenka může pomoci jeho dalšímu směřování.

*   [Odkaz na váš GitHub repozitář / profil – pokud existuje]
*   [Odkaz na váš LinkedIn / jiný relevantní kontakt – pokud chcete sdílet]

Cílem je vytvořit nástroj a přístup, který může pomoci zefektivnit a zkvalitnit práci s LLM, a možná inspirovat další vývoj v této fascinující oblasti.

## 📜 Licence

PromptAlchymista (jako koncept a tento dokument) je poskytován pod licencí **MIT**. Podrobnosti naleznete v souboru `LICENSE`.

---

<p align="center">
  <em>Transformujte své nápady v precizní prompty s PromptAlchymistou!</em>
</p>
