# OPS

[[OS Timeline]]
[[OPS Opáčko na test]] 2.11.2022

Freeware - Programy zadarmo komerčně i nekomerčně, ale nesmíme jej měnit.

Public Domain - Tvůrce se vzdává všech práv

Bundleware - Balíšek softwaru, který má většinou jednu hromadnou licensi

Cardware - Výměnou za užívání programu máte poslat tvůrci pohlednici města.

Donationware - Je možné přispět programu ale není to povinné

Abandonware - Opuštěné programy, které už nejsou udržované tvůrcem - vývojáři už nebudou dbět na jeho licensy a je tedy možné s ním dělat co uživatel chce. Př:. MS-DOS

CC License - Několik typů licensí
CC License Attributes
- BY
- NC
- ND
- SA
- CC0 - CC verze Public Domain

Copyleft - Opak Copyrightu
- Cokoliv pod licensí typu Copyleft musí být vydáno pod licensí Copyleft

EULA - End User License Agreement

Př. licensí: BSD, GPL, CC, MIT, EULA, UnLicense, atd...

OEM - Original Equipment Manufacturer - CD ke kterému je několik licensí, určených pro výrobce PC.
Volume - MultiLicense softwaru pro několik počítačů najednou.
Plovoucí license - Pomocí licenšního serveru se může spustit jenom určitý počet zařízení s daným softwarem.

! Program může mít více licensí a lze je kombinovat

**Autorský zákon** - V ČR Zákon č. 121 / r. 2000 Sb. ve znění pozdějších předpisů

---

## OS

Přípony souborů systému windows
- 8 + . + 3 => 8 písmen jména soubru, 3 písmena přípony

### PC
- Windows
- MacOS
- Linux
- BSD
- UNIX

![[NOS Struktura.png]]

### Mobile
- Android
- iOS
- Blackberry OS
- Harmony OS

### Funkce OS
- Správa paměti
- Správa úložiště?
- Správa uživatelských účtů
- Správa zařízení (a driverů)
- Uživatelské rozhraní (UI)
- Multitasking (Procesy a Úlohy)
- Virtualizace

---

## Výber vhodného OS

- Záleží na žádaných funkcích a účelu
- Životní cyklus = Life Cycle
- Cena - je potřebná zvážit i ceny za třeba podporu, aktualizace atd... = Náklady
- Náročnost pro uživatele

### Windows
- 3 - 5 Years release cyncle
- Long Maintaince Cycle
- Backwards Compatability

### Apple macOS
- Only runs on Apple hardware
- Server version adds packages to the desktop version to aid in management and sharing.

### Linux
- Depends on the distribution
- Some focus on Desktops, some on Servers, there are some for Phones, others for Network or Scientific purposes.
- Some of them offer commercial support - most is volunteer based

#### Linux Decision Points
- Role: What purpose do we need the system for?
- Function: What functions and features do we need? Eg: Security or Usage
- Life Cycle: How often can/should we update the system?
- Stability: Which branch do we want to use? (Stable, Testing, Unstable)
- Compatibility: You can pay for optional support - Enterprise users can pay for support or attempt self support.
- *Linux from scratch*

#### Linux Distros (A few of them at least)
- RHEL
- CentOS - Free RHEL Version (Without Commercial Support)
- Scientific Linux
- SUSE - Derived from Slackware, is sold as a server product, contains proprietary code
- OpenSUSE - Completly open and free version with multiple desktop packages
- Debian - Invented the APT package managment system; Community effort to promote open source software.
- Ubuntu - Most popular derived distribution (derived from Debian)
- Linux Mint - Derivate of Ubuntu; Designed to look the most like windows with the Cinamon DE.
- Raspbian - Derivate of Debian for the Raspberry Pi (RaspberryPi OS Since RP4)
- Android - OS for Mobile devices

---

## Zabezpečení OS

- Cookies - Na webu slouží k ukládání dat v prohlížeči. Slouží například pro ukládání přihlášení na stránkách. Také se ale dají použít pro sledování uživatele.
- Hesla
	- Hesla by měli být pestré - Obsahovat velká, malé písmena, čísla a znaky (@, #, $, ...)
	- Hesla by se neměli používat opakovaně na více stránkách, měly by být unikátní. Jenže problém je potom si je zapamatovat - na to lze použít password manager.
	- Heslo o délce 4 s velkími, malími písmeny a čísly má kolem 15 miliómů možných kombinací.
	- S novými výkonými GPU se zrychlylo crackování hesel pomocí Bruteforcu. Hesla by se měli měnit každý měsíc nebo 2, aby bylo těžší je uhádnout.

---

### Personal Notes
In windows `con:` is the console device.
Eg: `copy con: filename.txt`
`Ctrl + Z` = EOF

![[kebab.mp4]]