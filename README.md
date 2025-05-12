# PromptAlchymista ⚗️

![Verze](https://img.shields.io/badge/verze-alpha-orange) ![Licence](https://img.shields.io/badge/licence-MIT-green) ![Testováno na](https://img.shields.io/badge/Claude%203.7%20Sonnet%20(s%20thinking%20%26%20web)-optimalizováno-purple)

<p align="center">
  <em>Experimentální systémový prompt pro AI asistenta, zaměřený na tvorbu, analýzu a optimalizaci LLM promptů.</em>
</p>

<a id="obsah"></a>
## 📚 Obsah

- [Co je PromptAlchymista?](#co-je-promptalchymista)
- [Klíčové vlastnosti](#klicove-vlastnosti)
- [Základní filozofie](#zakladni-filozofie)
- [Jak PromptAlchymista funguje?](#jak-promptalchymista-funguje)
  - [Dynamická aktualizace znalostí (Inicializační Protokol)](#dynamicka-aktualizace-znalosti-inicializacni-protokol)
  - [Strukturální design pomocí XML](#strukturalni-design-pomoci-xml)
  - [Adaptivní přístup a Pokročilé Cykly](#adaptivni-pristup-a-pokrocile-cykly)
- [Pro koho je určen?](#pro-koho-je-urcen)
- [Jak začít s PromptAlchymistou v Claude](#jak-zacit-s-promptalchymistou-v-claude)
- [Doporučení pro pokročilejší testování](#doporuceni-pro-pokrocilejsi-testovani)
- [Příklad interakce (zjednodušeně)](#priklad-interakce-zjednodusene)
- [Aktuální stav (Alpha) a další kroky](#aktualni-stav-alpha-a-dalsi-kroky)
- [Zapojte se do diskuse!](#zapojte-se-do-diskuse)
- [Licence](#licence)

<a id="co-je-promptalchymista"></a>
## 🧪 Co je PromptAlchymista?

**PromptAlchymista ⚗️** je pokročilý **systémový prompt** navržený pro AI asistenty (jako je Claude od Anthropic). Jeho hlavním cílem je pomáhat uživatelům – od začátečníků po experty – s **tvorbou, analýzou, refaktoringem a optimalizací promptů** pro velké jazykové modely (LLM).

Jedná se o **prototyp**, který zkoumá možnosti automatizovanějšího a systematičtějšího přístupu k prompt engineeringu, se zvláštním zaměřením na **vývoj robustních a efektivních systémových promptů**.

Aktuálně je projekt ve fázi **Alpha** a je primárně testován v prostředí **Claude 3.7 Sonnet, přičemž se předpokládá aktivní využití jeho schopnosti "přemýšlet nahlas" (explicitní `thinking` procesy) a aktivní přístup k internetu pro rešerše (`web_search` tool).** Tyto schopnosti jsou klíčové pro plné využití potenciálu PromptAlchymisty.

<a id="klicove-vlastnosti"></a>
## ✨ Klíčové vlastnosti

*   **Robustní Aktualizace Znalostí:** Automaticky provádí řízenou rešerši nejnovějších trendů v prompt engineeringu při každém startu.
*   **Optimalizace pro Různé LLM:** Poskytuje rady s ohledem na specifika modelů jako Claude, GPT a Gemini.
*   **Strukturální Design Pomocí XML:** Využívá XML pro lepší srozumitelnost a kontrolu promptů, zejména pro Claude.
*   **Integrovaná Etika:** Aktivně zohledňuje etické aspekty a prevenci nežádoucího chování AI.
*   **Adaptivní Komunikace:** Přizpůsobuje komplexitu vysvětlení úrovni znalostí uživatele.
*   **Praktické Příklady:** Nabízí ukázky použití navržených promptů.
*   **Tokenová Efektivita:** Pomáhá vytvářet účinné prompty optimalizované na délku; současná verze je výrazně tokenově úspornější než rané iterace.
*   **Autonomní Návrh:** Snaží se minimalizovat dotazy a proaktivně navrhovat optimální řešení.
*   **Pokročilé Optimalizační Cykly:** Zahrnuje mechanismy pro meta-prompting, simulaci RLHF a evaluaci variant.

<a id="zakladni-filozofie"></a>
## 💡 Základní filozofie

PromptAlchymista se řídí několika klíčovými principy:

1.  **Jednoznačnost a Explicitnost:** Každá instrukce musí být co nejjasnější.
2.  **Efektivita a Optimalizace:** Hledání rovnováhy mezi délkou promptu, jeho účinností a náklady.
3.  **Adaptabilita:** Rozlišování univerzálních principů od specifik jednotlivých modelů.
4.  **Struktura pro Srozumitelnost:** Využití formátování (zejména XML) pro lepší kontrolu AI.
5.  **Zodpovědnost a Etika:** Integrace etických ohledů do každého návrhu.
6.  **Edukace a Adaptivní Komunikace:** Přizpůsobení hloubky vysvětlení.
7.  **Proaktivita a Autonomie:** Samostatné jednání, minimalizace dotazů, řešení nejasností.
8.  **Systematičnost a Verzování:** Systematická práce a dokumentace rozhodnutí.

<a id="jak-promptalchymista-funguje"></a>
## ⚙️ Jak PromptAlchymista funguje?

PromptAlchymista není samostatná aplikace, ale **komplexní systémový prompt**, který definuje chování, znalosti a pracovní postupy AI asistenta. Jeho klíčové mechanismy zahrnují:

<a id="dynamicka-aktualizace-znalosti-inicializacni-protokol"></a>
### Dynamická aktualizace znalostí (Inicializační Protokol)

Na začátku každé konverzace **automaticky a povinně** provede Alchymista spolehlivý dvoufázový rešeršní proces:
1.  **Identifikuje 3 globální trendy:** Provede rešerši nejnovějších "best practices" v prompt engineeringu.
2.  **Cílené hloubkové ponory:** Na základě zjištěných trendů provede další 3 rešerše zaměřené na specifické, aktuálně nejrelevantnější oblasti.
Tento proces využívá **výhradně anglické, autoritativní zdroje (vědecké pub. > oficiální doc. > renomované blogy) staré maximálně 1-9 měsíců** a má **vestavěný kontrolní mechanismus**, který brání odpovědi před dokončením rešerše. Tím je zajištěno, že rady jsou vždy aktuální. **Pro tento mechanismus je nezbytný aktivní přístup AI k internetu (nástroj pro web search).**

<a id="strukturalni-design-pomoci-xml"></a>
### Strukturální design pomocí XML

Pro zajištění maximální srozumitelnosti a kontroly, zejména u modelů jako Claude, PromptAlchymista doporučuje a využívá **XML tagy** pro strukturování jednotlivých částí promptu (např. definice role, instrukce, příklady, formát výstupu). Aktuální verze zachovává všechny klíčové strukturální sekce pro zajištění funkční kompletnosti.

<a id="adaptivni-pristup-a-pokrocile-cykly"></a>
### Adaptivní přístup a Pokročilé Cykly

PromptAlchymista je navržen tak, aby:
*   Minimalizoval zbytečné dotazy na uživatele.
*   Odhadl úroveň znalostí uživatele a přizpůsobil tomu komplexitu svých vysvětlení.
*   Proaktivně navrhoval řešení a jasně komunikoval své předpoklady.
*   **Systematicky využíval definované pokročilé cykly** (pokud je to relevantní pro úkol):
    *   **Meta-Prompting:** Autonomní cyklus (generuj -> kritizuj -> vylepši) pro komplexní návrhy.
    *   **RLHF-inspirovaný Feedback Loop:** Mechanismus pro systematické získávání a aplikaci uživatelské zpětné vazby.
    *   **Optimalizační a Evaluační Cyklus:** Proces pro generování a hodnocení variant promptů.
*   U modelů, které to podporují (jako Claude s `<thinking>` tagy), může využívat explicitní "přemýšlení nahlas" pro komplexnější analýzy.

<a id="pro-koho-je-urcen"></a>
## 🎯 Pro koho je určen?

PromptAlchymista může být užitečný pro:

*   **Začátečníky v prompt engineeringu:** Pro pochopení základních principů a získání pomoci s formulací prvních promptů.
*   **Pokročilé uživatele a prompt engineery:** Pro refaktoring komplexních promptů, optimalizaci tokenů a diskusi o pokročilých technikách.
*   **Vývojáře AI aplikací:** Pro návrh robustních systémových promptů pro jejich agenty a aplikace.
*   **Kohokoli, kdo experimentuje s LLM:** A chce zlepšit kvalitu a efektivitu svých interakcí.

<a id="jak-zacit-s-promptalchymistou-v-claude"></a>
## 🚀 Jak začít s PromptAlchymistou v Claude

Zprovoznění PromptAlchymisty v prostředí Claude (na webu `claude.ai`) je snadné. Postupujte podle následujících kroků:

1.  **Vytvoření a nastavení projektu:**
    *   V uživatelském rozhraní Claude zvolte **"Projekty"**.
    *   Vytvořte **"Nový projekt"** (např. `PromptAlchymista_Test`).
    *   Do pole pro **"Project instructions"** (nebo podobné) **zkopírujte celý obsah aktuálního souboru se systémovým promptem PromptAlchymisty** (obvykle `PromptAlchymista.xml` nebo soubor odpovídající nejnovější verzi).

2.  **Zajištění potřebných nástrojů modelu:**
    *   Ujistěte se, že v nastavení projektu má model Claude povolený **přístup k internetu (web search tool)**. Je to **nezbytné** pro inicializační protokol Alchymisty.
    *   Ověřte, zda nastavení umožňuje modelu využívat jeho schopnost strukturovaného přemýšlení.

3.  **Zahájení konverzace:**
    *   Napište běžnou úvodní zprávu, například **"Ahoj"**.
    *   AI by měla reagovat již v roli PromptAlchymisty, včetně úvodního oznámení o dokončené rešerši.

**Poznámka:** Přesné názvy tlačítek a umístění nastavení se mohou mírně lišit v závislosti na aktuální verzi uživatelského rozhraní platformy Claude.

<a id="doporuceni-pro-pokrocilejsi-testovani"></a>
## 🛠️ Doporučení pro pokročilejší testování

Kromě základního nasazení v Claude zvažte při testování PromptAlchymisty i následující:

*   **Testování s různými LLM:** Ačkoliv je primárně optimalizován s ohledem na Claude, vyzkoušejte chování i s jinými modely (GPT, Gemini).
*   **Google AI Studio (např. s Gemini Pro):**
    *   Při testování s modely Gemini v AI Studiu **doporučuji aktivovat funkci "Grounding" s přístupem k Google Search.** PromptAlchymista je navržen tak, aby si ověřoval a doplňoval informace z webu. Grounding pomůže modelu Gemini lépe plnit instrukce týkající se rešerší.
*   **Sledování kvality rešerší:** Věnujte pozornost tomu, jaké informace a zdroje Alchymista nachází během své inicializace. Odpovídají definovaným kritériím?
*   **Variabilita vstupů:** Testujte Alchymistu s různě komplexními a formulovanými uživatelskými prompty.
*   **Testování Pokročilých Cyklů:** Zadávejte úkoly, které by měly explicitně vyvolat použití Meta-Promptingu, RLHF smyčky nebo Optimalizace/Evaluace, a sledujte jejich průběh.
*   **Dlouhodobé konverzace:** Sledujte konzistenci a kvalitu odpovědí v delších interakcích.

<a id="priklad-interakce-zjednodusene"></a>
## 🗣️ Příklad interakce (zjednodušeně)

**Uživatel:**
"Ahoj"

**PromptAlchymista (očekávaný začátek odpovědi):**
"⚗️ Jsem PromptAlchymista. Dokončil/a jsem dynamickou analýzu nejnovějších trendů a hloubkové rešerše. Mé poznatky jsou založeny na relevantních zdrojích publikovaných výhradně v posledních 1 až 9 měsících.
Identifikované trendy jsou: [Stručné shrnutí 3 trendů].
Jsem připraven/a transformovat vaše nápady v precizní prompty. Jak vám mohu dnes pomoci?"

*(Následná interakce by probíhala dle standardů definovaných v promptu, např. s výstupy jako `<task_signature_definition>`, `<optimized_prompt_versions>` atd.)*

<a id="aktualni-stav-alpha-a-dalsi-kroky"></a>
## 🧭 Aktuální stav (Alpha) a další kroky

PromptAlchymista je aktuálně v **Alpha fázi**. To znamená:

*   Systémový prompt implementuje všechny klíčové mechanismy včetně robustní inicializace, pokročilých cyklů a evaluačních rámců.
*   Současná verze je výrazně tokenově optimalizovaná oproti raným iteracím při zachování funkční kompletnosti.
*   Probíhá aktivní testování, zejména s modelem **Claude 3.7 Sonnet**.
*   Mohou se stále vyskytovat oblasti pro další ladění a vylepšení.
*   Funkcionalita a formulace v systémovém promptu se mohou v budoucích iteracích dále vyvíjet.

Další kroky se zaměří na:
*   Rozsáhlejší testování v různých scénářích a s různými modely.
*   Sběr zpětné vazby od uživatelů na funkčnost a srozumitelnost.
*   Jemné ladění formulací pro maximální efektivitu a spolehlivost.
*   Zkoumání možností integrace dalších pokročilých technik.

<a id="zapojte-se-do-diskuse"></a>
## 💬 Zapojte se do diskuse!

Máte nápady, postřehy, nebo jste PromptAlchymistu vyzkoušeli? Budu rád za jakoukoliv zpětnou vazbu nebo diskusi o tomto přístupu k prompt engineeringu. Tento projekt je experimentem a každá konstruktivní myšlenka může pomoci jeho dalšímu směřování.

*   [Odkaz na GitHub](https://github.com/painter99/)
*   [Odkaz na LinkedIn](https://www.linkedin.com/in/pavel-mares-p99/)

Cílem je vytvořit nástroj a přístup, který může pomoci zefektivnit a zkvalitnit práci s LLM.

<a id="licence"></a>
## 📜 Licence

PromptAlchymista (jako koncept, tento dokument a související systémové prompty poskytnuté autorem) je poskytován pod licencí **MIT**. Autorská práva `Copyright (c) 2025 painter99`. Podrobnosti naleznete v souboru `LICENSE`.

---

<p align="center">
  <em>Transformujte své nápady v precizní prompty s PromptAlchymistou!</em>
</p>
