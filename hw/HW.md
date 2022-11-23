# HW

## Generace Počítačů

Generace 0 
Mechanické nebo elektro mechanické počítače.
Velikost místnosti, cca. 10 operací za sekundu

Generace 1 (Kolem konce 2. WW)
ENIAC - Využití elektronek

![[ENIAC.png]]

Generace 2
Byly vynalezeny transistory, ale každý transistor byl vlastí součástka.
Ciže se už nejednalo o relay ani elektronky.

Generace 3
Intel napadlo transistory spojit rovnou už ve výrobě, a vznikly tím intergrované obvody.
SSI Small Scale Integration (Malá hustota integrace)

Generace 4
Integrované obvody s velikou hustotou integrace. LSI Large Scale Integration.
Intel Pentium - 2 mil. transistorů.

Generace 5 - Budoucí generace
Několik předpokladů:
- Quantové počítače
- Neuronové počítače
- Optické počítače (použití světla)

---

# Anatomie počítače

Typy komponentů:
- Integrované (Dedikované)
- Externí - Připojené pomocí USB nebo kabelu

Komponenty:
- Základní deska - Nacházejí se na ní všechny ostatní komponenty
	- Nachází se na ní 2 integrované obvody: North Bridge a South Bridge
	- North Bridge se nachází poblíž procesoru. Řídí rychlé periferie: CPU, RAM
	- South Bridge se nachází poblíž konektorů a řídí pomalé periférie: Sound Card, Network Card, Keyboard, **Hard disky a SSD**, CD Mech., atd...
	- Také se na ní nachází BIOS + CMOS nebo UEFI (Firmware), PCIE sloty, AGP slot pro grafickou kartu, slot na procesor, porty na externí periférie a ethernet, DIMM Slot pro paměť.
	- **From Factor** - Určuje velikost desky, musí se shodovat s form factorem skříně.
- CPU (Central Processing Unit) Procesor
	- Integrovaný obvod - Skládá se z transistorů a polovodičů
	- Strašně se zahřívají - Teplo jim škodí - Je potřeba je chladit
	- Intel jsou lepší v desetiných číslech
	- AMD jsou výkonější v operacích s celými čísly.
- RAM (Random Access Memory) Paměť
- GPU (Graphical Processing Unit) Grafická Karta
- Skříň
	- Na výšku (Tower)
		- Mini Tower
		- Midi Tower
		- Big Tower
	- Ležmo (Desktop)
		- Desktop
		- Mini Desktop
		- Slim Line
	- **Chasis**
		- Side panel / Deska
		- Chasis

Chlazení:
- Vzduchem
	- Aktivní - Nucené chlazení
	- Pasivní - Přirozené
- Vodou
- Dusíkem
- Olejem
- Peltierovi články (Peltierův jev)
- Heat Pipe -> Měděná trubka odvádí teplo k chladiči nebo větráku.
	- Využití v notebooku

RAM a ROM - Operační paměti
- Random Access Memory
- Read Only Memory
	- ROM Read Only Memory
	- PROM Programable Read Only Memory
	- EPROM Erasable Programmable Read Only Memory
	- EEPROM Electricaly Erasable Programmable Read Only Memory
	- FLASH - V Flash Drivech, SSD, SD kartách atd...
- SRAM - Static RAM
	- 2 Tranzistory se přepínají navzájem mezi 1 / 0 - Jako klopný obvod
- DRAM - Dynamic RAM
	- Kondenzátory
	- Refresh = Obnovování nabytí kondenzátorů
	- Jsou pomalejší než SRAM, protože během Refreshu buňky z ní nemohu čist ani do ní psát
	- Naopak je levnější, kapacitnější a lehčí konstrukčně.
- Paměťové moduly
	- Pamětě se lehce ohnuly, takže vznikly tzv. paměťové moduly, které na sobě měli paměťe, a celý modul by se zasunul do PC.
	- Typy paměťových modulů:
		- DIP
		- SIMM
		- DIMM memory - Používají se v PC
		- SODIMM - Menší než DIMM (Asi 2/3), používají se v notebooku
- Cache
	- Vyrovnávající, vysoce rychlá paměť, která se umístňuje mezi 2 zařízení s jinou rychlostí čtení/psaní.
	- Třeba mezi CPU a RAM

Moduly rozeznáváme podle buďto značky anebo podle počtu vývodů a zobáčků na straně modulu paměťi.

---

![[ATXpowerPinout.png]]

---

## Personal Notes

![[saddam-hussein-adobada.mp4]]
