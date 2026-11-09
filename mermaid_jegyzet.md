# Saját szöveg
- alapvetően azt a problémát oldja meg, hogy a legtöbb esetben csak képként lehet menteni a munkát
- itt elsősorban kódot (leírónyelv) írunk, amiből a mermaid motor diagramot generál
- az összes szükséges diagramtípust tudja, amire szükség lehet
- mivel leírókóddal készítjük a diagramokat, ezért könnyebb lehet verziókezelni
- 


1. Előnyök és korlátok
Őszintén mutasd be mindkettőt, ettől hitelesebb lesz az előadás.

Előnyök:

verziókezelhető, szövegesen diffelhető
gyors és ingyenes, nem kell hozzá külön program
konzisztens megjelenés, több kimeneti formátummal (SVG, PNG)

Korlátok:

az elrendezést korlátozottan lehet befolyásolni, nagy diagramnál átláthatatlan lehet
a béta típusok (sankey, xychart, architecture, block) verziófüggők, és kényesek az ékezetekre (ezt te is láttad)
pixelpontos, designos ábrához nem ez az eszköz

6. Összehasonlítás alternatívákkal
Röviden érdemes megemlíteni a PlantUML-t (érettebb, de Java kell hozzá), a Graphviz/DOT-ot (gráfokra erős) és a draw.io-t (vizuális, de nem kódként kezelhető). Mondd el, mikor melyiket választanád.

7. Javasolt felépítés (kb. 10–15 perc)

Probléma és motiváció (1–2 perc)
Alapszintaxis egy flowchart-on, élő demóval (3–4 perc)
Két-három további típus bemutatása (3–4 perc)
Integrációk: GitHub, VS Code, saját oldal (2 perc)
Korlátok és alternatívák (1–2 perc)
Kérdések

Gyakorlati tippek

Készíts előre elmentett példákat, hogy ne gépelni kelljen a hosszú diagramokat, mert élőben könnyű elrontani a szintaxist.
Legyen biztonsági másolat képernyőképekben, ha nincs internet (a szerkesztőd CDN-ről tölti a könyvtárakat).
Használj valós példát a saját projektedből (például a Kanban alkalmazás állapotgépét vagy az architektúráját), mert a saját témájú diagram meggyőzőbb, mint az általános.