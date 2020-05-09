# STM32 Red Pill sablon

Ez a projekt az STM32F103C8T6 mikrokontroller köré épült Red Pill fejlesztői panel használatát mutatja be VS Code-al.

A PCB-n 2 kristály is be van körve (HSE és LSE), illetve egy piros LED a PC13-as lábra.

A `SYS` fülön a Debug lehetőségek között a `Serial Wire` van engedéylezve, hogy működjön az RTT.

A board-ról [itt](https://stm32duinoforum.com/forum/wiki_subdomain/index_title_Red_Pill.html) lehet részletesebben is olvasni.

Az UART is be van konfigurálva, 9600 Bits/s sebességgel. Az `USART2_TX` láb a `PA2` láb.

## Képek a CubeMX részletes beállításairól

### Lábkiosztás
![Lábkiosztás](/img/CubeMX1.png)

### Órajel konfiguráció
![Órajel konfiguráció](/img/CubeMX2.png)

### Projekt beállítások
![Projekt beállítások](/img/CubeMX3.png)

### Kódgenerálás beállítások
![Kódgenerálás beállítások](/img/CubeMX4.png)

## VS Code beállítások
### Gyorsbillentyűk
- build: `Ctrl+B`
- clean: `Ctrl+R`
- debud: `F5`
- run: `F11`
- build & run: `F6`