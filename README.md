 Miről szól a tananyag? 
A tananyag célja, hogy megismertesse a diákokat az alapvető elektronikai eszközökkel, alkatrészekkel, azok működésével, és az elektronikai áramkörök tervezésével. A tanulók megismerkednek az elektronikai alapfogalmakkal, a legfontosabb alkatrészekkel, és azok felhasználásával különböző áramkörökben.
Milyen alkatrészeket tanultunk, ezek mire valók? 
á Resisztorok (ellenállások): Az áramkörökben az áram erősségét szabályozzák, és védelmet nyújtanak a túl nagy áramok ellen.
Kondenzátorok: Energiát tárolnak és kisülnek, ezzel szabályozva a feszültséget. Az áramkörökben a zajcsökkentésre és feszültségszűrésre is használják.
Diódák: Egyirányú áramvezetésre képesek, főleg az áramkörök irányítására használják, például egyenirányítókban.
Tranzisztorok: Elektronikus kapcsolóként működnek, és lehetővé teszik az áramkörök erősítését, kapcsolását, például erősítőkben vagy logikai áramkörökben.
Integrált áramkörök (IC-k): Több elektronikai funkció egyetlen egységbe integrálása, pl. mikroprocesszorok, memóriachipek, stb.
Induktivitások: Olyan alkatrészek, amelyek mágneses teret hoznak létre, és segítenek az áramingadozások szűrésében.
 Milyen áramköröket lehet elkészíteni ezekből?
-Egyszerű áramkörök: Például fényerő-szabályozó áramkör, alap áramkörök kondenzátorokkal, ellenállásokkal.
Erősítők: Tranzisztorok felhasználásával hang- vagy jelelfogó erősítők.
Logikai áramkörök: Alap logikai műveletek (ÉS, VAGY, NEM) tranzisztorokkal, amelyek különböző vezérlési feladatokat látnak el.
Szerelt áramkörök: Digitális áramkörök IC-kkel, például mikroprocesszoros vezérlés vagy memória-kezelés.
Tápegységek: Az egyenáramú tápegységek létrehozása diódákkal és kondenzátorokkal.
 Stb.
Mérések és hibakeresés: Az elektronikai áramkörök működését multiméterekkel mérhetjük, ellenőrizhetjük az áramkörök feszültségét, áramát, és hőmérsékletét. A hibák azonosításában a szimulátorok és a gyakorlati tesztek segítenek.
Szimulációk: A tananyag részeként sokszor szimulációkat is végezhetünk (pl. Tinkercad vagy LTSpice), hogy az áramköröket virtuálisan teszteljük, mielőtt fizikailag is összeállítanánk őket.
1. Feszültség, áramerősség, ellenállás és teljesítmény
Feszültség (U): A feszültség az elektromos potenciálkülönbséget jelenti két pont között. Egyszerűbben fogalmazva, a feszültség az, ami "mozgásra kényszeríti" az elektronokat egy vezetőben, tehát a feszültség az áram áramlását előidéző erő. A feszültséget voltokban (V) mérjük.
Áramerősség (I): Az áramerősség a vezetőn áramló töltések (elektronok) számát jelenti egy adott idő alatt. Az áram mértéke azt mutatja meg, hogy milyen erővel áramlik az elektromos töltés az áramkörben. Az áramot amperben (A) mérjük.
Ellenállás (R): Az ellenállás az áramkör azon tulajdonsága, amely akadályozza az áram áramlását. Mértékegysége az ohm (Ω). Az Ohm törvénye szerint az ellenállás egyenesen arányos a feszültséggel, és fordítottan arányos az áramerősséggel:
𝑅
=
𝑈
𝐼
R= 
I
U
Teljesítmény (P): A teljesítmény azt mutatja meg, hogy egy áramkörben mennyi energiát fogyaszt az áram. A teljesítmény az áram és a feszültség szorzataként számítható: 
𝑃
=
𝑈
×
𝐼
P=U×I A teljesítmény mértékegysége a watt (W), és jellemzően a fogyasztók energiafelhasználásának meghatározására használják.
2. Árammérő és feszültségmérő bekötése
Árammérő (ampermérő): Az árammérő az áramkörben folyó áram erősségét méri. A helyes működés érdekében az árammérőt sorosan kell bekötni az áramkörbe, tehát az áramnak végig kell folynia rajta. Az árammérő belső ellenállása minimális, mert ha túl nagy lenne, akkor jelentősen csökkentené az áramot az áramkörben.
Feszültségmérő (voltmérő): A feszültségmérő a két pont közötti feszültséget méri. Ahhoz, hogy a feszültségmérő pontos adatokat adjon, párhuzamosan kell bekötni az áramkörben lévő eszközzel (például egy ellenállással vagy fogyasztóval). A feszültségmérő belső ellenállása nagyon magas, hogy ne befolyásolja az áramkör működését.
3. Ellenállás kapcsolása
Soros kapcsolás: Soros kapcsoláskor az ellenállásokat egy sorban kötjük be. Ez azt jelenti, hogy az áramnak mindegyik ellenálláson végig kell haladnia. Az összellenállás (Rₒssz) 
Mivel az áram minden egyes ellenálláson ugyanakkora, a feszültség oszlik meg közöttük, azaz minden ellenálláson más és más feszültség alakul ki, attól függően, hogy mekkora az ellenállás értéke.
Párhuzamos kapcsolás: Párhuzamos kapcsoláskor az ellenállások párhuzamosan csatlakoznak a feszültségforráshoz, tehát mindegyik ugyanakkora feszültséget kap. Az összellenállás ebben az esetben kisebb lesz, mint a legkisebb ellenállás, 
   párhuzamos kapcsolás előnye, hogy az áram elágazik a különböző ágak között, és minden ágban más-más áramerősség alakulhat ki, de a feszültség minden ágban azonos.

4. Ellenállás és kondenzátor jellemzői
Ellenállás: Az ellenállás az egyik alapvető elektronikai alkatrész, amely korlátozza az áram áramlását az áramkörben. A színkód segítségével jelezhetjük az ellenállás értékét és tűrését. Az ellenállások különböző alkalmazásokat szolgálnak, például feszültségosztók, áramkorlátozók és jelátalakítók formájában.

Kondenzátor: A kondenzátor egy olyan alkatrész, amely elektromos töltést képes tárolni. Két vezető lemez között szigetelő anyag található, és a kondenzátor kapacitása (mértékegysége: Farad) adja meg, hogy mennyi töltést képes tárolni. A kondenzátorokat többek között szűrésre, időzítésre, csatolásra és zajszűrésre használják. Fontos, hogy az elektrolit kondenzátorok polarizáltak, tehát figyelni kell a + és – bekötésre.

5. NE555 IC jellemzői
Az NE555 egy igen népszerű időzítő IC, amelyet széleskörű elektronikai alkalmazásokban használnak. Három fő működési módja létezik:

Monostabil: Az IC egyetlen impulzust ad ki egy trigger jelet követően.
Asztabil: Az IC folyamatosan ismétlődő négyszögjeleket generál, így például impulzusgenerátorokhoz vagy LED-villogtatókhoz alkalmazható.
Bistabil: Az IC két állapot között váltogat, például kapcsolók és digitális tárolás esetén.
6. Tranzisztor jellemzői
A tranzisztor egy félvezető eszköz, amelyet az elektronikai áramkörökben kapcsolási és erősítési célokra használnak. Két fő típusa létezik: NPN és PNP. A tranzisztorok az áramkörök fontos építőelemei, amelyek képesek kis jeleket nagyobb áramokká erősíteni, illetve kapcsolóként is működhetnek.

7. LED és félvezetők
A LED (Light Emitting Diode) egy olyan félvezető eszköz, amely fényt bocsát ki, amikor áram folyik rajta keresztül. Az LED-ek különböző színekben elérhetők, az előfeszítési feszültségük általában 1,8–3,3 V között van. Fontos, hogy áramkorlátozó ellenállást alkalmazzunk mellettük, hogy elkerüljük a túlfeszültséget. A LED-eket széles körben használják világításhoz, kijelzőkhöz és jelzésekhez.

8. DC tápellátás
A DC (egyenáramú) tápellátás folyamatos irányú áramot biztosít az áramkörök számára. A DC tápellátás előnye, hogy az áram iránya nem változik, és így stabil, egyenletes feszültség biztosítható a különböző eszközök számára. Az elérhető feszültségértékek például 5V, 9V, vagy 12V lehetnek.

