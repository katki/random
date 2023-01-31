**1. Meranie softvéru** - proces kvantifikácie softvéru. Je možné merať kvalitu softvéru aj proces vývoja.<br /><br />
**2. validáciou a verifikáciou** - val: program je užitočný, ver: ak program splňa požiadavky<br /><br />
**3. Modelovanie a čo je za tým**-softvér je vyvýjaný na základe modelu, ktorý sa približuje realite požiadaviek, avšak model má limity<br /><br />
**4. Limity modelov** nie všetko môže byť modelované (teoretické a tech. Obmedzenia), nie všetko by malo byť modelované (morálne, ekonomické limity)<br /><br />
**5. Návrh softvéru a problémy spojené s ním** vzhľadom na zvyšujúcu sa uroveň abstrakcie je problémom porozumenie doméne a požiadavkám a aj zvolený dizajn sw<br /><br />
**6. Inžinierstvo softvéru a ostatné typy "inžinierstva"** <br /><br />
**7. Evolúcia, údržba a pochopenie softvéru**<br /><br />
**8. Komplexnosť softvéru** softvér je komplexný pretože máme ambíciu používať počítače viac sofistikovane, komplexita ovplyvňuje používateľol aj stakeholderov<br /><br />
**9. Pochopenie, algoritmizácia a programovanie** <br /><br />
**10. Úplnosť súboru požiadaviek** súbor požiadaviek nikdy nie je úplný, pochopenie sw požiadaviek je proces<br /><br />
**11. Lehmanove prav. o zmenách** Systémy typu E, ktoré sa používajú, sa musia neustále prispôsobovať, inak sa stanú menej uspokojivé.<br /><br />
**12. Lehmanove prav. o komplexnosti** Ako sa systém typu E vyvíja, jeho zložitosť sa zvyšuje, pokiaľ udržiava alebo redukuje.<br /><br />
**13. Lehmanove prav. o samoregulácii** Procesy vývoja globálneho systému typu E sú samoregulačné.<br /><br />
**14. Lehmanove p. o stabilite** Globálna miera aktivity vo vyvíjajúcom sa systéme E má tendenciu byť konštantná počas životnosti produktu.<br /><br />
**15. Lehmanove p. o raste** Funkčný obsah systémov typu E sa musí zvyšovať, aby sa zachovala spokojnosť používateľov počas životnosti.<br /><br />
**16. Lehmanove p. o znižovaní kvality** Kvalita systému E bude klesať, ak nebude prispôsobený tak, aby zohľadňoval zmeny v prevádzkovom prostredí.<br /><br />
**17. GQM** definuje meranie na 3 úrovniach: Koncepčná úroveň (cieľ) Špecifikácia cieľa je definovaná podľa aktuálneho modelu.<br /><br />
Operačná úroveň (otázka) Pri hodnotení konkrétnych cieľov pomáha súbor otázok, ktoré model definujú a charakterizujú.<br />
Kvantitatívna úroveň (čo merať – metrika) Ide o súbor vlastností modelu, ktoré je potrebné merať, aby bolo možné odpovedať na otázky.<br />
**18. Demeterin zákon** je jednoduché pravidlo štýlu pre navrhovanie objektovo orientovaných systémov. Objekt by mal komunikovať iba so svojimi susedmi a nemal by vedieť o fungovaní okolitých objektov<br /><br />
**19. Spojenie (coupling)** 2 časti softvéru spolu súvisia natoľko, že jednu nie je možné oddeliť od druhej (problem dedenia v jave)<br /><br />
**20. Súdržnosť (cohesion)** opisuje úroveň sémantického prepojenia prvkov, vysoká súdržnosť hovorí o tom, že veľa prvkov má medzi sebou prepojenie<br /><br />
**21. Čo je testovanie?** proces hodnotenia aplikáciens cieľom nájsť chyby a zistiť či aplikácia splňa požiadavky<br /><br />
**22. Kedy testovať softvér a kedy iný produkt?** Testovanie je súčasťou vývojového procesu, nie je to výrobný proces. Tým sa líši od mnohých iných strojárskych produktov, kde je kladený dôraz na testovanie správnej reprodukcie. <br /><br />
**24. Nedostatok, zlyhanie, chyba** Nedostatok má za následok nechcené správanie SW. Chyba je rozpor medzi vypočítanými/nameranými hodnotami a skutočnými/zadanými hodnotami. Zlyhanie je neschopnosť systému plniť požadované funkcie v rámci špecifikovanej požiadavky.<br /><br />
**25. Testovanie - biela skrinka** testovanie uplatňujúce vedomosti o kóde založené na návrh a špecifikácii požiadaviek<br /><br />
**26. Testovanie - čierna skrinka** testovanie na používateľskom leveli<br /><br />
**27. Testovanie - sivá skrinka** k nejakým častima testovania pristupuje ako k blackboxu a k iným ako white boxu<br /><br />
**28. Pochopenie programu, pomocné nástroje** pochopiť program znamená pozozumieť jeho funkcionalite<br /><br />
**29. Architektúra testovania** Testovacia architektúra sa skladá z "testovacích bodov" a vzťahov medzi nimi
Prvky architektúry testovania: ­ Testvér ­ Testovaný systém (SUT) ­ Komponenty testov – prípady a procedúry ­ Testovacia množina dát<br /><br />
**30. Testvér** nástroje a dokumentácia vytvorené pre testovanie. test cases, test scripts a iný material na dizajnovanie, plánovanie a spuštanie testov<br /><br />
**31. Dokumentácia k testovaniu** obsahuje informácie o subjekte testu, cieľoch testu, metodach testovania, dátach, výsledkoch a verdikte<br /><br />
**32. Zmeny v softvéri** nevyhnutné - nové požiadavky, oprava chýb, zmena hw<br /><br />
**33. Život softvéru** vývoj -> evolúcia -> obsluha -> výslužba<br /><br />
**34. Proces evolúcie (implementácie zmien)** request -> analýza -> planning -> implementation -> release<br /><br />
**35. Evolúcia v agilných metódach vývoja softvéru** inkrementálny vývoj aplikácie založený na častých verziách sw<br /><br />
**36. Staré/Zastaralé systémy, problémy** spoliehajú sa na staré technologie a jazyky, ich výmena je riskantná a náročná<br /><br />
**37. Prvky starších systémov** aplikácia, dáta, podporné aplikácie, hw, bussiness pravidlá a procesy<br /><br />
**38. Stratégie evolúcie starších a zastaralých systémov** Nahradenie – riskantné a nákladné, Zmena – napr. ak je nedostatočná dokumentácia či potrebná zmena na konzistentný programovací štýl, Vyradenie ­ ak bude neužitočný<br /><br />
**39. Meranie starších a zastaralých systémov** <br /><br />
**40. Typy údržby** Oprava poruchy, Environmentálne prispôsobenie, Úprava funkčnosti, Pridanie novej funkcionality<br /><br />
**41. Predikcia údržby, predikcia zmien** rôzne metriky môžu určiť potenciálne problémové časti; PZ: na základe vzťahu sw a prostredia vieme predikovať potrebné zmeny <br /><br />
**42. Reengineering, prerábanie softvéru** zmena sw bez zmeny funkcionality, redukuje budúce náklady a risky, sw je jednoduchší na údržbu<br /><br />
**43. Refaktorizácia ako forma údržby** proces počas tvorby sw, ktorý ma za učel predísť degradácii kodu<br /><br />
**44. Zapáchajúce nedostatky - bad smells**duplicita kodu, dlhe metody, switch, data chumping<br /><br />
**45. Testovanie použiteľnosti** SUV testovanie používateľskeho rozhrania <br /><br />
**46. Constantineov zákon** štruktúra je stabilná ak je súdržnosť vysoká a spojenie slabé<br /><br />
**47. Mooreov zákon** každých 18 mesiacov sa zdvojnásobí počet integrovaných obvodov<br /><br />
**48. Zelený softvér** softvér vyvijany s dorazom na ekologiu napr. redukciou spotreby energie<br /><br />
**49. Invazívne meranie spotreby** vloženie niečoho do systému alebo odstránenie nejakej časti (napr. unit testy) alebo prepočítanie LOC na energiu<br /><br />
**50. Neinvazívne meranie spotreby** pozorovanie softvéru, využitie ext. nástrvojov, napr. pomocou nástroja na meranie energie <br /><br />
**51. Produktové línie** <br /><br />
**52. Znovupoužitie artefaktov pri evolúcii na úrovni komponentov** <br /><br />
**53. Znovupoužitie artefaktov pri evolúcii na úrovni aplikácií** <br /><br />
**54. Softvér typu E** softvér implementujúci reálne aplikácie sa neustále vyvíja, aby sa zachovala spokojnosť používateľov.<br /><br />
**55. Softvér typu P** <br /><br />
**56. Softvér typu S** Softvér založený na špecifikáciáci, Vedecký softvér, napríklad diferenciálne rovnice<br /><br />
**57. Ciele profilácie softvéru** hľadanie úzkeho hrdla, výkonnostných chýb, memory leakov,...<br /><br />
**58. Invazívne postupy profilácie** počas profilácie sa mení samotný kód, nyvýhoda-pridaním kodu na profiláciu je možné vytvoriť problém<br /><br />
**59. Neinvazívne postupy profilácie** kód je black box - profilácia prebieha sledovaním programu napr. vyťazenie procesora<br /><br />
**60. Správa a plánovanie verzií softvéru** <br /><br />
**61. Balenie komponentov pri ich znovupoužití** <br /><br />
**62. Balenie aplikácií pri ich znovupoužití** <br /><br />
**63. Evolúcia integrovaných systémov** <br /><br />
**64. Evolúcia vnorených systémov** <br /><br />
