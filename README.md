# L.O.N.G.I.N.
Logical Orchestrated Networked Generative Inteligent Nexus
L.O.N.G.I.N.
vytvoření a nastavení databáze vytvoření všech základních tabulek MCP server s instrukcemi pro ovládání té databáze.
Flow chat pro asynchronní start to end vývoj modulárních aplikací. Vývoj se skládá ze tří kroků. v 1 kroku a probíhá rozhovor mezi uživatelem A AI modelem určeným pro komunikaci. Uživatel navrhuje aplikaci a agent s mu navrhuje různá řešení technologie frameworky a podobně, A doptává se ho na všechny informace které nutně potřebuje znát k tomu aby mohl dokončit a nasadit aplikaci. Jakmile je uživatel spokojen se zadáním agent zpracuje k celému projektu detailní dokumentaci jakmile bude hotov zeptá se uživatele jestli je opět spokojen s tím jak pochopil že má vytvořit aplikaci. Jakmile je uživatel spokojen začíná fáze 2 a to je vytvoření environmentu pro programování byl dování testování o měření metrik, stoprocentní pokrytí kódu testy komenty s popisky a masivní error handling s try catch bloky je samozřejmostí. Po zadání úkolu nejdřív agenti vytvoří 3 testy pro danou funkcionalitu 1 úspěšný případ 1 neúspěšný případ a 1 krajní hodnoty. a a kompletní implementace malého kusu kódu pokud možno celého modulu I S konektory je to 2 základní stavební prvky se budou opakovat po celé aplikaci. V průběhu flow když se objeví nějaká nejasnost které bude potřebovat rozhodnutí uživatele bude se posílat komunikačnímu agentovi který bude postupně vypisovat otázky na uživatele s očíslováním. Nebude se čekat na odpověď uživatele ale pokračovat v práci na část těch projektů které nesouvisí s danou otázkou až v případě že už nelze dále pokračovat bez interakce uživatele za pauzuje vývoj projektu dokud uživatel neodpoví. Když se objeví nějaká chyba nebo test co neprojde spustí se rolleback funkce která vrátí vývoj zpátky do posledního nechybového stavu a přejde se k opravě kodu který způsobil chybu. pokusí se chybu opravit ale když se 3* opakuje ta samá chyba tak to předají jinému LLM modelu aby to zkusil pokud neuspěje ani ten předá se to ještě třetímu. pokud ani ten neuspěje půjdou s chybou za uživatelem. Pak zde bude asistent pro vyhledávání a rozdělování relevantního kontextu a garbage collection, komunikační agent je zároveň softwarový architekt, A agent pro práci S nástroji, jeho prací je tool execution na základě žádostí ostatních agentů a předání response data agentovi který žádal. integrace a instrukce k používání každého nástroje jsou součástí každého MCP server plugyn modulu.uživatel může kdykoliv v průběhu vývoje dodat nějaké detaily nebo změnit něco co se mu na aplikaci nelíbí hlavní orchestrační agent to opět přidá do seznamu úkolů ke splnění ale na začátek, pokud tu bude úprava, a nakonec pokud to bude něco navíc. když bude kód funkční a kompletní se všemi detaily a konfiguracemi které jsou potřeba úspěšně otestovaný pokusí se agenti nasadit na server a otestovat v reálném prostředí. Pokud tento test projde také oznámí se komunikačnímu agentovi že je tento úkon hotový a orchestrační agent předá další úkol co je na řadě. A takhle flow probíhá až do té doby když jsou všechny úkoly hotové otestované Nasazené a funkční samozřejmě. A pOté komunikační agent předá uživateli sumarizaci naměřených matrik navrhne co by bylo z hlediska bezpečnosti nebo jiných specifikací doplnit nebo jestli něco nechce ještě přidat uživatel a tím pak cyklus flow začíná znovu. Pokud již uživatel nic přidávat nechce a jestli je s aplikací spokojený vytvoří se instalační klient který během instalace provede uživatele veškerými nastaveními které jsou pro správnou funkcionalitu potřeba. tento interaktivní tutorial se bude vyvíjet i testovat stejně jako aplikace a aktualizuje se s novými funkcionalitami a bude spustitelný z UI tlačítkem. vždy se bude najednou vyvíjet jenom 1 modul a konektory k modulu náležící. Někde uložené jako hlavní kontext globálně přístupný po celém systému longin budou tyto dokumenty: list úkonů popisujících zadanou práci rozdělenou na co nejmenší úkoly které se budou postupně odškrtávat v souboru tasklist.md, abstraktní třída modulu a abstraktní třída konektoru, detaily jednotlivých úkolů s detailními popisy, příklady kódů a předpřipravenými nastaveními a konfiguračními soubory a vybranými technologiemi a URL adresy k dokumentaci těch technologií nebo jejich githubu sloužící jako dokumentace k vývoji. vše ostatní se bude ukládat rovnou do databáze ze které si pak může kontextový master zažádat nějaké info které bude rozdělovat mezi ostatní agenty jako potřebný kontext. Od začátku by měly být k dispozici hned po nastavení připojení 2 základní malý agenti docker desktop běžící Gordon a LM studiu základní komunikační model. 

vytvoření a nastavení vectorové lokální databáze vytvoření všech základních tabulek a MCP server s instrukcemi pro ovládání té databáze včetně vytváření a souštění migrací.
Docker vývojové prostředí ve kterém zároveň aplikace i poběží z důvodů hlavního účelu aplikace a to je llm modelem poháněný selfdevelopment TTD engine.   
základní jádro "longin core" poběží v kontejneru s vývojovým a testovacím prostředím společně se základní databází a state machine ovládající vývojovou agent flow a dynamické načítání nových modulů a konektorů. MCP server ze všemi základními nástroji jako pluginy s definováním nástrojů i příkazu k jejich ovládání, open AI API pro komunikaci S LM studiem a jinými cloudovými providery s možností načítat modely Z Lm studia i pullnuté nástrojem ollama'
MCP pro zadávání příkazů do příkazové řádky jejich spuštění a čtení terminálu,
 CRUD správu lokálních souborů A složek,
 vyhledávání na webu, sumarizování webový stránek,
 ovládání webu (interagovat s prohlížečem chrome jako uživatel), ovládání kurzoru myši, možnost kontroly prostřednictvím otevírání oken s potřebními informacemi na 2 monitoru když je k dispozici 2 monitor v případě že není, okna si bude otevírat v pravé čtvrtině monitoru a screenshottování s následnou analýzou obrázků pro zpětnou vazbu. Možnost spustit aplikaci jako server a vystavení její API na webu s možností otevřít si webové UI nebo se připojit na API přes klienta z Androidu obě 2 UI by měli pracovat s lokálně rozjetým serverem mít možnost načítat lokální modely z prostředí lm studio serveru a veškeré konfigurace které jsou potřeba a .env soubor se všemi sekrety a tokeny.

 každý další kus kódu to se do aplikace bude přidávat jako nový modul s novým kontejnerem ve kterém musí být vše včetně instrukcí pro používání daného modulu llm modelem a způsobu jakým bude komunikovat s "longin core". 
Pro backend použij python SDK
pro frontend javascript SDK
docker desktop SDK,
Místo knihovny conda použij knihovnu UV

webový frontend s funkcí přepínání do módu pro Android ve kterém se u upraví tak aby všechny prvky byly přizpůsobené pro dotykové ovládání a velikost displeje mobilu

skript na propojení olama modelů S lm studiem:

"# Spusťte jako: python3 link-ollama-models-to-lm-studio.py
# Na Windows spusťte s administrátorskými právy
import json
import os
from pathlib import Path![UI](https://github.com/user-attachments/assets/33c620f4-cbac-411f-86a5-770cc4c2628e)


USER_HOME_DIR = Path(os.path.expanduser("~"))
OLLAMA_MODEL_DIR = Path(os.environ.get("OLLAMA_MODELS") or USER_HOME_DIR / ".ollama" / "models")
LM_STUDIO_MODEL_DIR = USER_HOME_DIR / ".lmstudio" / "models"

# Funkce pro extrakci cesty k GGUF souboru modelu
def get_model_gguf_path(ollama_model_tag_manifest_path):
    with open(ollama_model_tag_manifest_path) as mf:
        manifest = json.load(mf)
    model_layer = next(
        layer
        for layer in manifest["layers"]
        if layer["mediaType"] == "application/vnd.ollama.image.model"
    )
    gguf_hash = model_layer["digest"]
    gguf_filename = gguf_hash.replace(":", "-")
    gguf_path = OLLAMA_MODEL_DIR / "blobs" / gguf_filename
    return gguf_path
"
